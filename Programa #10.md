    #include <string>
    #include <iostream>
    #include <stdio.h>
    using namespace std;
    
    /** PROGRAMA #10  
    *ESTE PROGRAMA TE IMPRIME LA TABLA QUE TU PIDAS HASTA EL NUMERO 12!!
    *Alumno: VILLA LLANES JUAN SEBASTIAN - 19211752
    *Dia: 23/03/2022 **/

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
