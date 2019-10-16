# taks2
#include<stdio.h>
int main()
{
	int sum;
	scanf("%d",&sum);
	if(sum>0&&sum<101)
	{
			if(sum >= 90)
				printf("Excellent%d",sum);
			else if(sum >= 80)
				printf("good%d",sum);
			else if(sum >= 70)
				printf("middle%d",sum);
			else if(sum >= 60)
				printf("passed%d",sum);
			else 
				printf("fail%d",sum);
						
	}
}
