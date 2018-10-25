# helloworlds c++

#include <iostream>
 
using namespace std;

int main()
{
  cout<<"HEY, you, I'm alive! Oh, and Hello World!\n";
  cin.get();
  
  return 1; //lets OS know code is completed
}
 
int main()
{
  int thisisanumber;
 
  cout<<"Please enter a number: ";
  cin>> thisisanumber; //user input is var
  cin.ignore(); //ignores enter
  cout<<"You entered: "<< thisisanumber <<"\n"; //output to user
  cin.get();
}

 
