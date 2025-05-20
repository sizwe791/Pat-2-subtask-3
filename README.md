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
          total += readingValue; // fixed wrong operation 
          }
          average = total / NUM_rEADINGS; // fIXED AVERAGE CALCULATION 

           // InCORPORATE EVALUATION LOGIC DIRECTLY 
           cout << fixed << setprecision(2); // set decimal formating 
           if (average < 100) {
                cout << "Exipereiment" <<i<< "
            average: " << average 
                             << " is Within acceptable range \n";
           } else if (average >= 100 && average <=300){
             cout << "Exiperiment " <<i<< "
             average: "<< average
                               << " is within acceptable range\n"
            }else {
            cout <<" Exiperement "<<i<<"
            average: "<< average 
                             << " is Above acceptable range \n";
            }
            }
            return 0;
            }
