#include <iostream>
#include <fstream>
#include <conio.h>

using namespace std;

class pishro{

public:

    void submit(){

   ofstream p1("pishro.dat",ios::app);
if(p1){
    cout<<"error";

    exit(0);
}
while(true){
string s;
cin>>s;
 ifstream p2("pishro.dat");
if(p2){
    cout<<"error: UserRepeated ";
       exit(0);
}
string c;
p2>>c;
p2.

p1.close();



close();

    }

    void login(){
      cout<<"error";
    }
};


int main()
{


//cout<<endl<<"***********************"<<endl<<"Enter:";
//pishro reza;
//string x;
//cin>>x;
//if(x=="submit"){
//
//reza.submit();
//}
//else if(x=="login"){
//reza.login();
//}
//else{
//    cout<<"error";
//}
    return 0;
}
