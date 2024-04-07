# Trabalho Avaliativo de Teoria da Computação

## Grupo

- [Kimberly](https://github.com/KimberlyScaldaC)
- [Vinícius](https://github.com/YellowMelro)
- [Vitor](https://github.com/OCVitin)

## Exercícios:

1 - fazer a máquina de touring com 3 fitas para reconhecer L={an bn cn, n>=0}.

<img src="/Imagens/Ativ1.png">

2 - fazer a máquina de touring com 1 fita para reconhecer L={an bn cn, n>=0}.

<img src="/Imagens/Ativ2.png">

3 - fazer a máquina de touring com 1 fita para reconhecer L={an bn cn dn, n>=0}.

<img src="/Imagens/Ativ3.png">

4 - fazer a máquina de touring com 4 fitas para reconhecer L={an bn cn dn, n>=0}.

<img src="/Imagens/Ativ4.png">

5 - Construa uma máquina de Turing que conte o número de a’s de uma cadeia de caracteres (Σ = {a, b} ). A MT é iniciada com a cabeça sobre o primeiro carácter da cadeia (ex. q0 abababbba). Deve parar à direita da cadeia com a cabeça a apontar para o número de ocorrências do carácter a (abababbba□ qf 1111).

<img src="/Imagens/Ativ5.png">

6 - Construa uma MT que dada uma cadeia de caracteres (Σ = {0, 1}) ordene essa cadeia. A MT é iniciada com a cabeça sobre o primeiro carácter da cadeia (ex. q0 1000110) e deve parar com a cabeça sobre o primeiro carácter da cadeia ordenada(ex. qf 0000111).

<img src="/Imagens/Ativ6.png">

7 - Construa uma MT (Σ = { a, b}) que detecte se uma cadeia é um palíndromo.

<img src="/Imagens/Ativ7.png">

8 - Construa uma MT que reconheça as seguintes linguagens:

a) fazer L = {w | na(w) = nb(w) = nc(w)} com 1 fita e com 3 fitas.

<img src="/Imagens/Ativ8a1fita.png">
<img src="/Imagens/Ativ8a3fitas.png">

b) fazer L = {an b2n c3n | n >= 0}com 1 fita e com 3 fitas.

<img src="/Imagens/Ativ8b1fita.png">
<img src="/Imagens/Ativ8b3fitas.png">

c) fazer L = {w | o décimo símbolo da direita para a esquerda é a} com 1 fita.

<img src="/Imagens/Ativ8c1fita.png">

d) fazer L = {ai bj ak | i = j ou j = k} com 1 fita e com 3 fitas.

<img src="/Imagens/Ativ8d1fita.png">
<img src="/Imagens/Ativ8d3fitas.png">

e) fazer L = {ai bj ak | i < j < k} com 1 fita e com 3 fitas.

<img src="/Imagens/Ativ8e1fita.png">
<img src="/Imagens/Ativ8e3fitas.png">

f) fazer L = {an b3n | n >= 1} com 1 fita e com 2 fitas.

<img src="/Imagens/Ativ8f1fita.png">
<img src="/Imagens/Ativ8f2fitas.png">

9 - Projete Máquinas de Turing que calcule as funções:
Obs: sugestão: usar duas fitas. Avaliar se precisa de mais fitas.

a) f(x, y) = x - y, para x e y inteiros e positivos, com x > y.

<img src="/Imagens/Ativ9a2fitas.png">


b) f(x, y) = 3*x, para x inteiro e positivo.

<img src="/Imagens/Ativ9b2fitas.png">

c) f(x, y) = x * y, para x e y inteiros e positivos.

<img src="/Imagens/Ativ9c2fitas.png">

d) fatorial de A, sendo A um número inteiro positivo.

<img src="/Imagens/Ativ9d2fitas.png">

e) pot(x,y) = (x ^y), para x e y inteiros positivos.

<img src="/Imagens/Ativ9e3fitas.png">

f) f(x,y) = x + y para x e y inteiros positivos.

<img src="/Imagens/Ativ9f2fitas.png">

g) teste(A > B): nos inteiros positivos.

<img src="/Imagens/Ativ9g2fitas.png">

h) teste (A >= B): nos inteiros positivos.

<img src="/Imagens/Ativ9h2fitas.png">

i) teste (A <=B) : nos inteiros positivos.

<img src="/Imagens/Ativ9i2fitas.png">

10 - 

a) Qual a linguagem aceita pela máquina de Touring M = ({q0, q1, q2, q3}, {a, b}, {a, b, □}, δ, q0, {q3}), onde
>
>δ (q0, a) = (q1, a, R),
>
>δ (q0, b) = (q2, b, R),
>
>δ (q1, b) = (q1, b, R),
>
>δ (q1, □) = (q3, □, R),
>
>δ (q2, a) = (q3, a, R),
>
>δ (q2, b) = (q2, b, R).
>
<img src="/Imagens/Ativ10a1fita.png">

L = {bn a | n >= 0}

b) Qual a linguagem aceita pela máquina de Touring M = ({q0, q1, q2, q3}, {a, b}, {a, b, □}, δ, q0, {q3}), onde
>
>δ (q0, a) = (q1, a, R),
>
>δ (q0, b) = (q2, b, R),
>
>δ (q1, b) = (q1, b, R),
>
>δ (q1, □) = (q3, □, R),
>
>δ (q2, b) = (q2, b, R),
>
>δ (q2, a) = (q3, a, R).
>
<img src="/Imagens/Ativ10b1fita.png">

L = {a b*, b* a}

c) Qual a linguagem aceita pela máquina de Touring M = ({q0, q1, q2, qf}, {0, 1}, {0, 1, □}, δ, q0, {qf}), onde
>
>δ (q0, □) = (q0, □, R),
>
>δ (q0, 1) = (q1, 1, R),
>
>δ (q1, 0) = (q2, 0, R),
>
>δ (q2, 1) = (q2, 1, R),
>
>δ (q2, □) = (qf, □, R),
>
<img src="/Imagens/Ativ10c1fita.png">

L = {1 0 1*}

11 - Construa uma máquina de touring que calcule o tamanho de uma cadeia w, onde w pertence ao conjunto {a, b}*, no qual o tamanho deve ser escrito na base unária. (A máquina de Touring irá simular o comando strlen() da linguagem C). Por exemplo: entrada = abaaba, saída = abaaba$111111.
Usar quantas fitas achar necessário.

<img src="/Imagens/Ativ112fitas.png">

12 - Construa uma máquina de touring que simule o comando strncpy(w1, w2, qt) da linguagem C, sabendo que as cadeias são do tipo {a, b}* e a quantidade estará escrita na base unária. Por exemplo: se entrada = aaabbbaa$1111, então a saída = aaabbbaa$1111#aaab.
Usar quantas fitas achar necessário.

2 Fitas:

<img src="/Imagens/Ativ122fitas.png">

3 Fitas:

<img src="/Imagens/Ativ123fitas.png">

13 - Construa uma máquina de touring que trabalha sobre cadeias do tipo {a, b}* e conte quantas letras a's e b's aparecem nessa cadeia. O número deverá estar em base unária. Por exemplo: se entrada = aaabbbaa, então saída = aaabbbaa$11111$111.
Usar quantas fitas achar necessário.

<img src="/Imagens/Ativ132fitas.png">
