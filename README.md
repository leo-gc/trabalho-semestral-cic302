# Trabalho Semestral CIC302
Trabalho semestral passado pelo professor Nuncio Perrella na matéria CIC302 (Sistemas Digitais e Arquitetura de Computadores) do Instituto Mauá de Tecnologia, que tem como objetivo o desenvolvimento de algoritmos no simulador BIPy, o qual simula arquitetura de processador BIP.  
O [BIPy](https://github.com/JoaoVitorBranco/BIPy) foi desenvolvido por alunos do curso de Engenharia da Computação.

## Como usar
Dentro da pasta windows, execute o programa BIPy.exe. Com o programa em execução, abra a memória de dados e siga o passo a passo a seguir.  
Obs.: Lembre-se que os valores no simulador são de base hexadecimal.

### Escolha o algoritmo
Para escolher o algoritmo, basta inserir um número no endereço 000 da memória de dados que corresponde ao algoritmo desejado:  
0001: Divisão de inteiros  
0002: Multiplicação de inteiros  
0003:   
0004: Fatorial  
0005:  
0006:  

### Insira os dados desejados

#### Divisão
Insira o valor do dividendo no endereço 010 e o do divisor no endereço 011. Após o processamento, o quociente estará no acumulador e no endereço 013.

#### Multiplicação
Insira os valores do multiplicando e multiplicador nos endereços 020 e 021. Após o processamento, o produto estará armazenado no acumulador e no endereço 023.

#### Fatorial
Insira o número do qual se deseja obter o fatorial no endereço 040. Após o processamento, o resultado estará armazenado no acumulador e no endereço 042.

### Execute o algoritmo
Para executar um algoritmo, clique no botão "RESET" para reiniciar o processador e, após inserir os dados, clique no botão "HALT" para iniciar a execução.  
O botão "STEP" pode ser usado para avançar um ciclo de clock do processador.

### Aviso
Alterar endereços que não são destinados a entrada de dados pelo usuário pode impedir o funcionamento dos algoritmos.
