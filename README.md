# atividade-10
João Guilherme Gomes Sanna 


QUSTAO 01:

 #include <stdio.h>
#include <stdlib.h>

 int main() {

float nota1; float nota2;
 float nota3;
 float nota4;

 printf("digite a primeira nota: ");
 scanf("%f", &nota1);
 printf("digite a primeira nota: ");
 scanf("%f", &nota2);
 printf("digite a primeira nota: ");
 scanf("%f", &nota3);
 printf("digite a primeira nota:");
scanf("%f", &nota4);

float total = nota1+nota2+nota3+nota4;

printf("nota total: %f", total);
 return 0;
 }



QUESTAO O2:

 #include <stdio.h>
 #include <stdlib.h>
 
 int main() {
 float nota1;
 float nota2;
 float nota3;
 float nota4;
 
 printf("digite a primeira nota: ");
 scanf("%f", &nota1);
 printf("digite a primeira nota: ");
 scanf("%f", &nota2);
 printf("digite a primeira nota: ");
 scanf("%f", &nota3);
 printf("digite a primeira nota:");
 scanf("%f", &nota4);
 
 float total = nota1+nota2+nota3+nota4;
 float media = total / 4;
 printf("nota total: %f", total);
 printf("A media das notas e :,%f",media);
 return 0;
 }



 QUESTAO 03:

 #include <stdio.h>
 
int main() {
//declaração variaveis
 float altura;
 float base;
 printf("escreva o valor da altura:");
 scanf("%f", &altura);
 printf("escreva o valor da base:");
 scanf("%f", &base);
 float total = altura * base;
 printf("o calculo da area e: %.2f/m", total);
 return 0;
 
 }
 



 QUESTAO 04:

  #include <stdio.h>
 #include <stdlib.h>
 
 int main() {
 	
 float valor1;
 float valor2;

 printf("digite o primeiro valor: ");
 scanf("%f", &valor1);
 printf("digite o segundo valor: ");
 scanf("%f", &valor2);
 
 float total = valor1 / valor2;

 printf("A diferenca entre os dois numeros e: %f", total);
 return 0;
 }



 QUESTAO 05:

  #include <stdio.h>
 
 
 int main() {
 	
 float peso;
 float gramas;

 printf("digite valor1 ");
 scanf("%f", &peso);

gramas = peso*1000;

printf("o peso em gramas sera : %f", gramas);
 
 return 0;
 }


 QUESTAO 06:

 #include <stdio.h>
 
 
 int main() {
 	float peso;
 	lfoat gramas;
 	
 	printf("digite o seu peso:");
 	scanf("%f, &peso");
 	
 	
 	float total = peso * 1000;
 	
 	printf("o valor do seu peso em gramas e de: %f", total);
 	
 	return 0;
 	
 }	


 QUESTÃO 07:

  #include <stdio.h>
 
 
 int main() {

float quilogramas;
float valor = 445.00;


printf("peso do prato:");
scanf("%f", &quilogramas);


float total = quilogramas * valor;
printf("o valor do seu praato e de: %f", total);
return 0;
}


QUESTAO 08:

#include <stdio.h>

float fahrenheit_para_celsius(float fahrenheit) {
    float celsius = (fahrenheit - 32) / 1.8;
    return celsius;
}

int main() {
    float fahrenheit, celsius;
    
    printf("Digite a temperatura em Fahrenheit: ");
    scanf("%f", &fahrenheit);
    
    celsius = fahrenheit_para_celsius(fahrenheit);
    
    printf("Temperatura em Celsius: %.2f\n", celsius);
    printf("Temperatura em Fahrenheit: %.2f\n", fahrenheit);
    
    return 0;
}


QUESTAO 09:

#include <stdio.h>
#include <math.h>

#define PI 3.14159

float calcular_diametro(float raio) {
    return 2 * raio;
}

float calcular_comprimento(float raio) {
    return 2 * PI * raio;
}

float calcular_area(float raio) {
    return PI * pow(raio, 2);
}

int main() {
    float raio, diametro, comprimento, area;
    
    printf("Digite o valor do raio da circunferencia: ");
    scanf("%f", &raio);
    
    diametro = calcular_diametro(raio);
    comprimento = calcular_comprimento(raio);
    area = calcular_area(raio);
    
    printf("Diametro da circunferencia: %.2f\n", diametro);
    printf("Comprimento da circunferencia: %.2f\n", comprimento);
    printf("Area da circunferencia: %.2f\n", area);
    
    return 0;
}


QUESTAO 10:

#include <stdio.h>

void trocar_valores(int *x, int *y) {
    int temp = *x;
    *x = *y;
    *y = temp;
}

int main() {
    int a, b;
    
    printf("Digite o valor de a: ");
    scanf("%d", &a);
    printf("Digite o valor de b: ");
    scanf("%d", &b);
    
    printf("Valores originais:\n");
    printf("a = %d\n", a);
    printf("b = %d\n", b);
    
    trocar_valores(&a, &b);
    
    printf("Valores trocados:\n");
    printf("a = %d\n", a);
    printf("b = %d\n", b);
    
    return 0;
}

 
