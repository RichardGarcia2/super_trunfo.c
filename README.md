# super_trunfo.c
aula1
#include <stdio.h>

int main ()
{

//usar %s, para caracteres, palavras e letras.
char UF[2];
char NF[4];

// usa "fgets" para ler os espaços entre o nome das cidades, quando for usar a variavel.//
char DF[20]; 

float hb; //habitantes.

float km; //A área da cidade em quilômetros quadrados.
float PIB;

int PT;

printf ("Diga a UF do estado:");
scanf ("%s", UF);

printf ("Diga a NF (K01 ou K02):");
scanf ("%s", NF);

printf ("Diga o nome da cidade:");
scanf ("%s",DF);
fgets (DF, sizeof(DF), stdin); 
//fgets suporta mais palavras e espaços.

printf ("Qual o numero de habitantes da cidade?:");
scanf ("%f\n", &hb);
//tentar com %e, Imprime um número de ponto flutuante na notação científica, se não der certo mudar para %f ponto flutuante padrão ou vice versa

printf ("Qual a kilometragem da cidade?:");
scanf ("%f\n", &km);

printf ("Qual o PIB da cidade?:");
scanf ("%f\n", &PIB);

printf ("Quantos pontos turisticos há na cidade?:");
scanf ("%f\n", &PT);


}
