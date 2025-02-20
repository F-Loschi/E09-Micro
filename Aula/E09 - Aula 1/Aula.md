## Diferenças entre Microcontrolador e Microprocessador

### Processamento : MicroP (2GHz) X MicroC (32MHz);
### Custo : MicroP (R$ 1000,00) X MicroC (R$ 30,00);

O Microprocessador funciona para tarefas gerais e consegue, por nível de processamento, ser muito mais eficiente que um Microcontrolador. O Microcontrolador, por sua vez, funciona bem para funções específicas e que se mantêm, mediante um código (firmware) escrito em C que dita a função a ser executada. No Arduíno Uno, há um ATMEGA328P que é o microcontrolador responsável pelas execuções das tarefas do arduíno, funcionando como um "cérebro" para o arduíno. O arduíno em si não é programado em C, mas seu microcontrolador sim.


## Microcontrolador

Componentes principais: 

- Unidade de processamento;
- Memória;
- Periféricos - Timer, UART e Conversor Analógico-Digital.

### Tipos de memórias

Memória de Programa - Dados são salvos se computador desligado("HD");
Memória de Dados - Memória volátil em que há perdas de dados(RAM).

Modificadores de tipos de dados

- Signed(com sinal pos ou neg);
- Unsigned(Apenas números positivos);
- Short(Menor que inteiros);
- Long(Maior que inteiros).

// Operadores duplos são usados em comparações de variáveis e valores.  
// Operadores simples(lógicos) são usados para comparar bits um a um.  
// Operadores lógicos: &(and), |(or), ^(xor), >>(deslocamento pra direita), <<(deslocamento pra esquerda).  
// Deslocamentos são usados para fazer multiplicações. Para multiplicar um binário por 4, devemos  
// deslocar para a esquerda duas vezes (2^2). Se quisermos dividir, devemos deslocar para a direita.
