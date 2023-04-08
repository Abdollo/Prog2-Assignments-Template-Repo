/*Abdallah Ahmed
  202106164*/

#include <iostream>
using namespace std;

int main()
{
	int x, y, z;
	cin >> x >> y >> z;
	int arr[] = { x,y,z };
	int unsorted[] = { x,y,z };
	int temp;
	for (int i = 0; i < 3; i++) {
		for (int j =i+ 1; j <3; j++) {
			
				if (arr[i] > arr[j]) {
					temp = arr[i];
					arr[i] = arr[j];
					arr[j] = temp;
				}
		}
	}
	for (int i = 0; i < 3; i++) {
		cout << arr[i] << endl;
	}
	cout << endl;
	for (int i = 0; i < 3; i++) {
		cout << unsorted[i] << endl;
	}
}


