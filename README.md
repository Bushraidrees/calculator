# calculator
#include<iostream>
using namespace std;
int main()
{
char a;
float number1,number2;
cout<<"Enter operator either + or - or * or / :";
cin>>number1>>number2;
switch(a){
case'+':
cout<< number1+number2;
break;
case'-':
cout<< number1-number2;
break;
case'*':
cout<< number1*number2;
break;
case'/':
cout<< number1/number2;
break;
default:
cout<<"Error";
break;
}
return 0;
}
