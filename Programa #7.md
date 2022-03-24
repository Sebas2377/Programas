    #include <string>
    #include <iostream>
    #include <stdio.h>
    using namespace std;
    
    

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
