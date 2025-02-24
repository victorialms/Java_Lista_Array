# Implementação de Lista com Array - Estrutura de Dados

Este repositório contém a implementação de uma lista baseada em array, utilizando a linguagem Java, como parte de uma disciplina de Estruturas de Dados na faculdade. A lista permite realizar operações de adição, remoção e busca de elementos, além de realizar o redimensionamento automático do array conforme necessário.

## Estrutura do Repositório

O repositório contém os seguintes arquivos:

- **ListaArray.java**: Implementação da classe `ListaArray` que contém a lógica da lista.
- **Main.java**: Programa de exemplo que demonstra como utilizar a classe `ListaArray`.

## Descrição dos Arquivos

### `ListaArray.java`

A classe `ListaArray` possui os seguintes métodos principais:

- **adicionar(Object elemento)**: Adiciona um elemento ao final da lista. O array é redimensionado automaticamente caso não haja espaço suficiente.
- **adicionar(Object elemento, int posicao)**: Adiciona um elemento em uma posição específica da lista, movendo os outros elementos, se necessário.
- **obter(int posicao)**: Retorna o elemento na posição indicada.
- **posicaoDe(Object elemento)**: Retorna a posição de um elemento na lista. Retorna `-1` caso o elemento não esteja presente.
- **remover(int posicao)**: Remove o elemento da posição indicada, realocando os elementos subsequentes.
- **remover(Object elemento)**: Remove o elemento especificado da lista, se ele estiver presente.
- **obterNumElementos()**: Retorna o número de elementos presentes na lista.

### `Main.java`

O arquivo `Main.java` contém um programa que demonstra como criar e manipular uma lista com a classe `ListaArray`. O programa realiza as seguintes operações:

1. Adiciona elementos à lista.
2. Adiciona um elemento em uma posição específica.
3. Remove um elemento pela posição.
4. Busca a posição de um elemento.
5. Remove um elemento pelo próprio objeto.

### Constantes e Atributos

- **TAMANHO_INICIAL**: Define o tamanho inicial do array (valor: 3).
- **FATOR_CRESCIMENTO**: Define o número de posições que o array crescerá quando não houver mais espaço disponível (valor: 5).
- **NAO_ESTA_PRESENTE**: Código retornado quando um elemento não é encontrado (valor: -1).

## Como Executar

Para executar o código:

1. Certifique-se de ter o JDK (Java Development Kit) instalado.
2. Compile os arquivos:
   ```bash
   javac ListaArray.java Main.java
    ```

3. Execute o programa:
   ```bash
   java Main
    ```

