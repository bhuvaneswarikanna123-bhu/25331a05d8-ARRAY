# 25331a05d8-ARRAY
#include <stdio.h>
void display array(int arr[],int size);
int main(){
int numbers[5]={10,20,30,40,50};
 display array(numbers[5]);
return 0;
}
void display array(int arr[],int size){
int i;
printf("array elements are:\n");
for(i=0;i < size;i++){
printf("%d",arr[i]);
}
printf("\n");
}
