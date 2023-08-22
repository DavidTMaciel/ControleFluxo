# Projeto Java: Contador de Números

Este é um projeto Java simples que implementa um contador de números baseado em dois parâmetros de entrada. O projeto inclui a definição de uma exceção personalizada chamada `ParametrosInvalidosException` para tratar casos em que os parâmetros informados são inválidos.

## Detalhes do Projeto

O objetivo deste projeto é receber dois parâmetros inteiros via terminal, representando dois números inteiros, calcular a quantidade de iterações necessárias e imprimir uma série de números incrementados no console.

### Executando o Projeto

Para executar o projeto, siga estas etapas:

1. Abra um terminal ou prompt de comando.

2. Navegue até o diretório onde o arquivo `Contador.java` está localizado.

3. Compile o arquivo `Contador.java` digitando o seguinte comando e pressionando Enter:

```shell
javac Contador.java
```

4. Execute o arquivo compilado `Contador.class` com os seguintes comandos, inserindo os valores desejados para os parâmetros:

```shell
java Contador
```

5. Siga as instruções fornecidas pelo programa para inserir os valores dos parâmetros.

### Funcionalidades

- O programa aceita dois parâmetros inteiros via terminal.
- O programa calcula a diferença entre os parâmetros e executa um loop `for` para imprimir os números incrementados.
- Se o segundo parâmetro for menor que o primeiro, uma exceção `ParametrosInvalidosException` será lançada.
