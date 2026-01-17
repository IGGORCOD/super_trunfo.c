//# super_trunfo.c
#include <stdio.h>


int main(){
    //Inicializei todas as variaveis das 2 cartas.
    char estado1, estado2;
    char codCarta1[20],codCarta2[20];
    char nomeCidade1[20], nomeCidade2[20];
    int pontoTuristi1, pontoTuristi2;
    int pop1, pop2;
    float area1, area2;
    float pib1, pib2;
      
    //aqui foi pedido todos os dados da primeira Carta
    //acredito que da pra passar a função scanf dentro do printf para otimizar o código e já preencher as variáveis.
    printf("Digite a letra do primeiro Estado: ");
    scanf(" %c", &estado1);
    printf("Digite o código do primeiro Estado: ");
    scanf(" %s", &codCarta1);
    printf("Digite o nome da cidade: ");
    scanf(" %s", &nomeCidade1);
    printf("Digite a população de sua cidade: ");
    scanf(" %d", &pop1);
    printf("Digite a área da cidade: ");
    scanf(" %f", &area1);
    printf("Digite o pib da sua cidade: ");
    scanf(" %f", &pib1);
    printf("Digite o número de pontos turísticos da sua cidade: ");
    scanf(" %d", &pontoTuristi1);
    printf("\n");

    //pedido as entradas da segunda carta ao usuário     
    printf("Digite a letra do segundo Estado: ");
    scanf(" %c",&estado2);
    printf("Digite o código do primeiro Estado: ");
    scanf(" %s",&codCarta2);
    printf("Digite o nome da cidade: ");
    scanf(" %s",&nomeCidade2);
    printf("Digite a população de sua cidade: ");
    scanf(" %d",&pop2);
    printf("Digite a área da cidade: ");
    scanf(" %f",&area2);
    printf("Digite o pib da sua cidade: ");
    scanf(" %f",&pib2);
    printf("Digite o número de pontos turísticos da sua cidade: ");
    scanf(" %d",&pontoTuristi2);

    //Aqui estou imprimindo na tela do usuário todos os dados fornecidos.
    //Vale lembrar que na entrada da variavel população se o cliente digitar com . da erro.
    printf("Carta 1\n");
    printf("Letra do Estado: %c\n", estado1);
    printf("Código do Estado: %s\n", codCarta1);
    printf("Nome cidade: %s\n", nomeCidade1);
    printf("População: %d habitantes\n", pop1);
    printf("Área: %.2f km²\n", area1);
    printf("PIB: %.2f bilhões de reais\n", pib1);
    printf("Números de Pontos Turísticos: %d\n", pontoTuristi1);
    printf("\n");

    printf("Carta 2\n");
    printf("Letra do Estado: %c\n", estado2);
    printf("Código do Estado: %s\n", codCarta2);
    printf("Nome cidade: %s\n", nomeCidade2);
    printf("População: %d habitantes\n", pop2);
    printf("Área: %.2f km²\n", area2);
    printf("PIB: %.2f bilhões de reais\n", pib2);
    printf("Números de Pontos Turísticos: %d\n", pontoTuristi2);

    //agora é só repetir dando a mesma coisa da entrada das variaveis da segunda carta e imprimir tudo de uma vez.

    return 0;

}


