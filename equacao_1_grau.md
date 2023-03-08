# SISTEMA DE EQUAÇÕES DO 1º GRAU

## MÉTODO DA SUBSTITUIÇÃO

$$
\begin{cases}
    \begin{array}{r c r c r}
        2x & + & y & = & 5 \\
         x & + & 2y & = & 4
    \end{array}
\end{cases}
$$

### PASSO 1
* Escolher uma das equações para isolar uma das incógnitas.

$$
\begin{cases}
    \begin{array}{r r r r}
        2x & + & y & = & 5 & \to & y = 5 - 2x \\
         x & + &2y & = & 4
    \end{array}
\end{cases}
$$

### PASSO 2
* Pegar a outra equação e substituir a incógnita pela equação criada no \
**PASSO 1**.

$$
\begin{cases}
    \begin{array}{r r r c l c l}
        2x & + & y & = & 5 \\
         x & + &2y & = & 4 & \to & x + 2.(5 - 2x) = 4
    \end{array}
\end{cases}
$$

* Resolver a equação e encontrar o 1º par ordenado.

$$
x + 2.(5 - 2x) = 4 \\
x + 10 - 4x = 4 \\
x - 4x = 4 - 10 \\
-3x = -6 \\
-3x.(-1) = -6.(-1) \\
3x = 6 \\
x = \frac{6}{3} \\
x = 2
$$

### PASSO 3
* Pegar a equação encontrada no **PASSO 1** e substiuir a incógnita pelo \
resultado encontrado no **PASSO 2**.
* Resolver a equação e encontrar o 2º par ordenado.

$$
\begin{cases}
    \begin{array}{r r r r}
        2x & + & y & = & 5 & \to & y = 5 - 2x & \to & y = 5 - 2.(2)\\
         x & - &2y & = & 4
    \end{array}
\end{cases}
$$

$$
y = 5 - 2.(2) \\
y = 5 - 4 \\
y = 1
$$

### PASSO 4

* Escrever o conjunto solução correspondente ao sistema de equações do com os \
pares ordenados encontrados.

$S = \big\{(2, 1)\big\}$

## MÉTODO DA ADIÇÃO

O objetivo é zerar uma das incógnitas somando os termos correspondentes das \
equações.

$$
\begin{cases}
    \begin{array}{r c r c l}
        2x & + & y & = & 5 \\
         x & + & 2y & = & 4
    \end{array}
\end{cases}
$$

### PASSO 1

* Analisar qual incógnita deseja zerar.
* Analisar qual equação desaja alterar.
    * Pode não ser necessário alterar.
    * Pode ser necessário alterar só uma equação.
    * Pode ser necessário alterar as duas equações.

### PASSO 2

* Se necessário alterar uma das equações, descobriar por qual número \
múltiplicar.

Vamos zerar o termo x, nesse caso é fácil perceber visualmente que para zerar \
o x da equação debaixo precisa valer -2.

**Caso precise faça o MMC**: 
$$
m.m.c (2,1) = 2 \\
2,1 \mid 2 \\
1,1 \mid
$$

### PASSO 3

* Multiplicar toda a equação escolhida pelo M.M.C encontrado.

$$
\begin{cases}
    \begin{array}{r c r c l}
        2x & + & y & = & 5 \\
        (x & + & 2y & = & 4).(- 2) & \to & -2x -4y = -8
    \end{array}
\end{cases}
$$

### PASSO 4

* Some os termos correspondentes e forme uma única equação com uma única \
incógnita.

$$
+
\begin{cases}
    \begin{array}{r c r c r}
        & 2x & + & y & = & 5 \\
        - & 2x & - & 4y & = & -8 \\
        \hline
        & 0 & - & 3y & = & -3
    \end{array}
\end{cases}
$$

### PASSO 5

* Resolver a equação e encontrar o 1º par ordenado.

$$
-3y = -3 \\
-3y.(-1) = -3.(-1) \\
3y = 3 \\
y = \frac{3}{3} \\
y = 1
$$

### PASSO 6

* Pegar qualquer uma das equações inicias e substiuir a incógnita pelo \
resultado encontrado no **PASSO 5**.
* Resolver a equação e encontrar o 2º par ordenado.


$$
2x + y = 5 \\
2x + 1 = 5 \\
2x = 5 - 1 \\
2x = 4 \\
x = \frac{4}{2} \\
x = 2
$$

### PASSO 7
* Escrever a solução do conjunto dos pares ordenados encontrados.

$$S = \big\{(2, 1)\big\}$$

### MÚLTIPLICAR AMBAS AS EQUAÇÕES

$$
\begin{cases}
    \begin{array}{r c r c r}
        3x & + & 4y & = & 10 \\
        2x & + & 5y & = &  9
    \end{array}
\end{cases}
$$

No caso acima para zerar qualquer uma das incógnitas é preciso mútiplicar as \
duas equaçõs por algum número.

Então escolha qual incógnita quer zerar e depois disso encontre o m.m.c delas.

Após encontrado o m.m.c, múltiplique cada equação pelo número que faça as \
incógnitas terem o mesmo valor.

$$
2,3 \mid 2 \\
1,3 \mid 3 \\
1,1 \\
$$

$$
2.3 = 6
$$

$$m.m.c (2,3) = 6$$

$$
\begin{cases}
    \begin{array}{r c r c l}
        (3x & + & 4y & = & 10).2 \\
        (2x & + & 5y & = & \ \ 9).(-3)
    \end{array}
\end{cases}
$$

$$
+
\begin{cases}
    \begin{array}{c r c r c r}
        & 6x & + & 8y & = & 20 \\
        - & 6x & - & 15y & = & -27 \\
        \hline
        & 0 & - & 7y & = & -7
    \end{array}
\end{cases}
$$

$$
-7y = -7 \\
-7y . (-1) = -7 . (-1) \\
7y = 7 \\
y = \frac{7}{7} \\
y = 1
$$

$$
3x + 4y = 10 \\
3x + 4.1 = 10 \\
3x = 10 - 4 \\
3x = 6 \\
x = \frac{6}{3} \\
x = 2
$$

$$S = \big\{(2, 1)\big\}$$

### SEM PRECISAR MULTIPLICAR

$$
\begin{cases}
    x & + & y & = & 48 \\
    x & - & y & = & 8
\end{cases}
$$

$$
+
\begin{cases}
    \begin{array}{r r c r}
        x & + & y & = & 48 \\
        x & - & y & = & 8 \\
        \hline
        2x & - & 0 & = & 56
    \end{array}
\end{cases}
$$

$$
2x = 56 \\
x = \frac{56}{2} \\
x = 28
$$

$$
x + y = 48 \\
28 + y = 48 \\
y = 48 - 28 \\
y = 20
$$

$$S = \big\{(28, 20)\big\}$$
