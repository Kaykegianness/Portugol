# Portugol

VARIÁVEL

1- Deve começar com uma letra
2- Os próximos podem ser letras ou números
3- Não pode utilizar nenhum símbolo, exceto _
4- Não pode conter espaços em branco
5- Não pode conter letras com acentos
6- Não pode ser uma palavra reservada (mas Inicio_Algoritmo pode :)!)

TIPOS PRIMITIVOS

Inteiro     Ex: 1  3  -5  198  0
Real        Ex: 0.5  5.0  9.8  -77.3  3.1415
Caractere   Ex: "Gustavo"  "Algoritmo"  "123"
Logico      Ex: verdadeiro  falso

OPERADORES ARITMÉTRICOS
                               A <- 5
                               B <- 2
+ Adição                       A + B = 7
- Subtração                    A - B = 3
* Multiplicação                A * B = 10
/ Divisão                      A / B = 2.5
\ Divisão Inteira              A \ B = 2
^ Exponenciação                A ^ B = 25
% Módulo                       A % B = 1           != Módulo Ex: 5 / 2 = 2 (O 2 no caso seria a divisão inteira: \). E para o 5, restaria o 1, o que seria o Módulo (%).

FUNÇÕES ARITMÉTRICAS

Abs                            Valor Absoluto              Abs (-10)         10
Exp                            Exponenciação               Exp (3,2)         9
Int                            Valor Inteiro               Int (3.9)         3
RaizQ                          Raiz Quadrada               RaizQ (25)        5
Pi                             Retorna Pi                  Pi                3.14...
Sen                            Seno (rad)                  Sen (0.523)       0.5                  !0.523 é aproximadamente em radianos 30º, sendo assim, Seno de 30 é 0.5 (O mesmo exemplo se segue a: Cos e Tan).
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

OPERADORES LÓGICOS

p        q        pEq                          p        p        pOUq
_____________________                          ______________________
V        V        V                            V        V        V
V        F        F                            V        F        V
F        V        F                            F        V        V
F        F        F                            F        F        F

p        NÃOp
_____________
V        F
F        V

ORDEM DE PRECEDÊNCIA

Aritméticos     ()
                ^
                */
                +-
_____________________
Relacionais     Todos
_____________________
Lógicos         E
                OU
                NÃO