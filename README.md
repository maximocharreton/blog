en este blog compartire algunos de los trabajos realzados en clase, EL PRIMER EJECICIO QUE COMPARTIRE ES COMO APRENDIMOS A DECLARAR CUANTOS BYTES TIENE CADA FUNCION 
/*autor: MAXIMO CHARRETON 

fecha:04/02/2025

Objetivo: Obtener el tamaño en bytes de las variables */

#include <stdio.h>
 
int main()

{	//Zona de declaración de variables 

	char c;
    short s;
	int i;
    long l;
    long long ll;
    float f;
    double d;
    long double ld;
	int tamano;
	tamano=sizeof(c);
	printf("char ocupa %lu byte porque representa un solo carácter.\n",tamano);
	tamano=sizeof(s);
	printf("short ocupa %lu bytes, generalmente usado para números pequeños.\n",tamano);
	tamano=sizeof(i);
	printf("int ocupa %lu bytes, el tamaño estandar para enteros.\n",tamano);
	tamano=sizeof(l);
	printf("long ocupa %lu bytes, permitiendo valores enteros más grandes.\n",tamano);
	tamano=sizeof(ll);
	printf("long long ocupa %lu bytes, usando valores aun mas grandes.\n",tamano);
	tamano=sizeof(f);
	printf("float ocupa %lu bytes, para numeros con punto decimal de precision simple.\n",tamano);
	tamano=sizeof(d);
	printf("double ocupa %lu bytes, para precision doble en punto flotante.\n",tamano);
	tamano=sizeof(ld);
	printf("long double ocupa %lu bytes, para mayor precision de calculos.\n",tamano);


}








 /*
autor: maximo charreton 
fecha: 30/01/2025
objetivo: imprimir variables enteras 
*/
#include <stdio.h>
#include <math.h> // para usar la funcion sqrt

int main()
{ //zona de declaracion de variables 
  int edad=20;
  float dinero= 200.50;
  
    printf("hola yo tengo %d años y en mi cuenta de banco he ahorrado %f",edad, dinero);
    
    printf("¿ que hace este \n\n");
    printf("\t alguien ya sabe ");
    return 0;
}
