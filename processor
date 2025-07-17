#include <iostream>
#include <windows.h>
#include <ctime>

using namespace std;

int main()
{
      int a=0, b=2, c=3;
      double t1 = clock();
      for(int i=0; i<100000000; i++)
      {
            a += 1;
       }
      double t2 = clock();
      double time1 = (t2-t1)/CLOCKS_PER_SEC;
      cout << time1 << endl;
      double t3 = clock();
      for(int i=0; i<100000000; i++)
      {
            c += 1;
            b += c;
      }
      double t4 = clock();
      double time2 = (t4-t3)/CLOCKS_PER_SEC;
      cout << time2 << endl;
      double result = 1/((time2-time1)/ 100000000);
      cout << result << " Ghz" << endl;
      return 0;
}
