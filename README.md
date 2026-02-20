# super_trunfo.c
aula1


#include <stdio.h>

int main ()
{
    // Declaração das variáveis da Carta 1
    char UF1 [3];
    char NF1[10];
    char DF1[100];
    int hb1;
    float km1;
    float pib1;
    int pt1;

    // Declaração das variáveis da Carta 2
    char UF2 [3];
    char NF2[10];
    char DF2[100];
    int hb2;
    float km2;
    float pib2;
    int pt2;

    // ===================== CARTA 1 =====================
    printf("=== Cadastro da Carta 1 ===\n");

    printf("Estado (UF): ");
    scanf(" %2s", UF1);

    // N°S, está impondo limite de numeros digitados, impedindo memoria cheia

    printf("NF da Carta (ex: A01): ");
    scanf(" %9s", NF1);

    printf("Cidade: ");
    scanf(" %99[^\n]", DF1);

    //me permite impor um limite, e ler espaços

    printf("Populacao: ");
    scanf("%d", &hb1);

    printf("Area (km²): ");
    scanf("%f", &km1);

    printf("PIB (em bilhoes de reais): ");
    scanf("%f", &pib1);

    printf("Quant. Pontos Turisticos:");
    scanf("%d", &pt1);

    // ===================== CARTA 2 =====================
    printf("\n=== Cadastro da Carta 2 ===\n");

    printf("Estado (UF): ");
    scanf(" %2s", UF2);

    // N°S, está impondo limite de numeros digitados, impedindo memoria cheia

    printf("NF da Carta (ex: B02): ");
    scanf("%9s", NF2);

    printf("Cidade: ");
    scanf(" %99[^\n]", DF2);
    
    //me permite impor um limite, e ler espaços

    printf("Populacao: ");
    scanf("%d", &hb2);

    printf("Area (km²): ");
    scanf("%f", &km2);

    printf("PIB (em bilhoes de reais): ");
    scanf("%f", &pib2);

    printf("Quant. Pontos Turisticos:");
    scanf("%d", &pt2);

    // ===================== EXIBIÇÃO DOS DADOS =====================
    printf("\n\n===== CARTAS CADASTRADAS =====\n");

    printf("\nCarta 1\n");

    printf("Estado: %s\n", UF1);

    printf("Codigo: %s\n", NF1);
    
    printf("Nome da Cidade: %s\n", DF1);
    
    printf("Populacao: %d\n", hb1);
    
    printf("Area: %.2f km²\n", km1);
    
    printf("PIB: %.2f bilhoes de reais\n", pib1);
    
    printf("Quant. Pontos Turisticos: %d\n", pt1);

    
    printf("\nCarta 2\n");
    
    printf("Estado: %s\n", UF2);
    
    printf("Codigo: %s\n", NF2);
    
    printf("Cidade: %s\n", DF2);
    
    printf("Populacao: %d\n", hb2);
    
    printf("Area: %.2f km²\n", km2);
    
    printf("PIB: %.2f bilhoes de reais\n", pib2);
    
    printf("Quant. Pontos Turisticos:%d\n", pt2);

    return 0;
}
