#include <stdio.h> // Biblioteca para entrada e saída de dados

int main() { // Função principal onde o prpgrama começa a ser executado

    
    int idade;// Declaração da variável inteira para armazenar a idade

    float altura;// Declaração da variável float para armazenar a altura
  
    char inicial;// Declaração da variável char para armazenar a inicial do nome

    idade = 17; // Atribuindo valores às variáveis
    altura = 1.75; // Atribuindo valores às variáveis
    inicial = 'G'; // Atribuindo valores às variáveis

    printf("Idade: %d anos\n", idade);// Exibindo os valores armazenados na tela
    
    printf("Altura: %.2f metros\n", altura);// %.2f exibe o número float com 2 casas decimais

    printf("Inicial do nome: %c\n", inicial);// %c é utilizado para exibir um caractere

    
    return 0;// Retorna 0 indicando que o programa terminou corretamente
}
