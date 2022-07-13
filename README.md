# Modelagem de um inversor

Este arquivo trata-se de um modelo implementado no ATP-Draw de um inversor de frequência

O Model Source gera um sinal de referência, este sinal pode ser de duas maneiras:

* Senoide com amplitude e frequência determinada clicando no bloco;
* Onda de frequência variável, sendo a frequ~encia fundamental e a amplitude também especificada clicando no bloco

O Model Inversor, apresenta a lógica em PWM segundo uma onda triangular portadora, cuja amplitude e frequência também pode ser alterada clicando no bloco.

Ao partir disso, o Model Inversor gera o sinal de chaveamento dos IGBT's.

Um indutor de ordem elevada é clocado no terminal do inversor, com o intuito de funcionar como filtro.

Um resistor de 1k modela uma carga de impedância constante, de onde será lida o formato da tensão de saída;

A fonte de 400 Vdc modela uma fonte primária de energia.
