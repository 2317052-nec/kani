#include <stdio.h>    
#include <stdlib.h>   
     
int t7(int i,int j,int k){    
    return (i+j+k);
}

int main(){ 
     
int a,b,c;  
printf("This program adds three integer values.\nPlease enter three integers separated by a space:\n"); 
scanf("%d %d %d\n",&a,&b,&c);   
printf("The result of %d+%d+%d is %d\n",a,b,c,t7(a,b,c)); 
     
}