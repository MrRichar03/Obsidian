Ejercicios del parcial uwu

L = $\large{a^n (bc^n + cb^n) }$ para n > 0
L = $\large{ a^n bc^n + a^ncb^n }$ para n > 0

(q0, a, z0) = {(q1, az0)}

(q1, a, a) = {(q1, aaz0)}

(q1, b, a) = {(q2, az0)}

(q2, c, a) = {(q2, z0)}

(q2, a, z0) = {(q1, az0)}

(q1, c, a) = {(q3, az0)}

(q3, b, a) = {(q3, zo)}

(q3, a, z0) = {(q1, az0)}

(q2, $\large{\lambda}$, z0) = {(q0, z0)}

(q3, $\large{\lambda}$, z0) = {(q0, z0)}


Diseñar una GIC para el lenguaje del ejercicio anterior:

![[ef7590b4-3e97-456e-a82b-4e60add12b3c.png]]

S -> aAc | aBb
A -> aAc | b
B -> aBb | c

3 diseñar un árbol de derivación para el caso n = 2
aabcc

S -> aAc -> aaAcc -> aabcc



Hacer una G.r para el lenguaje del primer ejercicio

L = $\large{ a^n bc^n + a^ncb^n }$ para n > 0

S -> aA
A -> aA | bC | cB
B -> bB | bA | b
C -> cB | cA | c




