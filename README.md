# projeto_so_gerenciamento_memoria
Projeto feito para a disciplina de sistemas operacionais, com o intuito de fazer o gerenciamento de memória. Você encontrará aqui, 4 algoritimos de gerenciamento, o FIFO,  NRU, AGING e SECOND_CHANCE

## Como rodar o projeto

Neste projeto tem uma pasta chamada *massa_teste* nela você encontra o arquivo par teste, onde, se quiser, pode modifica-lós
Para rodar esse projeto, vá no seu terminal, até o caminho da pasta do projeto e cole o seguinte comando *gcc -Wall main.c -o vmm && ./vmm fifo 10 < massa_teste/anomaly2.dat*, ele irá compilar o seu código, e depois executar o algoritimo fila, com os dados do arquivo anomaly2.dat, e retornará a quantidade de page fault que ele teve.

Neste comando você pode mudar os parametros de algoritimo, você tem 5 opções pra colocar *fifo, random, nru, second_chance e aging*, também pode ser mudado o arquivo anomaly2.dat, com as opções *anomaly.dat, anomaly2.dat, anomaly3.dat e anomaly4.dat*


## Autores

### Thalyta Maely Correa - 6392
### Rodrigo Moreira (Professor)


