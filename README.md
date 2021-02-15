# Lab-18.30-
#include <iostream>
using namespace std;


 void coinToss() {

   double side;
   side = rand () % 2 + 1;
   if (side == 1) 
   cout << "Heads " << side << endl;
   else 
   cout << "Tails " << side << endl;
 }
int main() {
  int numOfTosses;
  cout << "How many times would you like to flip the coin: " << endl;
  cin >> numOfTosses;
  srand (time(NULL));
  for (int t = 1; t <= numOfTosses; t++)
  coinToss();
}
 








