
TARGET DECK
Lineare Algebra II

Gram-Schmidt
--
## Definition
***
Dies ist ein Algorithmus um eine Basis zu einer Orthogonalbasis zu machen. Das ist eigentlich nur eine Abgewandelte Version des Gauß-Verfahren (Its all just Gauß).

Gegeben seien $\{v_1,\dots,v_n\}$.
$$w_1:=v_1$$
$$w_j:=v_j-\sum^{j-1}_{i=1}\frac{<v_j,w_i>}{<w_i,w_i>}w_i$$
DANN GILT: $\{w_1,...,w_n\}$ ist ein Orthogonalsystem
$LH(w_1,...,w_m)=LH(v_1,...,v_m)$.
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt