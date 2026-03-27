//exercicio 1
#include <stdio.h>

int main(){
    int numero;
    float valor;
    char letra;
    
    numero = 10;
    valor = 4.9;
    letra = 'D';
    
    printf ("Numero:%d \n ",numero) ;
    printf ("Valor: %.2f \n ",valor) ;
    printf ("Letra:%c \n",letra) ;

    return 0;
}

//exercicio 2

#include <stdio.h>

int main(){
   
    int idade;
    float altura;
    //char nome[50];
    
    printf ("digite sua idade: ");
    scanf ("%d", &idade);
    
    printf ("digite sua altura: ");
    scanf ("%f", &altura);
    
    //printf ("qual seu nome: ");
    //scanf ("%c", &nome);
    
   // printf ("nome %c \n", nome);
    printf ("idade %d \n", idade);
    printf ("altura %.2f \n", altura);
    
    
    return 0;
}


exercicio 2 
#include <stdio.h>

int main()
{
      float r, area;
      float pi =  3.14159;
    printf ("digite o raio:");
    scanf ("%f", &r);
    
    if(r < 0) {
       printf ("Erro: O raio não pode ser negativo.\n");
       } else{
           area = pi * r * r;
           printf ("a area do circulo é: %.2f\n", area);
           
           
       }

    return 0;
}
    
