    #include <string>
    #include <iostream>
    #include <stdio.h>
    using namespace std;
    
    

    int main()
    {;
      int numero;
      do {
        cout << "INGRESE UN NUMERO: ";
        cin >> numero;

      } while ((numero < 1) || (numero > 12));

      for (int i = 1; i <= 12; i++) {
        cout << numero << " * " << i << " = " << numero * i << endl;
      }
      return 0;
    }
