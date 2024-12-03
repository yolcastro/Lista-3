#include <stdio.h>
#include <stdlib.h>
#include <time.h>

#define TAM 15
#define INI 0.0f
#define MX 100.0f

int main() {
    float vetor[TAM];

    srand(time(NULL));

    for (int k = 0; k < TAM; k++) {
        vetor[k] = INI + ((float)rand() / RAND_MAX) * MX;
        printf("%.2f\n", vetor[k]);
    }

    float menor = vetor[0];
    for (int k = 1; k < TAM; k++) {
        menor = (menor > vetor[k]) ? vetor[k] : menor;
    }

    float maior = vetor[0];
    for (int k = 1; k < TAM; k++) {
        maior = (maior < vetor[k]) ? vetor[k] : maior;
    }

    printf("Menor valor: %.2f\n", menor);
    printf("Maior valor: %.2f\n", maior);

    return 0;
}
