#include <stdio.h>
#include <stdlib.h>
#include <math.h>


/** 1   PROABLEMAS SECUENCIALES)

int main()
{
    int capital;
    int MesPorcentaje;
    float interes= 0.02;
    printf("Ingrese monto a invertir\n");
    scanf("%i", &capital);
    printf("Monto a invertir es de: %i\n", capital);
    int resultado;
    MesPorcentaje =(capital*interes);
    resultado= (MesPorcentaje+capital);
    printf("Dinero ganado en un mes: %i",resultado);

    return 0;
}

**/
/** 2)
int main()
{

    float compra;
    float descuento;
    float total_a_pagar;
    float porcentaje = 0.15;

    printf("Ingrese el monton de tu compra\n");
    scanf("%f",&compra);
    descuento =(compra*porcentaje);
    printf("DESCUENTO DEL 15%%: %f\n",descuento);
    total_a_pagar = compra-descuento;
    printf("TOTAL A PAGAR: %f", total_a_pagar);

    return 0;
}

**/

/** 3)

int main()
{
    int hombres;
    int mujeres;
    float porcentajeH;
    float porcentajeM;
    float TotalA;

    printf("Ingrese cantidad de hombres\n");
    scanf("%i",&hombres);
    printf("Ingrese cantidad de Mujeres\n");
    scanf("%i",&mujeres);
    TotalA = hombres+mujeres;
    printf("Cantidad total de Alumnos %f\n",TotalA);
    porcentajeH= (hombres*100/TotalA);
    porcentajeM= (mujeres*100/TotalA);
    printf("Porcentaje de estudiantes hombre: %f%%\n",porcentajeH);
    printf("Porcentaje de estudiantes mujeres: %f%%\n",porcentajeM);


    return 0;
}

**/
/** 1) PROBLEMAS CONDICIONALES SELECTIVOS SIMPLES

int main()
{
    float nota1,nota2,nota3;
    float Sumatoria;
    float NotaFinal;
    printf("Ingrese su primera nota\n");
    scanf("%f",&nota1);
    printf("Ingrese su segunda nota\n");
    scanf("%f",&nota2);
    printf("Ingrese su tercera nota\n");
    scanf("%f",&nota3);
    Sumatoria= nota1+nota2+nota3;
    NotaFinal=Sumatoria/3;
    printf("Promedio de sus 3 notas es: %f\n",NotaFinal);
    if(NotaFinal>=7){
            printf("APROBADO");
            }
    else printf("DESAPROBADO");

    return 0;
}

**/

/** 2)
int main()
{
    float TotalDeCompra;
    float porcentaje=0.20;
    float MontoSuperado=5000;
    float MontoFinal;
    float MontoDescuento;
    printf("Ingrese el valor de su compra\n");
    scanf("%f",&TotalDeCompra);
    if(TotalDeCompra>MontoSuperado){
        MontoDescuento=TotalDeCompra*porcentaje;
        MontoFinal=TotalDeCompra-MontoDescuento;
        printf("20%% POR MONTO SUPERADO A $5000: $%f\n",MontoDescuento);
        printf("VALOR A PAGAR: $%f\n",MontoFinal);
    }
    else{
        printf("NO APLICA DESCUENTO POR MONTO NO SUPERADO");
    }

    return 0;
}

**/
/** 3)
int main()
{
    int horas;
    int valormenor=40;
    int salariofinal;
    int salariobasico=300;
    int salariomayor=400;
    int horasextras;
    printf("Ingrese sus horas trabajadas:\n");
    scanf("%i",&horas);
    if(horas>valormenor){
        horasextras= horas - valormenor;
        salariofinal=(valormenor*salariobasico)+(horasextras*salariomayor);
        printf("Su salario es de $%i",salariofinal);
    }
    else{
        salariofinal=horas*salariobasico;
        printf("Su salario es de $ %i",salariofinal);
    }

    return 0;
}

 **/

 /** 4)

int main()
{
    float numero1;
    float numero2;
    printf("Ingrese un numero\n");
    scanf("%f",&numero1);
    printf("Ingrese un numero\n");
    scanf("%f",&numero2);
    if(numero1<numero2){
        printf("Ordenado de forma ascendente\n");
        printf("%f\n",numero1);
        printf("%f\n",numero2);
    }
    else{
        printf("%f\n",numero2);
        printf("%f\n",numero1);
    }


    return 0;
}

 **/

 /** 5)

int main()
{
    float precio;
    int camisas;
    float total;
    float descuentoBasico = 0.10;
    float descuentoMaximo = 0.20;
    float descuento=0;
    printf("Ingrese el precio de la camisa\n");
    scanf("%f",&precio);
    priLES SELntf("Ingrese el total de camisas compradas\n");
    scanf("%i",&camisas);
    total= precio*camisas;
    if (camisas>=3){
        descuento= total*descuentoMaximo;

        printf("DESCUENTO APLICADO %%20: $%f\n",descuento);
        printf("TOTAL A PAGAR: $%f\n",total - descuento);

    }
    else {
        descuento=total*descuentoBasico;
        printf("DESCUENTO APLICADO %%10: $%f\n",descuento);
        printf("TOTAL A PAGAR: $%f\n",total - descuento);

    }


    return 0;
}

 **/

/** PROBLEMAS CONDICIONALES SELECTIVOS COMPUESTOS(SI ANIDADOS O EN CASCADA)
1)
int main(){


    float numero1;
    float numero2;
    float resta;
    float multiplicacion;
    float suma;
    printf("Ingrese un numero\n");
    scanf("%f",&numero1);
    printf("Ingrese un numero\n");
    scanf("%f",&numero2);
    if(numero1==numero2){
        multiplicacion=numero1*numero2;
        printf("%f",multiplicacion);
    }
    else{
        if(numero1>numero2){
            resta=numero1-numero2;
            printf("%f",resta);
        }
        else{
            suma=numero1+numero2;
            printf("%f",suma);
        }
    }
    return 0;
}

**/

/** 2

int main(){
    float numero1;
    float numero2;
    float numero3;

    printf("Ingrese un numero\n");
    scanf("%f",&numero1);
    printf("Ingrese un numero\n");
    scanf("%f",&numero2);
    printf("Ingrese un numero\n");
    scanf("%f",&numero3);
    if(numero1>numero2){
        if(numero1>numero3){
            printf("El mayor de los 3 numeros es: %f",numero1);
        }
        else{
            printf("El mayor de los 3 numeros es: %f",numero3);
        }
    }
    else{
        if(numero2>numero3){
            printf("El mayor de los 3 numeros es: %f",numero2);
        }
        else{
            printf("El mayor de los 3 numeros es: %f",numero3);
        }
    }
    return 0;

}

**/

/** PROBLEMAS CON REPETICIONES

1)

int main(){

    float i;
    float nota1, acumNotas=0;
    float promedio;

    for(i=0;i<7;i++){
        printf("Ingrese su nota\n");
        scanf("%f",&nota1);
     ///   acumNotas += nota1;
     acumNotas = nota1 + acumNotas;
    }
    promedio = acumNotas/7;
    printf("TU PROMEDIO DE NOTA ES: %f",promedio);

    return 0;
}

**/

/** 2)

int main(){

    float numero;
    float i =0;
    float acum =0;
    float cuarta;
    float cubo;

    for(i=0;i<10;i++){
        printf("Ingrese un numero\n");
        scanf("%f",&numero);
        acum += numero;
    }
    cuarta= pow(numero, 4);
    cubo=pow(numero,3);
    printf("El cubo es:%f\n,",cubo);
    printf(" la cuarta es:%f\n",cuarta);



    return 0;
}

**/

/** 3)

int main(){

    int i;
    float numero;
    int acum=0;


    for(i=0;i<10;i++){
        printf("Ingrese un numero\n");
        scanf("%f",&numero);
        if(numero>0){
            printf("Es un numero positivo\n");
        }
        else{
            printf("Es un numero negativo\n");
        }
    }

    return 0;
}

 **/

 /**4)
 int main(){
    int i = 1;
    float numero;

     while(i<=15)
    {
        printf("Ingrese un numero\n");
        scanf("%f",&numero);
        if(numero <0){
            printf("%f\n",numero*(-1));
        }
        else{
            printf("El numero es positivo\n");
        }
        i++;

    }


     return 0;
 }

 **/

 /** 5)**/

 int main(){

     float numero;
     int i;
     int acum = 0 ;
     float promedio;
     int baja = 10;



     for(i=0;i<4;i++){
        printf("Ingrese una calificacion\n");
        scanf("%f",&numero);
        acum += numero;
        if (numero < baja){
        baja = numero;
     }
     }
     promedio = acum/4;
     printf("El promedio de las califaciones es: %f\n",promedio);
     printf("La calificacion mas baja es: %i",baja);

     return 0;
 }
