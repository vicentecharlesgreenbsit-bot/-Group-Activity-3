# -Group-Activity-3

#include <iostream>

using namespace std;

int main() {
    int hours, minutes;
    
   cout << "Expected Output:\n ";
  
   cout << "Input hours: ";
   cin >> hours;
  
   cout << "Input Minutes: ";
   cin >> minutes;
   
   int totalMinutes = (hours * 60) + minutes;
   
   cout << "Total: " << totalMinutes << "Minutes" << endl;
   
    return 0;
}
