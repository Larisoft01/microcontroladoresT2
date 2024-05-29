# Tetris e SpaceInvaders em MicroPython

Este projeto consiste na criação de um console portário que tenha os jogos de Tetris e SpaceInvaders utilizando o MicroPython em uma placa de desenvolvimento com suporte a MicroPython e uma tela OLED. O jogo contará com quatro botões para movimentar as peças/nave e mudar a seleção dos os jogos e dois botões auxiliares que são usados para atirar, selecionar o jogo e rodar a peça no Tetris.


### Esquema Eletrico

![WhatsApp Image 2024-05-25 at 09 40 25](https://github.com/luckmigz/microcontroladores/assets/54560901/6e415620-7a3d-41e6-982f-65e82f091a9a)


### Diagrama de Blocos

![image](https://github.com/luckmigz/microcontroladores/assets/81933900/f83177d7-6a21-416e-8865-31775085df8e)



### Pré-Requisitos

- Ser portátil;
- Placa de desenvolvimento com suporte a MicroPython;
- Display grafico (Tela OLED);
- Buzzer para efeitos sonoros;
- Botão para start;

## Execução dos Testes
Para testar o funcionamento do Raspberry Pi Pico,

### Analisando os testes do Console
Os testes de ponta a ponta podem ser executados ao jogar os jogos de Tetris e Space Invaders e verificar se todos os componentes (botões e tela OLED) estão funcionando corretamente e se os jogos estão sendo executados sem erros.

### Instalação do Console
Para instalar e executar corretamente o projeto de Pong em Micropython com Raspberry Pi Pico, é importante ter conhecimento sobre o esquema de pinos para conectar cada componente.

Tela OLED: Tem que estar conectada aos GPIO14 SDA e GPIO15 SCL

Botões de Movimento: Tem que estar conectados ao GPIO1 até GPIO5, segundo o diagrama de blocos.

Botão A: Tem que estar conectado ao GPIO7.

Botão B: Tem que estar conectado ao GPIO6.

Certifique-se de que todas as conexões estejam corretas antes de prosseguir com a instalação das bibliotecas e do código do projeto.

(Cabe ressaltar que o codigo possui comentarios que torna intuitivo a mudança das pinagens)

### Implantação

Para implantar o projeto em um sistema ativo, basta copiar todos os arquivos do projeto para o Raspberry Pi Pico.

### Video funcional do Projeto






https://github.com/luckmigz/microcontroladores/assets/54560901/25c14e36-c4fa-482d-a7b1-7dd179b43818







### Feito com
-MicroPython - a linguagem de programação usada

-Raspberry Pi Pico - o microcontrolador utilizado

-Bibliotecas do python:

 -Ssd1306
 
### Analise de custo
Lista de custos:

- 1 Raspberry Pi Pico: R$ 50,00 cada.  
- 1 Tela OLED I2C: R$ 35,00 cada.
- 6 PUSH button: R$ 3,00 10 unidades.
- 1 Placa padrão 5cm x 10cm: R$ 7,90 cada.
- 1 Transistor BC547: R$ 12,60 10 unidades
- 1 Caixa 3D: R$ 10,00 cada.
- 1 Buzzer: R$ 2,48 cada.
- 1 resistor: R$ 2,00 cada.
- Componentes adicionais com baixo custo. Ex: Solda e Fios. R$ 5,00.
- Estima-se que podemos vender cada unidade no valor de R$ 157,18 (Com uma margem de lucro de aproximadamente 10%)

## 📌 Versão

O projeto se encontra na Versão 1.0

## Criadores
-Larissa Navarro Pizarro     RA:19.02028-7 </br>
-Lucas Miguel de Matos Negri RA:19.00386-2
-Matheus Igino Machado       RA:20.01629-8
-Vinicius Urias da Cruz      RA:20.00601-2

## Agradecimentos

Gostaríamos de agradecer aos nossos professores Sergio e Rodrigo pela orientação e suporte durante o desenvolvimento deste projeto.

