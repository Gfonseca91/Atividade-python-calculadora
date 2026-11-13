# 🧮 Calculadora Interativa em Python

Este é um projeto simples e eficiente de uma **Calculadora Interativa via Terminal** desenvolvida em Python. O objetivo principal é demonstrar o uso de funções, estruturas condicionais e de repetição para realizar operações matemáticas básicas de forma simples.

---

## 🚀 Funcionalidades

*   **Soma (`+`)**: Soma dois números decimais.
*   **Subtração (`-`)**: Calcula a diferença entre dois números.
*   **Multiplicação (`*`)**: Multiplica dois números.
*   **Divisão (`/`)**: Divide dois números com tratamento robusto para evitar erros de divisão por zero (`0`).
*   **Interface Interativa**: Menu simples no terminal que permite realizar múltiplas operações até que o usuário decida sair.

---

## 🛠️ Tecnologias Utilizadas

*   **Linguagem:** Python 3.x
*   **Ambiente de Execução:** Google Colab / Terminal Local

---

## 📋 Como Executar

1.  **Passo 1:** Execute a primeira célula do notebook que contém as definições das funções matemáticas (`somar`, `subtrair`, `dividir`, `multiplicar`).
2.  **Passo 2:** Execute a segunda célula para iniciar o loop interativo.
3.  **Passo 3:** Escolha a opção desejada no menu digital digitando o número correspondente:
    *   `1` para Somar
    *   `2` para Subtrair
    *   `3` para Dividir
    *   `4` para Multiplicar
    *   `0` (ou `5`) para Sair

---

## 📂 Estrutura do Código

*   `somar(num1, num2)`: Retorna a mensagem com o resultado da adição.
*   `subtrair(num1, num2)`: Retorna a mensagem com o resultado da subtração.
*   `dividir(num1, num2)`: Retorna o resultado da divisão, validando se o divisor é diferente de zero.
*   `multiplicar(num1, num2)`: Retorna o resultado da multiplicação.
*   `while True`: Estrutura principal que mantém o programa rodando até o comando de parada.
