#include <stdio.h>

int main() {

    float dolar, real, cotacao;

    printf("Digite o valor em reais: ");
    scanf("%f", &real);

    printf("Digite a cotacao do dolar: ");
    scanf("%f", &cotacao);

    dolar = real / cotacao;

    printf("Valor em dolares: US$ %.2f\n", dolar);

    return 0;
}
