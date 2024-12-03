#include <stdio.h>
#include <stdlib.h>
#include <time.h>
#include <math.h>

#define TAM 3
#define INI 0
#define MX 19

int main() {
    int vetor[TAM];
    double soma = 0.0, produto = 1.0;
    double aritmetica, geometrica;

    srand(time(NULL));

    for (int k = 0; k < TAM; k++) {
    vetor[k] = INI + rand() % MX;

    soma += vetor[k];
    produto *= vetor[k];

    printf("%d\n", vetor[k]);
    }
    
    aritmetica = soma / TAM;
    geometrica = pow(produto, 1.0 / TAM);

    printf("Média aritmética: %.2f\n", aritmetica);
    printf("Média geométrica: %.2f\n", geometrica);

    return 0;
}
