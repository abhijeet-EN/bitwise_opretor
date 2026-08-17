bitwise_opretor
#include<stdio.h>
int main()
{
	int a=5;
	int b=10;
	int c=15;
	printf("%d",a&b);
	printf("\n %d",a&&b);
	printf("%d",!a);
	printf("\n %d",~a);
	if (a&1){
		printf("odd");
	}
	else{
		printf("even");
	}
	printf("%d \n %d\n ",a,b);
	a=a^b;
	b=a^b;
	a=a^b;
	printf(" %d\n ",a);
	printf("%d",b);
	printf("%d\n",a<<1);
	printf("%d\n ",a<<2);
	printf("%d\n",a>>1);
	printf("%d\n",a>>2);
	a<b?printf("a is small"):printf("a is great");
	a%2==0?printf("num is even "):printf("num is odd");
	printf("%d \n",++a);
	printf("%d\n",a++);
	printf("%d\n",--a);
	printf("%d\n",a--);
int z=a++ + ++a + a++;
int y=(a-- )+ (--a )+ (a--);
printf("%d",z);
printf("%d",y);

}
