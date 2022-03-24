    #include <string>
    #include <iostream>
    #include <stdio.h>
    using namespace std;
    
    /** PROGRAMA #5  
    *ESTE PROGRAMA TE IMPRIME LA TABLA DE POTENCIAS DEL 2 SIN EXCEDER EL NUMERO 1000!!
    *Alumno: VILLA LLANES JUAN SEBASTIAN - 19211752
    *Dia: 23/03/2022 **/


    int main()
    {
        int i;

        printf("\n   ");

        for (i = 1; i <= 9; i++)
        {
            printf("%.f ", pow(2, i));
        }
        return 0;
    }

