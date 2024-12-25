#include<iostream>
using namespace std;

int main(){
	cout<<"how you old :";
	int age;
	cin>>age;
	if(age<13){
	
	cout<<"you are not enoug "<<endl;
		}	
	else if(age<19){
		cout<<"you are almost 19 age"<<endl;
	}
	else{
		cout<<"flase"<<endl;
	}
	
}
#include<iostream>
#include<string>
using namespace std;

int main(){
	
	string answer = "sawera";
	string gusess;
	cout<<"gusess my name:";
	cin>>gusess;
	if(gusess == answer){
		cout<<"you are right";
	}
	else{
		cout<<"you are not right";
	}
}
