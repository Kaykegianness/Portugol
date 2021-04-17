# Portugol

VARI�VEL

1- Deve come�ar com uma letra
2- Os pr�ximos podem ser letras ou n�meros
3- N�o pode utilizar nenhum s�mbolo, exceto _
4- N�o pode conter espa�os em branco
5- N�o pode conter letras com acentos
6- N�o pode ser uma palavra reservada (mas Inicio_Algoritmo pode :)!)

TIPOS PRIMITIVOS

Inteiro     Ex: 1  3  -5  198  0
Real        Ex: 0.5  5.0  9.8  -77.3  3.1415
Caractere   Ex: "Gustavo"  "Algoritmo"  "123"
Logico      Ex: verdadeiro  falso

OPERADORES ARITM�TRICOS
                               A <- 5
                               B <- 2
+ Adi��o                       A + B = 7
- Subtra��o                    A - B = 3
* Multiplica��o                A * B = 10
/ Divis�o                      A / B = 2.5
\ Divis�o Inteira              A \ B = 2
^ Exponencia��o                A ^ B = 25
% M�dulo                       A % B = 1           != M�dulo Ex: 5 / 2 = 2 (O 2 no caso seria a divis�o inteira: \). E para o 5, restaria o 1, o que seria o M�dulo (%).

FUN��ES ARITM�TRICAS

Abs                            Valor Absoluto              Abs (-10)         10
Exp                            Exponencia��o               Exp (3,2)         9
Int                            Valor Inteiro               Int (3.9)         3
RaizQ                          Raiz Quadrada               RaizQ (25)        5
Pi                             Retorna Pi                  Pi                3.14...
Sen                            Seno (rad)                  Sen (0.523)       0.5                  !0.523 � aproximadamente em radianos 30�, sendo assim, Seno de 30 � 0.5 (O mesmo exemplo se segue a: Cos e Tan).
Cos                            Cosseno (rad)               Cos (0.523)       0.86
Tan                            Tangente (rad)              Tan (0.523)       0.57
GraupRad                       Graus para Radianos         GraupRad (30)     0.52

OPERADORES RELACIONAIS

> Maior que
< Menor que
>= Maior ou igual a
<= Menor ou igual a
= Igual a
<> Diferente de

OPERADORES L�GICOS

p        q        pEq                          p        p        pOUq
_____________________                          ______________________
V        V        V                            V        V        V
V        F        F                            V        F        V
F        V        F                            F        V        V
F        F        F                            F        F        F

p        N�Op
_____________
V        F
F        V

ORDEM DE PRECED�NCIA

Aritm�ticos     ()
                ^
                */
                +-
_____________________
Relacionais     Todos
_____________________
L�gicos         E
                OU
                N�O