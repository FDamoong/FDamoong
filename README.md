#include <iostream>
#include <string>

using namespace std;

double double_subtract_function(double a, double b)
{
    return a - b;
}

double double_add_function(double a, double b)
{
    return a + b;
}
double double__Divide_function(double a, double b)
{
    return a / b;
}

double double_Multiply_function(double a, double b)
{
    return a * b;
}

int int_subtract_function(int a, int b)
{
    return a - b;
}

int int_add_function(int a, int b)
{
    return a + b;
}
int int_Divide_function(int a, int b)
{
    return a / b;
}
int int_Multiply_function(int a, int b)
{
    return a * b;
}

int main()
{
   double double_val1 = 0, double_val2 = 0;
 
    cout << "???";
   cin >> double_val1 >> double_val2;
   cout << "subtract = " << double_subtract_function( double_val1, double_val2) << endl;
   
   cout << "add = " << double_add_function( double_val1, double_val2) << endl;

   cout << "Divide = " << double__Divide_function( double_val1, double_val2) << endl;

   cout << "Multiply = " << double_Multiply_function( double_val1, double_val2) << endl;
   
   int int_val1 = 0, int_val2 = 0;
    cout << "???";
   cin >> int_val1 >> int_val2;
  
   cout << "subtract = " << int_subtract_function(int_val1, int_val2) << endl;
   
   cout << "add = " << int_add_function(int_val1, int_val2) << endl;
   
   cout << "Divide = " <<int_Divide_function(int_val1, int_val2) << endl;
   
   cout << "Multiply = " <<  int_Multiply_function(int_val1, int_val2) << endl;
    return 0;
}

