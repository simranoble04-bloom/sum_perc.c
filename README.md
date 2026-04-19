/*WAP that accepts the marks of five subjects and finds
 the sum and percentage of marks obtained by the students*/ 

#include <stdio.h>

int main(){
    float s1, s2, s3, s4, s5, sum=0, per;

    printf("Enter marks of subject 1: ");
    scanf("%f", &s1);
    printf("Enter marks of subject 2: ");
    scanf("%f", &s2);
    printf("Enter marks of subject 3: ");
    scanf("%f", &s3);
    printf("Enter marks of subject 4: ");
    scanf("%f", &s4);
    printf("Enter marks of subject 5: ");
    scanf("%f", &s5);

    sum = s1 + s2 + s3 + s4 + s5;
    per = (sum/500)*100;

    printf("Sum of 5 subjects : %f\n", sum);
    printf("percentage of student: %f\n", per);

    return 0;
}

