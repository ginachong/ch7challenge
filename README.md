//Program to find a baseball palyer's batting average.
//Display batting average to 3 decimal places.

//-------------------------------------------------------------------------------------------

#include <iostream>
#include <iomanip>
using namespace std;

int main()
{
  double timesAtBat, hits;

  cout << "Enter the number of times player was at bat: ";
  cin >> timesAtBat;
  cout << "Enter player's number of hits: ";
  cin >> hits;

  cout << setw(15) << left << "Times at Bat" << setw(15) << "Hits" << setw(15) << "Batting Average" << endl;
  cout << setw(15) << timesAtBat << setw(15) << hits;
  cout << fixed << showpoint << setprecision(3);
  cout << setw(15) << hits/timesAtBat << endl;

  return 0;
}

