#include <stdio.h>

#define LINHAS 3
#define COLUNAS 3

int main() {
    int matriz[LINHAS][COLUNAS];

    puts("A matriz possui três linhas e três colunas.\n");
    
    for (int i = 0; i < 3; i++) {
        printf("Digite os elementos da linha %d:\n", i + 1);
        for (int j = 0; j < 3; j++) {
            scanf("%d", &matriz[i][j]);
        }
    }

    puts("Elementos da diagonal principal:\n");
    printf("%d %d %d", matriz[0][0], matriz[1][1], matriz[2][2]);

    return 0;
}
