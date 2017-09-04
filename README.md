
#include <iostream>
using namespace std;

int main() {

	int t;
	long long int g,l;
	bool check= false;
	cin>>t;
	while(t--){
		cin>>g>>l;
		if(l%g==0){
			cout<<min(g,l)<<" " << max(g,l)<<endl;
		}else {
			cout<<-1<<endl;
		}
	}
	

	return 0;
}
