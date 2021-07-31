#include<stdio.h>
float summing(int x,int y,int z){
	return x+y+z;
}
int main(){
	int x,y,z;
	printf("enter three numbers\n");
	scanf("%d%d%d",&x,&y,&z);
	int P=summing(x,y,z);
	printf("sum is %d",P);
}
