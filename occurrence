	void Count(FILE *data,int T[26][2])
	{
	    char caractere;
	   while( ( caractere =(int) fgetc(data) ) != EOF )
	     {  //printf("%c-%d\n",caractere,caractere);
	
	
	         if(caractere<91 && caractere>64)
	        {//printf("%d\n",T[(caractere)-65][1]);
	        T[caractere-65][1]++;
	        T[caractere-65][0]=caractere-65;
	        }
	        if(caractere<123 && caractere>96)
	        {printf("%d\n",T[caractere-97][0]);
	        printf("%d\n",T[caractere-97][1]);
	        T[caractere-97][1]++;}
	     }
	
	
	}
