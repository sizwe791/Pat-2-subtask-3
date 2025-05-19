#include #include using namespace std;

const int NUM_EXPERIMENTS = 3;
const int NUM_READINGS = 3;

int main() {
    int i, j; // corected types to int 
    double readingValue, total, average;

    for (i = 1 <=Num_EXPERIMENTS; i++) {
         total = 0; 
         cout << "\nEXPERIMENT " << i <<
endl;
         cout << "===================\n";

         for (j = 1; j <= NUM_READINGS; j++)
            cout << "Enter reading " <<j<<
"Value: ";
          cin >>readingValue;
