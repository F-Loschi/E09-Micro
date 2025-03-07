# Aula
---
## Registradores flutuantes:
Registradores que não estão nem ligados no terra nem no vcc, seu valor pode flutuar entre 0 e 1, não se tendo certeza o que ele assume, sendo então chamados de registradores flutuantes

---
## Resistor de pull-up / pull down:
São usados quando uma entrada digital do micro-controlador não está conectada nem à ***vcc*** e nem à ***gnd***

![image](https://github.com/user-attachments/assets/b0796516-8b48-40a0-96ce-620f846ab985)


---
## Utilização de máscaras
* Ligar um ou mais pinos sem alterar os demais:
	* Faz uma operação lógica | para as casas onde eu quero ligar
	* PORTD = 0b11001011;
	* PORTD = 0b11001011 | 0b00100100;
	* O que vem depois do | é chamado de ***máscara*** 
	* PORTD = PORTD | (1<<PD5) | (1<<PD2);
	* PORTD |= (1<<PD5) | (1<<PD2);
	* [![imagem-2025-03-07-113314508.png](https://i.postimg.cc/Wb91TDYw/imagem-2025-03-07-113314508.png)](https://postimg.cc/56CVmtVX)
* Desligar um pino sem alterar os demais:
	* Faz uma operação lógica & para as casas onde eu quero desligar
	* PORTD = 0b11000101 & 0b11111011;
	* PORTD = PORTD & ~(1<<PD2);
		* ~(1<<PD2):
			* (1<<PD2) deixaria só o PD2 como 1
			* O ~ inverte isso, que deixa só o PD2 como 0
	* PORTD &= ~(1<<PD2)
	* ![image](https://github.com/user-attachments/assets/255baeb3-ed61-4c0a-ae2e-66705ddbfd34)


