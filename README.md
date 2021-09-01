# massa
#include <iostream>
using namespace std;
int main (){
	
	int fr = 200;
	int m = 20;
	int a = 20;
	
	fr = m * a;
	a = fr / m;
	
	cout << "força resultante: " << fr << "\n";
	cout << "aceleracao: " << a;
	
	return 0;
}
