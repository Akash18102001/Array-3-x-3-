#include<stdio.h>

main()
{
	int arr[3][3],i,j;  //Declaration of an array

	for(i=0;i<3;i++)
	{
		for(j=0;j<3;j++)
		{
			printf("\n Enter the element[%d][%d] : ",i,j);
			scanf("%d",&arr[i][j]);  //Scanning and storing the input
		}
	}
	
	printf("\n The matrix is : \n");//printing the matrix
	for(i=0;i<3;i++)
	{
		printf("\n");
		
		for(j=0;j<3;j++)
		{
			printf("%d\t",arr[i][j]);
		}
		
	}
}
