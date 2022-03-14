//Food-choice
#include<stdio.h>
int main()
{
	int choice;
	printf("enter your choice \n1.Pizza:Rs 239 \n2.Burger:Rs 129 \n3.Pasta:Rs 179 \n4.French Fries:Rs 99 \n5.Sandwich:Rs 149");
	scanf("%d", &choice);
	switch (choice)
	{
	case 1:
		printf("Food item- pizza\n");
		printf("Price: Rs. 239");
		break;
	case 2:
		printf("Food item- Burger\n");
		printf("Price: Rs. 129");
		break;
	case 3:
		printf("Food item- Pasta\n");
		printf("Price: Rs. 179");
		break;
	case 4:
		printf("Food item- French Fries\n");
		printf("Price: Rs. 99");
		break;
	case 5:
		printf("Food item- Sandwich\n");
		printf("Price: Rs. 149");
		break;
	default : printf("invalid choice");
    }
	return 0;
 } 
