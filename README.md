#include <stdio.h>
#include <math.h>
int main(){
	float base ;
	float high ;
	float radius ;
	float side ;
	
	printf("Area Triangle Calculator\n") ;
	printf("\nEnter high = ") ;
	scanf("%f", &high) ;
	printf("\nEnter base = ") ;
	scanf("%f", &base) ;
	printf("\nArea Triangle = %.2f\n",base*high/2) ;
	printf("\n--------------------------------\n\n") ;
	
	printf("Area Circle Calculator\n") ;
	printf("\nEnter radius = ") ;
	scanf("%f", &radius) ;
	printf("\nArea Circle = %.2f\n",M_PI*(radius*radius)) ;
	printf("\n--------------------------------\n\n") ;
	
	printf("Area Square Calculator\n") ;
	printf("\nEnter side = ") ;
	scanf("%f", &side) ;
	printf("\nArea Square = %.2f\n", side*side) ;
	
	return 0 ;
}
