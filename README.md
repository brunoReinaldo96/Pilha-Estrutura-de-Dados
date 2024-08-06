# Pilha em Java

Este projeto implementa uma estrutura de dados pilha em Java. A classe `Pilha` fornece métodos para empilhar, desempilhar, e visualizar elementos, além de verificar se a pilha está cheia ou vazia. A classe `Exemplo1` demonstra o uso da pilha, solicitando cinco valores inteiros ao usuário e exibindo o conteúdo da pilha.

## Estrutura do Projeto

- **Pilha.java**: Implementa a estrutura de dados pilha.
- **Exemplo1.java**: Demonstra o uso da classe `Pilha`.

## Compilação e Execução

1. **Compile os arquivos Java**:
   ```sh
   javac Pilha.java Exemplo1.java
Execute o programa:

java Exemplo1

O programa solicitará cinco valores inteiros, empilhará esses valores e exibirá o conteúdo da pilha.

# Métodos Principais

## Classe Pilha

### Construtor:

**Pilha(int tam)**: Inicializa a pilha com o tamanho especificado.

### Métodos:

**boolean PilhaVazia()**: Verifica se a pilha está vazia.

**boolean PilhaCheia()**: Verifica se a pilha está cheia.

**void Empilhar(int elemento)**: Adiciona um elemento ao topo da pilha.

**int Desempilhar()**: Remove e retorna o elemento do topo da pilha.

**void ElementoTopo()**: Exibe o elemento no topo da pilha.

**void MostrarPilha()**: Exibe todos os elementos da pilha, do topo para a base.




