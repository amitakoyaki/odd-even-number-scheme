//Name:Fatima Dayego
//Activity: Performance Task 1
//Year and Section:BSIE 1-1

#include<iostream>

using namespace std;

int main(){
char choice;
int num,x,numbers;

do {
    cout << "     ~~~~~~~~~~~~~~~~~~~~~~~~~~" << endl;
    cout << "     | WELCOME TO MY PROGRAM! |" << endl;
    cout << "     ~~~~~~~~~~~~~~~~~~~~~~~~~~" << endl;
   
    cout << "\n Enter the range of the numbers: ";
    cin >> num;
    cout << "\n Enter the " << num << " consecutive numbers: " ;
    cin >> numbers;

    cout << endl;

x=1;

while(x <= num){
    if(x % 2 == 0){
        cout << x;
                cout << " - Even number";
        cout << endl;
    }
    else{
        cout << x;
                cout << " - Odd number";
        cout << endl;        
    }
     x++;

    }

  cout << endl;
  cout << "~`~`~`~`~`~`~`~`~`{ Thank you for using the program!}`~`~`~`~`~`~`~`~`~`~`~`~`~`~`" << endl;
  cout << endl;
  cout << "Would you like to try again?: ";
  cin >> choice;
} while (choice == 'Y' || choice == 'y'); 

return 0;
}
