#include <stdio.h>
#include <string.h>

#define TAM 100

int caracteres(char *str) {
    int qtd = 0;

    while (*str != '\0') {
        if (*str != ' ') {
            qtd++;
        }
        str++;
    }

    return qtd;
}

int main() {
    char str[TAM];

    printf("Digite algo:\n");
    fgets(str, TAM, stdin);

    str[strcspn(str, "\n")] = '\0';

    int qtd = caracteres(str);

    printf("Quantidade de caracteres: %d\n", qtd);

    return 0;
}
