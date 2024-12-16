# Respostas Avaliação

Aluno: Fabiana Campos Serra dos Santos 20231014040033 e Wesley Costa da Silva 20222014040017

## Questão 1

Um sistema operacional (SO) gerencia os recursos de hardware e software de um computador para garantir **eficiência** (uso otimizado dos recursos) e **segurança** (proteção contra acessos não autorizados ou erros). Os principais aspectos do gerenciamento são:  

1. Gerenciamento de processos  
- O SO controla a execução dos programas, dividindo o tempo de CPU entre processos para garantir multitarefa.  
- Utiliza escalonadores (como FIFO ou Round Robin) para decidir a ordem de execução dos processos.  
- **Exemplo**: Quando um usuário edita um documento enquanto ouve música, o SO alterna rapidamente entre os processos para que ambos pareçam executar simultaneamente.  
- Garante segurança isolando processos uns dos outros, evitando que erros em um programa afetem outros.  

2. Gerenciamento de memória  
- O SO aloca e monitora o uso da memória RAM pelos processos, garantindo que cada um tenha os recursos necessários sem ultrapassar seus limites.  
- Gerencia a memória virtual, permitindo que programas maiores do que a memória disponível sejam executados utilizando o disco rígido como extensão.  
- **Exemplo**: Ao abrir várias abas no navegador, o SO aloca memória suficiente para cada aba e reutiliza-a ao fechar uma aba.  

3. Gerenciamento de dispositivos de entrada e saída (E/S)  
- Controla o acesso aos dispositivos, como teclado, mouse, impressoras e discos rígidos, garantindo que vários processos possam utilizá-los sem conflitos.  
- Utiliza drivers para traduzir comandos do software em instruções que o hardware compreende.  
- **Exemplo**: Quando um usuário clica em "Imprimir", o SO organiza as tarefas na fila de impressão para que várias solicitações sejam atendidas sem problemas.  

4. Gerenciamento de arquivos  
- O SO organiza os dados no sistema de arquivos, permitindo criação, leitura, escrita e exclusão de arquivos.  
- Garante a segurança por meio de permissões de acesso (por exemplo, leitura, escrita e execução).  
- **Exemplo**: Um sistema operacional como Windows utiliza o NTFS para organizar e proteger dados, enquanto no Linux o ext4 é um dos sistemas de arquivos mais comuns.  

