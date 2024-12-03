#include <stdio.h>
#include <string.h>

#define TAM 100

int main() {
    char str[TAM];
    char caractere;
    int encontrado = 0;

    printf("Digite algo:");
    fgets(str, TAM, stdin);

    str[strcspn(str, "\n")] = '\0';

    printf("Digite um caractere específico:");
    scanf("%c", &caractere);

    for (int i = 0; i < strlen(str); i++) {
        if (str[i] == caractere) {
            puts("Caractere encontrado.");
            encontrado = 1;
            break;
        }
    }

    if (!encontrado) {
        puts("Caractere não encontrado.");
    }

    return 0;
}
