#include <stdio.h>
#include <stdlib.h>
#include "pila.h"

//PROTOTIPADO

int sumarConRetornoConParametros(int A,int B);
void sumarSinRetornoConParametros(int A,int B);
int sumarConRetornosinParametros();
void sumarSinRetornosinParametros();
Pila cargarPilaPorTeclado(Pila A);

int main()
{

    //int resultado = sumarConRetornoConParametros(2,3);
    //printf("El resultado es %i",resultado);
    /*int A=3;
    int resultado2 = sumarConRetornosinParametros();
    printf("El resultado es %i",resultado2);
    **/
    /*  sumarSinRetornoConParametros(2,5);*/

    sumarSinRetornosinParametros();
    Pila A;
    inicpila(&A);
    cargarPilaPorTeclado(A);
    printf("Pila dentro de la funcion\n");
    mostrar(&A);


    return 0;

}

//FUNCIONESSS /////////////////

int sumarConRetornoConParametros(int A,int B)
{
    int resultado;
    resultado = A+B;
    return resultado;

}

void sumarSinRetornoConParametros(int A,int B)
{
    int resultado = A+B;
    printf("El resultado es :%i\n",resultado);

}


int sumarConRetornosinParametros()
{
    int A;
    printf("Ingrese un numero\n");
    scanf("%i",&A);
    int B;
    printf("Ingrese un numero\n");
    scanf("%i",&B);
    int resultado= A+B;
    return resultado;

}

void sumarSinRetornosinParametros()
{
    int A;
    printf("Ingrese un numero\n");
    scanf("%i",&A);
    int B;
    printf("Ingrese un numero\n");
    scanf("%i",&B);
    int resultado;
    resultado = A+B;
    printf("El resultado es %i", resultado);

}


Pila cargarPilaPorTeclado(Pila A)
{
    char control = 's';
    while(control == 's')
    {
        leer(&A);
        printf("Quiere seguir cargando? Presione s o n\n");
        fflush(stdin);
        scanf("%c",&control);
    }
}
