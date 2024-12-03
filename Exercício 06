#include <stdio.h>
#include <string.h>

#define TAM 100

void inverter(char* str) {
    int comeco = 0;
    int fim = strlen(str) - 1;
    char aux;

    while (comeco < fim) {
        aux = str[comeco];
        str[comeco] = str[fim];
        str[fim] = aux;

        comeco++;
        fim--;
    }
}

int main() {
    char str[TAM];

    puts("Digite algo:");
    fgets(str, TAM, stdin);
    
    inverter(str);

    printf("Resultado: %s\n", str);

    return 0;
}
