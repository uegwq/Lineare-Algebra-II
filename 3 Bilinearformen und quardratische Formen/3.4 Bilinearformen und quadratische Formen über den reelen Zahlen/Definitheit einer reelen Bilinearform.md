
TARGET DECK
Lineare Algebra II

Definitheit einer reelen Bilinearform
--
## Definition
***
Es sei $V$ ein reeler Vektorraum und $\beta:V\times V\rightarrow\Bbb R$ eine symmetrische Bilinearform mit dazugehöroger quadratischer Form $q_\beta:V\rightarrow\Bbb R$. Dann nennen wir $\beta$ (und auch $q_\beta$):
- positiv definit, falls $\forall v\in V\setminus\{0\}:q_\beta>0$
- negativ definit, falls $\forall v\in V\setminus\{0\}:q_\beta<0$
- positiv semidefinit, falls $\forall v\in V:q_\beta\ge0$
- negativ semidefinit, falls $\forall v\in V:q_\beta\le0$
- infefinit, falls es Vektoren gibt die $>0$ und $<0$ auf der quadratischen Form sind.
## Bestimmung der Definitheit
***
Es sei $n ∈ \Bbb N$. Eine symmetrische Matrix $A ∈ \Bbb R^ {n×n}$ heiße 
- positiv definit, falls $∀x ∈ \Bbb R^ n \setminus\{0\} : x ^T Ax > 0$ 
- negativ  definit, falls $∀x ∈ \Bbb R^ n \setminus\{0\} : x ^T Ax < 0$ 
- positiv semidefinit, falls $∀x ∈ \Bbb R^ n : x ^T Ax ≥ 0$ 
- negativ semidefinit, falls $∀x ∈ \Bbb R^ n : x ^T Ax ≤ 0$ 
- indefinit, falls es Vektoren $x, y ∈ \Bbb R^ n$ gibt mit $x ^T Ax < 0$ und $y ^T A y > 0$.
## Erstes Kriterium
***
Sei $V$ ein $n$-dimensionaler reeller Vektorraum und $\beta : V \times V \to \mathbb{R}$ eine symmetrische Bilinearform. Es sei weiterhin $B$ eine Orthogonalbasis (diese gibt es immer und für diese Ist $FM_B$ in diagonalform) für $\beta$. Dann gilt:

- **positiv definit**, falls alle Diagonaleinträge von $FM_{B}(\beta)$ größer als $0$ sind.
- **negativ definit**, falls alle Diagonaleinträge von $FM_{B}(\beta)$ kleiner als $0$ sind.
- **positiv semidefinit**, falls alle Diagonaleinträge von $FM_{B}(\beta)$ größer als oder gleich $0$ sind.
- **negativ semidefinit**, falls alle Diagonaleinträge von $FM_{B}(\beta)$ kleiner als oder gleich $0$ sind.
- **indefinit**, falls es sowohl positive als auch negative Zahlen auf der Diagonalen gibt.
Man bringt die Matrix mit Gauß-Umformungen also in diagonalform und schaut sich die Vorzeichen an!
## Kriterium über Determinante (NUR FÜR POSITIVE DEFINITHEIT)
***
1. Die Matrix einer Positiv definiten Matrix ist immer positiv.
Es sei $A\in\Bbb R^{n\times n}$ eine symmetrsiche $(n\times n)$-Matrix mit $n\ge2$ und $B\in\Bbb R^{(n-1)\times(n-1)}$ die Matrix die man erhält, wenn man von $A$ die letzte Zeile und Spalte streicht,
Dann ist äquivalent:
- Die Matrix $A$ ist positiv definit
- Die Matrix $B$ ist positiv definit und $det(A)>0$
## Hurwitz-Kriterium
***
Es sei $A \in \mathbb{R}^{n \times n}$ eine symmetrische Matrix und für jedes $k \in \{1, \dots, n\}$ sei $F_k \in \mathbb{R}^{k \times k}$ die Matrix, die aus den obersten $k$ Zeilen und den ersten $k$ Spalten besteht.
- Die Matrix $A$ ist genau dann **positiv definit**, wenn für alle $k \in \{1, \dots, n\}$ gilt: $\det(F_k) > 0$.
- Die Matrix $A$ ist genau dann **negativ definit**, wenn für alle $k \in \{1, \dots, n\}$ gilt: $(-1)^k \cdot \det(F_k) > 0$.
- Falls $\det(A) \neq 0$ ist und $A$ weder positiv noch negativ definit ist, dann ist $A$ **indefinit**.
## Definitheit mit Eigenwerten
***
Es sei $A \in \mathbb{R}^{n \times n}$ eine symmetrische Matrix. Dann gilt:
- **positiv definit**, falls alle Eigenwerte von $A$ größer als $0$ sind.
- **negativ definit**, falls alle Eigenwerte von $A$ kleiner als $0$ sind.
- **positiv semidefinit**, falls alle Eigenwerte von $A$ größer als oder gleich $0$ sind.
- **negativ semidefinit**, falls alle Eigenwerte von $A$ kleiner als oder gleich $0$ sind.
- **indefinit**, falls $A$ sowohl positive als auch negative Eigenwerte besitzt.
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt