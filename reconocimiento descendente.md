
S -> aBCd
B -> CB|b
C -> cc|$\large{\lambda}$ 

Primeros:

P(S) = {a}
P(B) = {b, c, $\large{\lambda}$}
P(C) = {c, $\large{\lambda}$} 

Siguientes:

S(S) = {$}
S(B) = {c, a}
S(C) = {d, b, c}

otro ejemplo uwu

S -> BC
B -> $\large{\lambda}$| m
C -> $\large{\lambda}$| s

P(S) = {m, $\large{\lambda}$}
P(B) = {m, $\large{\lambda}$}
P(C) = {s, $\large{\lambda}$} 

S(S) = {$}
S(B) = {s, m}
S(C) = {$}

otro ejemplo owo

E -> TE'
E' -> +TE|-TE|$\large{\lambda}$ 
T -> FT'
T' -> $*FT|/FT|\large{\lambda}$ 
F -> (E)|num|id

Primeros:

P(E) = {(, num, id)
P(E') = {+, -, $\large{\lambda}$)
P(T) = {(, num, id}
P(T') = {$*, /, \large{\lambda}$}
P(F) = {(, num, id}

Siguientes:

S(E) = {$, )}
S(E') = {$, )}
S(T) = {+, -, $, )}
S(T') = {+, -, $, )}
S(F) = {$*$, /, +, -, $, )}

otro ejemplo mufu

E -> T+E|T
T -> F$*$T|F
F -> a|b|(E)

P(E) = {a, b, (}
P(T) = {a, b, (}
P(F) = {a, b, (}

S(E) = {$, )}
S(T) = {+, $, )}
S(F) = {$*$, +, $, )}

ultimo ejemplo moh

E -> T+E|T
T -> F$*$T|F
F -> (E)|id|num|$\large{\lambda}$ 

P(E) = {(, id, num, $\large{\lambda}$}
P(T) = {(, id, num, $\large{\lambda}$}
P(F) = {(, id, num, $\large{\lambda}$}

S(E) = {$, )}
S(T) = {+, $, )}
S(F) = {$*$, +, $, )}