Pilha em Java
Este projeto implementa uma estrutura de dados pilha (stack) em Java, utilizando um array para armazenar os elementos. A pilha permite empilhar e desempilhar elementos, bem como verificar se está vazia ou cheia.

Descrição do Código
O código é composto por duas classes principais:

Pilha: Representa a estrutura de dados pilha. Inclui métodos para empilhar (adicionar) e desempilhar (remover) elementos, além de verificar se a pilha está vazia ou cheia e exibir o elemento no topo.

Exemplo1: Contém o método main, que serve como um exemplo de uso da classe Pilha. O programa solicita ao usuário que insira cinco valores inteiros, empilha esses valores e, em seguida, exibe o conteúdo da pilha.

Classes e Métodos
Classe Pilha
Atributos:

int tamanho: Define o tamanho máximo da pilha.
int topo: Indica o índice do topo da pilha. Inicialmente, é -1, indicando que a pilha está vazia.
int vetor[]: Array que armazena os elementos da pilha.
Construtor:

Pilha(int tam): Inicializa a pilha com um tamanho especificado.
Métodos:

boolean PilhaVazia(): Verifica se a pilha está vazia.
boolean PilhaCheia(): Verifica se a pilha está cheia.
void Empilhar(int elemento): Adiciona um elemento ao topo da pilha.
int Desempilhar(): Remove e retorna o elemento do topo da pilha. Retorna -1 se a pilha estiver vazia.
void ElementoTopo(): Exibe o elemento no topo da pilha.
void MostrarPilha(): Exibe todos os elementos da pilha, do topo para a base.
Classe Exemplo1
Método:
public static void main(String[] args): Ponto de entrada do programa. Solicita ao usuário cinco valores inteiros, empilha-os e exibe o conteúdo da pilha.
Instruções para Execução
Compile o código:

sh
Copiar código
javac Pilha.java Exemplo1.java
Execute o programa:

sh
Copiar código
java Exemplo1
Interaja com o programa:

Insira cinco valores inteiros quando solicitado. Os valores serão empilhados e, em seguida, a pilha será exibida na tela.
Exemplo de Saída
Após inserir cinco valores, o programa exibirá algo semelhante a:

Copiar código
Elemento 5 posição 4 da Pilha
Elemento 4 posição 3 da Pilha
Elemento 3 posição 2 da Pilha
Elemento 2 posição 1 da Pilha
Elemento 1 posição 0 da Pilha
Observações
Certifique-se de que o Java está instalado e configurado corretamente em seu ambiente de desenvolvimento.
O programa termina automaticamente após exibir o conteúdo da pilha devido ao System.exit(0).
