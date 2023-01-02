#include<iostream>
using namespace std;
int a,b,c;

class raj
{
    
   };
int nahi()
{
cin>>a>>b>>c;
	int d,h;
    d=a+b+c;
    cout<<d<<"="<<a<<"+"<<b<<"+"<<c;
    //using of and operator
    if((d=0)||(d>0))
    {
        cout<<"NUMBER IS POSITIVE";
        
    }
    else
    {
        cout<<"NUMBER IS NEGATIVE";
    }
    h=a-b-c;
    cout<<h<<"="<<a<<"-"<<b<<"-"<<c;
    //using of and operator
    if(!((h=0)||(h<0)))
    {
        cout<<"NUMBER IS POSITIVE";
        
    }
    else
    {
       cout<<"NUMBER IS NEGATIVE";
    }
}
int pata()
{
	int e;
    e=a*b*c;
    cout<<e<<"="<<a<<"*"<<b<<"*"<<c;
    if(e%2==0)
    {
        cout<<"NUMBER IS EVEN";
    }
    else
    {
    	 cout<<"NUMBER IS ODD";
	}
	
	
     
    
}
int kaha()
{
	int f,g;
     f=a/b;
    cout<<f<<"="<<a<<"/"<<b;
     g=a%b;
    cout<<g<<"="<<a<<"%"<<b;
}
int main()
{
    
    nahi();
    pata();
    kaha();
    return 0;
}
