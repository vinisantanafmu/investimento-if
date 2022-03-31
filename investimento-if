#include <stdio.h>

int tipo;
float investimento, renda;

int main() {
    
    printf("\n\nBem vindo à calculadora de investimento da Rich!\n\n");
    printf("CLIQUE AQUI FIQUE RICO GANHANDO APENAS R$1000,00 POR MÊS!!!\n");
    printf("Saia da pupança!! invista AQUI e ganhe 0,1 porcento a mais por mês!!!\n\n");
    
    printf("Primeiro digite seu tipo de investimento:\n\n");
    
    printf("    [1] Poupança\n");
    printf("    [2] Fundo de Renda Fixa\n\n");
    
    scanf("%i", &tipo);
    
    printf("\n\nOk! Agora digite o valor do seu investimento:\n");
    scanf("%f", &investimento);
    
    if (tipo > 0 && tipo < 3) {

        if (tipo == 1) {
            renda = investimento * 1.03;
        }
        
        else {
            renda = investimento * 1.04;
        }
    }
    else {
        printf("\n\nValor invalido, é burro e ta investindo?");
    }
    
    printf("\n\nVocê reberá o valor de R$%.2f!", renda);
    
    
}
