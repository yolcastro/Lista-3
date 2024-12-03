#include <stdio.h>
#include <stdlib.h>
#include <time.h>

#define LINHAS 3
#define COLUNAS 3
#define INI 0
#define MX 100

int main() {
    int matriz[LINHAS][COLUNAS];
    int x, contador = 0;

    srand(time(NULL));

    puts("Matriz gerada pseudoaleatoriamente:");
    
    int i, j;

    for (i = 0; i < LINHAS; i++) {
        for (j = 0; j < COLUNAS; j++) {
        matriz[i][j] = INI + rand() % MX;
        printf("%d ", matriz[i][j]);
        }
        printf("\n");
    }
    
    printf("\n");
    printf("Digite um valor numérico inteiro:\n");
    scanf("%d", &x);

    for (i = 0; i < LINHAS; i++) {
        for (j = 0; j < COLUNAS; j++) {
            if (matriz[i][j] == x) {
            contador++;
            }
        }
    }
    
    printf("\n");
    if (contador > 0) {
        printf("O valor aparece %d vez(es) na matriz.", contador);
    }
    else {
        printf("O valor não aparece na matriz.");
    }

    return 0;
}
