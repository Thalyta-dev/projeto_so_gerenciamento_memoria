# Projeto - Gerenciamento de memória

Projeto desenvolvido para a disciplina de sistemas operacionais, com o intuito de utilizar o gerenciamento de memória. Você encontrará aqui, 5 algoritmos de gerenciamento, o FIFO, NRU, AGING e SECOND_CHANCE e RANDOM, A linguagem  utilizada para o desenvolvimento foi C.

Neste repositório existe pasta chamada *`**massa_teste`*** nela você encontra os arquivos para testar os algoritmos construídos. Caso queira se divertir, fique a vontade para modificar ou criar mais arquivos.

## **Como executar o projeto**

Para testar um algoritmo, primeiro você precisa ter o `GCC` instalado no seu sistema, para conseguir compilar o código.

### Passo a passo para a execução

1. Vá até o seu terminal, na pasta do projeto onde se encontra o arquivo `main.c`
2. Execute o comando  *`gcc -Wall main.c -o vmm && ./vmm fifo 10 < massa_teste/anomaly.dat`*

Este comando indicado no passo 2. vai compilar o código e depois executá-lo com o algoritmo fifo, executando 10 vezes e com a estrutura de memória encontrada no arquivo anomaly.dat. Caso você queira executar outros algoritmos é só fazer a substituição no comando indicado: *`gcc -Wall main.c -o vmm && ./vmm {Algoritmo} {quantidade de execução}< massa_teste/{arquivo_de_teste.dat}`*

no parâmetro {Algoritmo}, você pode substituir por `fifo, second_chance, nru, random e aging.`

Ao executar o passo 2, você receberá como saída o número 9, que corresponde a quantidade de page fault que aconteceu.

## **Autores**

     Thalyta Maely - 6392

     Rodrigo Moreira- Professor
