
# Código COBOL - Calculadora

## Introdução
Este documento fornece uma visão geral do código fonte da calculadora escrita em COBOL. O código permite que o usuário selecione uma operação (soma, subtração, divisão ou multiplicação) e insira dois números para realizar a operação desejada.

## Estrutura do Código
O código está estruturado em seções distintas de acordo com as convenções do COBOL. Ele consiste nas seguintes seções:

1. **IDENTIFICATION DIVISION:** Define o nome do programa (`CALCULADORA`).
2. **DATA DIVISION:** Declara as variáveis utilizadas no programa.
3. **PROCEDURE DIVISION:** Contém a lógica do programa, incluindo a definição de procedimentos para cada operação matemática.

## Variáveis
O programa utiliza as seguintes variáveis:

- **WS-MODO:** Variável para armazenar o modo de operação selecionado pelo usuário.
- **WS-NUM-1 e WS-NUM-2:** Variáveis para armazenar os dois números inseridos pelo usuário.
- **WS-RESULTADO:** Variável para armazenar o resultado da operação matemática.

## Procedimentos
O programa define procedimentos para cada operação matemática:

- **PROC-SOMAR:** Realiza a operação de soma.
- **PROC-SUBTRAIR:** Realiza a operação de subtração.
- **PROC-DIVIDIR:** Realiza a operação de divisão.
- **PROC-MULTIPLICAR:** Realiza a operação de multiplicação.
- **PROC-ENCERRAR:** Encerra a execução do programa.

## Fluxo de Execução
O programa segue o seguinte fluxo de execução:

1. Inicialização das variáveis.
2. Exibição do menu de seleção de operações.
3. Solicitação para inserir os números.
4. Execução da operação selecionada pelo usuário.
5. Exibição do resultado da operação.
6. Pergunta se o usuário deseja continuar ou encerrar o programa.
7. Encerramento do programa, se solicitado.

## Como Executar
O código pode ser compilado e executado utilizando [OpenCobolIDE](https://opencobolide.software.informer.com/4.7/).

## Conclusão
Este programa em COBOL fornece uma demonstração simples de como implementar uma calculadora básica. Ele pode ser expandido e modificado para adicionar mais funcionalidades conforme necessário.

---