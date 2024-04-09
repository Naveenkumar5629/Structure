# Structure
#include<stdio.h>
struct student{
    int roll;
    char a[20];
    float marks;
};
int main(){
    struct student st1;
    scanf("%d%s%f",&st1.roll,&st1.a,&st1.marks);
    printf("%d%s%f",st1.roll,st1.a,st1.marks);
}
