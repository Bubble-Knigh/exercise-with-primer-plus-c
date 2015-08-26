#define _CRT_SECURE_NO_WARNINGS
#include<stdio.h>
#include<process.h>
int main(void)
{
	float in, cm, c;
	c = 0.3937008;
	printf("你的身高(cm)是：");
	scanf("%f",&cm);
	printf("换算成英寸后是%.2fin\n",in=cm*c);
	system("pause");
	return 0;

}
