# Passo a passo:
1) Definir entradas e saídas(DDRx)
  * DDRD = 0b00000000; (Estamos usando todos como entrada)
  * DDRB = 0b00100000; (Pois estou usando só o PB5 como saída)
  * DDRC = 0b00100010; (Pois só o PC5 e o PC1 são saída)
2) Ligando/desligando os pinos de saída(PORTx) ➜ PORT é um registrador
  * PORTB = 0b00100000; (Isso liga o pino PB5)
  * PORTC = 0b00000010; (Isso liga o pino PC1)
