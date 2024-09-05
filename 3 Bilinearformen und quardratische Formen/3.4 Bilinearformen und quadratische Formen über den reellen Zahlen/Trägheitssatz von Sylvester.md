
TARGET DECK
Lineare Algebra II

Trägheitssatz von Sylvester
--
## Definition
***
Es sei $n\in\Bbb N$ und $V$ ein $n$-dimensionaler reeller Vektorraum. Da sei $\beta:V\times V\rightarrow\Bbb R$ eine symmetrische Bilinearform.
- Dann können wir $V$ zerlegen in $V=V_+\oplus V_-\oplus V_0$,
  sodass $\beta|_{V_+\times V_+}$ positiv definit, $\beta|_{V_-\times V_-}$ negativ definit und $\beta|_{V_0\times V_0}$ die Nullabbildung ist und Vektoren aus verschiedenen der drei direkten Summanden stammen, orthogonal bezüglich $\beta$ sind, d.h. $\beta(u,v)=0$.
## Folgerungen
***
1. Das Tripel $(\dim(V_+), \dim(V_-), \dim(V_0)) \in \mathbb{N}_0^3$ hängt nicht von der Zerlegung ab und ist eindeutig bestimmt. Die Zahl $\dim(V_-)$ wird die **Signatur** von $\beta$ genannt. Wenn die Signatur von $\beta$ und der Rang $\dim(V_+) + \dim(V_-)$ bekannt sind, ist die Bilinearform bis auf Basiswechsel eindeutig bestimmt.
2. Es gibt eine geordnete Basis $B$ von $V$, sodass $FM_{B}(\beta)$ eine Diagonalmatrix ist, die nur die Zahlen $1$, $-1$ und $0$ auf der Diagonale hat. Die Signatur entspricht der Anzahl der $-1$ auf der Diagonale. Der Rang ist die Summe der Anzahl aller $1$ und aller $-1$.
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt