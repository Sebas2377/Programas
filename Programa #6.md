    #include <string>
    #include <iostream>
    #include <stdio.h>
    using namespace std;
    
    

    int main()
    {;

      //PRIMERA CONVERSION
      double pulg, yard;
      cout << " \nEscriba la cantidad de Pulgadas que desea convertir a Yardas: " << endl;
      cin >> pulg;
      yard = pulg * 0.0277778;

      cout << "\nEste es el resultado de la Conversion: " << yard << endl;

      //SEGUNDA CONVERSION

      double pies;
      cout << " \nEscriba la cantidad de Pies que desea convertir a Pulgadas: " << endl;
      cin >> pies;
      pulg = pies * 12;

      cout << "\nEste es el resultado de la Conversion: " << pulg << endl;

    }
