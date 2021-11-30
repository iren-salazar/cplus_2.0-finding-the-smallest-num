# cplus_2.0-finding-the-smallest-num
the easy version of finding the smallest num among the entered num.


#include <iostream>
using namespace std;
int main ()
{
    int num;
    int num1, num2, num3, num4, num5;
    int smallestNum;

    cout << "Salazar, Iren Mercado" << endl;
    
    
    cout << " Enter a number: " << endl;
    cin >> num1;
    smallestNum = num1;
    
    cout << "Enter a number: " << endl;
    cin >> num2;
    while (num2 < smallestNum)
    {
      smallestNum = num2;
    }
    cout << "Enter a number: " << endl;
    cin >> num3;
    while (num3 < smallestNum) 
    {
      smallestNum = num3;
    }
    cout << "Enter a number: " << endl;
    cin >> num4;
    while (num4 < smallestNum)
    {
      smallestNum = num4;
    }
    cout << "Enter a number: " << endl;
    cin >> num5;
    while (num5 < smallestNum) 
    {
      smallestNum = num5;
    }
    cout << smallestNum << " is the smallest number." << endl;
    return 0;
}
  /*output:
  
  Salazar, Iren Mercado
 Enter a number: 
23
Enter a number: 
23
Enter a number: 
45
Enter a number: 
56
Enter a number: 
65
23 is the smallest number. */                                                             
                                                             
