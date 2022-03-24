    #include <string>
    #include <iostream>
    #include <stdio.h>
    using namespace std;

    /** PROGRAMA #1  
    *ESTE PROGRAMA CONTIENE UN CICLO FOR Y UNA CONDICION IF QUE HACE QUE TE IMPRIMA LOS NUMEROS PARES DEL 2-48!
    *Alumno: VILLA LLANES JUAN SEBASTIAN - 19211752
    *Dia: 23/03/2022 **/
    
     int main()
     {
        float a;
        for (int i = 2; i <= 48; i++)
        {
            a = i % 2;
            if (a == 0)
            {
                cout << i << endl;
            }

         }
      }

