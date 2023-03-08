# MDC - MÁXIMO DIVISOR COMUM
* Qual o M.D.C entre 32 e 48?

## MÉTODO CONVÊNCIONAL
* $D(32) = \{1, 2, 4, 8, 16, 32\}$
* $D(48) = \{1, 2, 3, 4, 6, 8, 12, 16, 24, 48\}$
* $M.D.C(32, 48) = 16$

## MÉTODO PRÁTICO
* A divisão é feita somente por números primos.
* Somente multiplicar primos que dividem todos os números da linha.
    * Caso isso não ocorra nenhuma vez, o resultado é $1$.

$$
\begin{array}{c|c}
    32, 48 & 2 \\
    16, 24 & 2 \\
    8, 12 & 2 \\
    4, 6 & 2 \\
    2, 3 & 2 \\
    1, 3 & 3 \\
    1, 1
\end{array}
$$

$$2 \times 2 \times 2 \times 2 = 16$$
* $M.D.C(8, 12) = 16$
