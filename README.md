# pointValues

#include<iostream>
using namespace std;

int main()
{ 
    int i;
    string *u;
    string arr[5];
    cout<<"ENTER ELEMENTS :\n";
    u=arr;
    for(i=0;i<5;i++)
    {
    cin>>*u;
    u++;
    } 
    cout<<"YOU ENTERED :\n";
    for(i=0;i<5;i++)
    {
    cout<<arr[i]<<"\n";
    }
    
    return 0;
}
