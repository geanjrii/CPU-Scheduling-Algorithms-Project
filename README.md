# Projeto de Algoritmos de Escalonamento de CPU
Este projeto implementa três algoritmos de escalonamento de CPU e calcula estatísticas com base nesses algoritmos. Os algoritmos de escalonamento implementados são FCFS, SJF e RR.

O programa lê de um arquivo uma lista de processos com seus respectivos tempos de chegada e de duração e, em seguida, imprime na tela uma tabela com as seguintes métricas: tempo de retorno médio, tempo de resposta médio e tempo de espera médio.

## Algoritmos Implementados
## FCFS (First-Come, First-Served)
O algoritmo FCFS é simples e fácil de implementar. Ele simplesmente executa os processos na ordem em que eles chegaram, sem considerar o tamanho do processo ou o tempo restante.

## SJF (Shortest Job First)
O algoritmo SJF seleciona o próximo processo com base no tamanho do processo. Ele executa primeiro os processos mais curtos, com a intenção de minimizar o tempo médio de espera.

## RR (Round Robin)
O algoritmo RR é um algoritmo de escalonamento de tempo compartilhado. Ele permite que cada processo seja executado por um período fixo de tempo (chamado de quantum) e, em seguida, interrompe o processo atual e passa para o próximo processo na fila.
