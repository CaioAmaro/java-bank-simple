Sistema de Gerenciamento de Conta Bancária

Este é um programa simples em Java para gerenciamento básico de uma conta bancária.
Permite consultar saldo, receber valores, transferir valores e encerrar a sessão.
📋 Funcionalidades

    📄 Mostrar informações do cliente

    💵 Consultar saldo atual

    ➕ Receber um valor na conta

    ➖ Transferir valor (com validação de saldo suficiente)

    🚪 Encerrar o programa

🛠️ Tecnologias

    Java (linguagem principal)

    DecimalFormat (formatação de valores monetários)

    Scanner (entrada de dados pelo teclado)

🚀 Como executar

    Clone ou copie o projeto para sua máquina.

    Compile o arquivo Main.java.

    Execute o programa.

    Siga as instruções no console.

Exemplo de execução:

javac Main.java
java Main

🔎 Fluxo do Programa

    O usuário informa:

        Nome

        Tipo da conta

        Saldo inicial

    O menu principal é exibido:

    Operações

    1 - Consultar saldos
    2 - Receber valor
    3 - Transferir valor
    4 - Sair

    Dependendo da opção escolhida:

        1: Exibe nome, tipo de conta e saldo formatado (R$ 0.00).

        2: Permite receber um valor (não aceita valor ≤ 0).

        3: Permite transferir valor (não aceita saldo insuficiente ou valor ≤ 0).

        4: Encerra o programa.

📄 Organização do Código

    clienteShow(): Exibe as informações do cliente formatadas.

    menu(): Mostra o menu de operações.

    receberValor(): Gerencia a entrada de dinheiro na conta.

    transferirValor(): Gerencia a saída de dinheiro da conta.

    main(): Controla o fluxo principal do programa.

📌 Observações

    O saldo é formatado usando DecimalFormat("0.00") para manter sempre duas casas decimais.

    Todas as entradas de valor são validadas para evitar erros.

    O programa só termina quando o usuário escolhe a opção 4.
