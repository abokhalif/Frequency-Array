# Frequency-Array
#include <iostream>
//#include<algorithm>
using namespace std;

int main()
{
	int size,count;
	cin >> size>>count ;
	int arr[1000001]={0};//we create the array that has the counter of num
	for (int i = 0; i < size; i++)
    {
			int num;
			cin >> num;
			arr[num]++;//we increase the num , if we input number this number consider it as an index and the array has how many it repeated
	}
	for (int i = 1; i <= count; i++)
		cout << arr[i] << endl;
	


}
