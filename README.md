
# IAS Computer simulator In Python

🇺🇸 Project development for homework of the subject Architecture and Organization of Computers, Bachelor's Degree in IT in Stadual University of Maringá.

🇧🇷 Projeto desenvolvido para o trabalho da matéria Arquitetura e Organização de Computadores, curso de Informática( Universidade Estadual de Maringá ).




## What is?

🇺🇸 A Simulator of the IAS Computer, is a student language, has no application to be used on Systems Interface, due to this necessity, this simulator reads a code written in IAS and return the results.

🇧🇷 Um simulador do computador IAS, é uma linguagem estudantil ou seja, não tem aplicação ou linguagem para ser usada na interface do Sistema, devido essa necessidade, esse simulador lê um código escrito em IAS e retorna os resultados.
## How Works?

=========🇺🇸=============

The Simulator starts, asks the number of memory spaces it will have on the IAS computer, then asks for a file to be read in text format, it must be in the same folder, this file must be written in the form of the IAS computer, with a instruction per line. If the file is non-existent, the user is asked if he wants to create a file, if yes, the user must pass the instructions one at a time, if not, the program is closed.

After reading the file and instructions, it passes the results in Binary and decimal, binary which is how the computer operates and in decimal for the user to understand.

=========🇧🇷=============

O Simulador inicia, pergunta a quantidade de espaços de memórias que terá no computador IAS, após pede um arquivo para ser lido em formato de texto, o mesmo deve estar na mesma pasta, este arquivo deve estar escrito na forma do computador IAS, com uma instrução por linha. Caso o arquivo seja inexistente, é perguntado ao usuário se ele deseja criar um arquivo, se sim, o usuário deverá passar as instruções uma por vez, se não, o programa é fechado.

Após a leitura do arquivo e das instruções, o mesmo passa os resultados em Binário e em decimal, binário que é como o computador opera e em decimal para o usuário entender.
## The IAS Computer

🇺🇸 The first generation of computers used vacuum tubes for digital logic elements and memory. A
number of research and then commercial computers were built using vacuum tubes. For our
purposes, it will be instructive to examine perhaps the most famous first-generation computer, known
as the IAS computer. This example illustrates many of the fundamental concepts found in all computer
systems.
A fundamental design approach first implemented in the IAS computer is known as the stored-
program concept. This idea is usually attributed to the mathematician John von Neumann. Alan Turing
developed the idea at about the same time. The first publication of the idea was in a 1945 proposal by
von Neumann for a new computer, the EDVAC (Electronic Discrete Variable Computer)

🇧🇷 A primeira geração de computadores usava tubos de vácuo para elementos lógicos digitais e memória. A
várias pesquisas e, em seguida, computadores comerciais foram construídos usando tubos de vácuo. Para nós
Para fins, será instrutivo examinar talvez o mais famoso computador de primeira geração, conhecido
como o computador IAS. Este exemplo ilustra muitos dos conceitos fundamentais encontrados em todos os computadores
sistemas.
Uma abordagem de design fundamental implementada pela primeira vez no computador IAS é conhecida como método armazenado
conceito de programa. Esta ideia é geralmente atribuída ao matemático John von Neumann. Alan Turing
desenvolveu a ideia quase ao mesmo tempo. A primeira publicação da ideia foi numa proposta de 1945 de
von Neumann para um novo computador, o EDVAC (Electronic Discrete Variable Computer)
## Examples

Temperature conversor in IAS Computer.

[30, 9, 5, 32, 273] is the measures to convert. 30 is in Celsius, 9, 5 and 32 is used to convert to Fahrenheit, and 273 to Kelvin.

```
30
9
5
32
273
LOADMQMX M(0)
MUL M(1)
DIV M(2)
LOADMQ M(1)
ADD M(3)
STOR M(18)
LOAD M(0)
ADD M(4)
STOR M(19)
```


![img](https://i.imgur.com/fW7U7ee.png)

![img](https://i.imgur.com/9g798Nx.png)

![img](https://i.imgur.com/9zNEMxT.png)

In this case, we have 20 memory spaces, in the IAS Code, the Temperature in Fahrenheit is in memory space 18 and the Kelvin temperature is in 19.
So, 30 in Celsius  is 86 in Fahrenheit and 303 in Kelvin.