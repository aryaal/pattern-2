In this program outer loop is for printing the rows.Here number of rows is taken as 5.Therefore n=5.

                for(int i=1;i<=n;i++)
                
Inside outer for loop one more for loop is used to print the spaces.Take a variable j which starts with i value ang goes till n.
              for(int j=i;j<n;j++)
			        {
			            	System.out.print(" ");
                    
             }
For printing star one more for loop is taken.Here one more variable k is taken which starts from 1 and goes till (2*i-1).
                for(int k=1;k<=(2*i-1);k++)
                
 A condition is given if k==1 or i==n or k==(2*i=1) then print star.If the condition is false then print space.
 
        if(k==1||i==n||k==(2*i-1))
				{
					System.out.print("*");
				}
	  	else
				{
					System.out.print(" ");
				}
		Print statement is for printing next line .
        System.out.println();
