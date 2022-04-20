#include<iostream>
using namespace std;
	int main(){
		int x , y , *xptr , *yptr;
		
		cout << "\n Please Enter the Values of x  = " ;
		cin >> x;
		
		cout << "\n Please Enter the Values of x  = " ;
		cin >> y;

		xptr = &x;
		yptr = &y;
		
		
		if ( *xptr > *yptr ) {
			cout << "\n x is greater than y";
		}
		else {
			cout << "\n y is greater than x";
		}
		
		return 0;
		
		}
