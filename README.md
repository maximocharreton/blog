en este blog compartire algunos de los trabajos realzados en clase, este ejercicio noes ayuda a saber el ph del suelo 
include <stdio.h>

int main()
{
    //zona de declaracion de variables 
    float ph; 
    int ph_aprox;
    
    printf("ingrese el valor de ph del suelo: ");
    scanf("%f", &ph);
    
    // casteo o conversion 
    ph_aprox=(int)ph;
    
    switch(ph_aprox)
    {
        case 0: case 1: case 2: case 3: case 4: 
        printf("el numero es extremadamente acido, \n");
        break;
        case 5: 
        printf("el suelo es fuertemenrte acido, \n");
        break;
         case 6: 
        printf("el suelo es moderadamente acido, \n");
        break;
         case 7: 
        printf("el suelo es neutro, \n");
        break;
         case 8: 
        printf("el suelo es alcalino, \n");
        break;
        
        
    }
        

        
        
    
    

    return 0;
}
