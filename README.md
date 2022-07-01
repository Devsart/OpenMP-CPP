# Relatório OpenMP-CPP

o arquivo "main.cpp" é um arquivo C++ compilável que contém as instruções para serem executadas e tempos a serem marcados.
Foram testadas as tratativas O1 O2 e O3 de compilação e os resultados foram os seguintes:

![Resultados Compilador](https://i.ibb.co/nLTbLR5/resultados-O.png)

Por outro lado, é possível compilar utilizando a opção de gerenciar o paralelismo utilizando o OpenMP utilizando a flag -fopenmp no compilador gcc/g++.
Para definir o número de Threads é necessário modificar a variável de ambiente OMP_NUM_THREADS antes de executar o código. Foram testados então as opções com 2,4 e 8 Threads.
Por fim, foi verificado que não houve uma efetividade do paralelismo neste código.

![Resultados OpenMP](https://i.ibb.co/Bq9MPY1/resultados-OMP.png)
