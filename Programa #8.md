    #include <string>
    #include <iostream>
    #include <stdio.h>
    using namespace std;
    

    int main()
    {;
      int x;
      cout << "Ingresa algun numero: " << endl;
      cin >> x;

      if (x % 6 == 0)
      {
        cout << " El numero " << x << " Es multiplo de 6" << endl;
      }
      else
      {
        cout << " El numero " << x << " No es multiplo de 6" << endl;
      }

    }
