# pilhas-
Exercício A3
alunos: Ana Luísa Pacífico 
RA: 1232023412
Luiz Gustavo Domingues Lacerda 
RA: 123118071

O código deverá atender às seguintes características: 

Inclusão dos processos na pilha. Uma configuração inicial deverá ser feita com todos os processos a serem incluídas na pilha. Deverá ser permitido a configuração com input dos dados de cada processo a ser trabalho na pilha. O usuário irá digitar os atributos de cada um dos processos. Ao final da entrada de dados, deverá ser mostrado, um resumo dos processos incluídos, na ORDEM DE INSERÇÃO, mostrando apenas o PID de cada processo.
Recuperação do processo a ser executado na pilha. Recuperação do último processo da pilha para execução. Deve-se mostrar uma saída de qual processo será executado (PID).
Execução do processo recuperado da pilha. A execução irá consistir em uma execução de uma espera, em segundos, configurada nos atributos do processo em questão. Deve-se dar uma saída, indicado o início da execução do processo de PID X, além de mostrar na tela que o processo está em execução (tempo em segundos está correndo), como uma barra de progresso.
Remoção do processo executado da pilha. Após a execução com sucesso do processo, ele deve ser removido da pilha. Deverá ser dado uma saída informando qual processo foi executado.
Visualização do resumo da execução: Deverá ser dada uma saída com o resumo dos processos executados, EM ORDEM DE EXECUÇÃO. Logo após essa saída, deverá ser mostrado o consumo total de memória (soma do memSize de todos os processos executados) e o tempo total gasto na execução de todos os processos.
A estrutura de cada processo deverá conter: 

PID: ID do Processo. Inteiro. Autoincremento. Deve começar em 0 e para cada inserção do usuário de novo processo, deve-se criar um PID novo com o incremento de 1;
menSize: Tamanho de Memória utilizada pelo Processo. Inteiro, deve ser cadastrado pelo usuário.
timeExecution: Tempo de execução. Inteiro. Deve ser um informando pelo usuário e deve estar entre 30 e 90 segundos.
