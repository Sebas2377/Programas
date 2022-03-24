    #include <string>
    #include <iostream>
    #include <stdio.h>
    using namespace std;
    
    /** PROGRAMA #2  
	*ESTE PROGRAMA CONTIENE UN CICLO FOR Y UNA CONDICION IF QUE HACE QUE TE IMPRIMA LOS NUMEROS IMPARES DEL 7-52! 
	*Alumno: VILLA LLANES JUAN SEBASTIAN - 19211752
	*Dia: 23/03/2022 **/

    int main()
    {
  
      for (int i = 7; i < 52; i++)
	    {
		      if (i & 1)
		    {
			    cout << i << endl;
		    }

	    }
    }

