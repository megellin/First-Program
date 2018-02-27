# First-Program

  #include <stdio.h>

int main()
{
	int num1, num2, num3;
	int product;


	printf("Please enter the first integer number: ");
	scanf("%d%*c", &num1);

	printf("Please enter the second integer number: ");
	scanf("%d%*c", &num2);

	printf("Please enter the third integer number: ");
	scanf("%d%*c", &num3);

	product = num1 + num2 + num3;

	printf("The product of the three numbers is: %d\n", product);

	return(0);
}

