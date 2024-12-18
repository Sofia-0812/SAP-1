# SAP-1
Este projeto busca a melhoria e expansão funcional da arquitetura do processador SAP-1, realizado para a disciplina de Arquitetura de Computadores 1.

Esse projeto foi uma modificação do trabalho feito pelo grupo do:
- André Luís Silva de Paula
  
Acrescentando as funcionalidades presentes no trabalho feito pelo grupo do:
- Gabriel Jota Lizardo

O projeto foi disponibilizado pelo professor Cláudio Dias Campos.

> [!WARNING]
> Compatibilidade: Este projeto é compatível exclusivamente com o simulador [Logisim](http://www.cburch.com/logisim/). Não é garantido que funcione no [Logisim Evolution](https://github.com/logisim-evolution/logisim-evolution).

## Grupo
- Davi Godoi Grilo
- Gabriel Henrique Pereira Carvalhaes
- João Victor de Almeida Maia
- Paula de Nogueira Castro Carvalho
- Sofia Grossi Vieira Santos

## Sobre o projeto
O projeto utiliza a microprogramação, assim como o projeto do André, que consiste em armazenar as microinstruções em uma ROM (Read-Only Memory), em vez de gerá-las a partir de uma matriz de controle. Essa ROM, que armazena as microinstruções, é endereçada com base nos códigos de operação das instruções e nos estados do contador em anel (T1 a T6). Isso facilita bastante as expansões, permitindo alterar o conjunto de instruções sem muita dificuldade. Com isso, acrescentamos ao projeto do André as funcionalidades do projeto do Gabriel, como as instruções MUL, DIV, JMP e SV, por exemplo, e a possibilidade de realizar operações como exibir a sequência de Fibonacci. Além disso, adicionamos algumas instruções que não estavam presentes nos trabalhos de base, como INC e DEC.

## Vídeo Demonstrativo
<p align="center">
	<a href="https://www.youtube.com/watch?v=PljYwo1bpDM">
		<img src="https://img.youtube.com/vi/PljYwo1bpDM/maxresdefault.jpg" width="500" alt="SAP-1 Turbo - AC1">
	</a>
</p>

## Como Executar
O sistema utiliza duas ROMs no contador-sequenciador: uma para endereços e outra para o controle. Caso as ROMs não contenham o conteúdo correto, você pode carregá-las a partir de arquivos de texto.

Arquivos de ROM
Os arquivos necessários para as ROMs estão disponíveis na pasta [`/conteudos_roms`](/conteudos_roms/).
