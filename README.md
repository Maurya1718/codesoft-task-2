# codesoft-task-2
ta#include<bits/stdc++.h>
using namespace std;
int a,b;
void inputdata()
{
    cout << " Enter two numbers ";
    cin >> a >> b;
}
 void calculate()
    {
char op;
cout << "+ - * /\n";
cout << "Enter the operator";
cin  >> op;

switch(op)
{
    case '+' : cout << " Result "<< a+b;
    break;
    case '-' : cout <<"Result "<< a-b ;
    break;
    case '*' : cout << "Result "<< a*b ;
    break ;
    case '/' : cout << "Result " << a/b ;
    break ;
    default : cout << "invalid choice ";
    break ;


}


    }
    int main(){
        inputdata();
         calculate();

    }sk 2
