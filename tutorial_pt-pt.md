# Substituir a fonte de alimentação de um Amiga 2000 por uma fonte ATX

**ATENÇÃO: O autor deste guia não se responsabiliza por quaisquer danos realizados durante a operação aqui descrita. Os passos deverão ser realizados apenas por alguém com conhecimentos de electrónica.**

**ATENÇÃO: No interior das fontes de alimentação existem condensadores que armazenam elevadas cargas eléctricas, mesmo quando o computador se encontra desligado. Tocar nesses condensadores, com as mãos ou com ferramentas, é altamente perigoso.**

## Introdução

Neste guia irei mostrar como substituir a fonte de alimentação original do A2000, mantendo 3 componentes originais: a ventoinha de 80mm, a ficha de alimentação e o interruptor on/off.
Material necessário:

- Adaptador [Original/Big Box ATX](http://www.ianstedman.co.uk/Sales/IanStedmanscatalogue/ianstedmanscatalogue_2.html) vendido pelo Ian Steadman
- Fonte ATX com ventoinha de 80mm
- Alicate de corte
- Descarnador para cabos (ou a vossa forma preferida de descarnar – eu uso uma faca)
- Junções para fios (eu usei uma barra de junção e cortei consoante necessário)
- Fita isoladora ou manga termoretráctil

## Passo 1: Adaptador para fonte ATX

Inicialmente é necessário adquirir um adaptador [Original/Big Box ATX](http://www.ianstedman.co.uk/Sales/IanStedmanscatalogue/ianstedmanscatalogue_2.html) vendido pelo Ian Steadman. Existem outros adaptadores à venda, mas este tem a vantagem de já nos fornecer o sinal TICK, ao contrário dos outros.

[ inserir foto do adaptador do Ian Steadman ]

Nos PC’s modernos, para ligar o computador, temos de ter o interruptor da fonte ligado (ON) e para além disso temos de carregar no botão de Power, geralmente na parte frontal do computador.  No nosso caso, queremos que o Amiga 2000 se ligue de imediato ao ligar o interruptor da fonte de alimentação. Para isso é necessário configurar o adaptador para o switch type “latch” e sinal tick “50 Hz”:

1. Adicionar um jumper em JP4 ou ligar um fio entre os dois orifícios que se encontram abaixo do jumper JP4:

![Jumper P4](images/connect_to_switch.jpg)

2. Configurar os dois pequenos interruptores que se encontram no adaptador para as posições “On”:

