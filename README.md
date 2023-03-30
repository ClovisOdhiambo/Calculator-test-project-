# Calculator-test-project-
#include<stdio.h>
int main()
{
    double num1,num2,result;
    char operator;
     printf("Enter Arithmetic Operator:");
    scanf("%c", &operator);
    printf("Enter First Number:");
    scanf("%lf", &num1);
    printf("Enter Second Number");
    scanf("%lf", &num2);
   

    switch (operator)
    {
    case '+':
        result=num1+num2;
        printf("Result:%.2lf %c %.2lf=%.2lf", num1, operator, num2, result);
        break;
     case '-':
        result=num1-num2;
        printf("Result:%.2lf %c %.2lf=%.2lf", num1, operator, num2, result);
        break;
     case '*':
        result=num1*num2;
        printf("Result:%.2lf %c %.2lf=%.2lf", num1, operator, num2, result);
        break;
     case '/':
        result=num1/num2;
        printf("Result:%.2lf %c %.2lf=%.2lf", num1, operator, num2, result);
         break;
     default:
        printf("Enter a valid operator!!");
        break;
    }
    return 0;

}
