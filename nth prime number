#include<stdio.h>
int main()
{
    int n,i,j=0,arr[1000],x=0,c=1;
    float z;
    while(c==1)
    {
        printf("enter N : ");
        if(scanf("%f",&z))
        {
            n=z;
            if(n>0 and n==z)
            {
                for(i=2;i<1000;i++)
                {
                    if(i==2 or i==3 or i==5 or i==7 )
                    {
                        j=j+1;
                        arr[x]=i;
                        x=x+1;
                        if(j==n)
                        {
                        	printf("%dth prime number  : %d" ,n,i);
                    
						}
				    }
				    else if(i%2!=0 and i%3!=0 and i%5!=0 and i%7!=0)
			        {
					    j=j+1;
						arr[x]=i;
						x=x+1;
						if(j==n)
						{
							printf("%dth prime number  : %d",n,i);
	     				}
	     				
				    }
				    else
				    {
				    	continue;
					}
			    }
			    printf("\n%d prime numbers after %dth prime number = ",n,n);
			    for(int m=n;m<=(2*n)-1;m++)
			    {
			    	printf("%d",arr[m]);
				}
		    
			}
			else
			{
				printf("\ninvalid");
		    }
	    }
	    else
	    {
	    	printf("\ninvalid");
		}
		printf("\nenter 1 to continue: ");
		scanf("%d",&c);
    }
}
