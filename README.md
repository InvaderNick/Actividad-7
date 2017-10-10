//# Actividad-7
//Herra#include <stdio.h>
/*
int main()
{
    int a[]={1,2,3,4,5,6,7,8,9,10};
    int t=sizeof(a)/sizeof(int);
    printf("%d\n",t);
    func1(a, t);
    return 0;
}

void func1(int p[],int t){
    int i;
    for (i=0;i<t;++i){
        printf("%d",p[i]);
        printf("\n");
    }

}
*/

#include <stdlib.h>
#include <time.h>
#define S 15
/*
int func_1 (){

  printf("%30s %s %s","ALMACEN ", noma, "\n");
    printf("%30s %s %s","SURCUSAL ", noms, "\n");
    printf("%45s","REPORTE SEMANAL DE VENTAS \n\n");
    for(x=0;x<=3;x++){
    printf("%20i. Sucursal %s\n",x+1,s[x]);
    }
    printf("                   5. Totales finales\n");
    printf("                   6. Finalizar\n");

}
*/
int main()
{
    char noma[15], noms[15],s[4][15]={"Centro","Bugaba","Terronal","Mall Chiriqui"};
    int departamento,dia,monto,total,d,c,x,n;
    srand(time(NULL));
    d=rand()%9999;
    c=rand()%99;
    scanf("%s",&noma);
    printf("%30s %s %s","ALMACEN ", noma, "\n");
    printf("%45s","REPORTE SEMANAL DE VENTAS \n\n");
    for(x=0;x<=3;x++){
    printf("%20i. Sucursal %s\n",x+1,s[x]);
    }
    printf("                   5. Totales finales\n");
    printf("                   6. Finalizar\n");
    scanf("%i",&n);
switch(n){
case 1:
    {
    char noms[S]={"Centro"};
    printf("%30s %s %s","ALMACEN ", noma);
    printf("\t SURCUSAL %s \n", noms);
    printf("\t REPORTE SEMANAL DE VENTAS \n");
    printf("\t DIA DE MAYOR VENTA\n");
    printf("\t DEPARTAMENTO DE MAYOR VENTA\n");
    }
     break;
case 2:{
    char noms[S]={"Bugaba"};
}
break;
case 3:{
    char noms[S]={"Terronal"};
}
case 4:{
    char noms[S]={"Mall Chiriqui"};
}
case 5:

case 6:

default:
    printf("No niggie no");
    }
}

    
 
