    #include <string>
    #include <iostream>
    #include <stdio.h>
    using namespace std;
    
    /** PROGRAMA #9  
    *ESTE PROGRAMA TE DICE SI UN NUMERO ES MULTIPLO DE 6!!
    *Alumno: VILLA LLANES JUAN SEBASTIAN - 19211752
    *Dia: 23/03/2022 **/

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
