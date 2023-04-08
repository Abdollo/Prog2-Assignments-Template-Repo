/*Abdallah Ahmed
  202106164*/

#include <iostream>
using namespace std;

int main()
{
	int x;
	cin >> x;
	int result = x / 1000;
	if (result % 2 == 0)
		cout << "EVEN";
	else
		cout << "ODD";

}


