    #include <string>
    #include <iostream>
    #include <stdio.h>
    using namespace std;
    
    /** PROGRAMA #1  
    *ESTE PROGRAMA TE MUESTRA SI UNA DIVISION ES DIVISIBLE O NO LO ES!
    *Alumno: VILLA LLANES JUAN SEBASTIAN - 19211752
    *Dia: 23/03/2022 **/

    int main()
    {;

            int a, b, c;
            printf("Ingrese 2 numeros: \n");
           cin >> a;
           cin >> b;
            c = a % b;
            if ((b < a) && (c == 0)) {
                printf("Es DIVISIBLE\n");
            }
            else
            {
                printf("No es DIVISIBLE\n");
            }

            return 0;

    }
