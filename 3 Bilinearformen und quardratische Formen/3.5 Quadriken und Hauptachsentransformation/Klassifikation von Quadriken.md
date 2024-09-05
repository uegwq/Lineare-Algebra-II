
TARGET DECK
Lineare Algebra II

Klassifikation von Quadriken
--
## affiner Fall
***
Sei $\Bbb K$ ein Körper mit $\text{char}(\Bbb K) \neq 2$ und $Q \subseteq \Bbb K^n$ eine Quadrik. Dann gibt es immer einen affinen Automorphismus $\Psi : \Bbb K^n \to \Bbb K^n$, $x \mapsto Sx + v_0$ mit $S \in \text{GL}(n, \Bbb K)$ und $v_0 \in \Bbb K^n$, eine Zahl $m \in \{1, \dots, n\}$ und Skalare $\alpha_1, \dots, \alpha_m \neq 0$, sodass genau einer der drei folgenden Fälle zutrifft:

1. $Q$ ist eine **kegelartige Quadrik** (oder auch **kegelige Quadrik**), d.h.
   $\Psi(Q) = \left\{ \begin{pmatrix} u_1 \\ \vdots \\ u_n \end{pmatrix} \in \Bbb K^n \ \middle|\ \sum_{j=1}^{m} \alpha_j u_j^2 = 0 \right\}$
   
2. $Q$ ist eine **Mittelpunktsquadrik**, d.h.
   $\Psi(Q) = \left\{ \begin{pmatrix} u_1 \\ \vdots \\ u_n \end{pmatrix} \in \Bbb K^n \ \middle|\ \sum_{j=1}^{m} \alpha_j u_j^2 = 1 \right\}$

3. $Q$ ist eine **parabolische Quadrik**, d.h. $m \leq n-1$ und
   $\Psi(Q) = \left\{ \begin{pmatrix} u_1 \\ \vdots \\ u_n \end{pmatrix} \in \Bbb K^n \ \middle|\ \sum_{j=1}^{m} \alpha_j u_j^2 + 2u_{m+1} = 0 \right\}$
Die Zahl $m$ entspricht hier dem Rang der zur Quadrik gehörenden symmetrischen Bilinearform.
## isometrischer Fall; Hauptachsentransformation
***
Es sei **$Q \subseteq \Bbb R^n$** eine Quadrik. Dann gibt es immer einen **isometrischen** affinen Automorphismus $\Psi : \Bbb R^n \to \Bbb R^n$, $x \mapsto Sx + v_0$ mit $S \in S(n)$ und $v_0 \in \Bbb R^n$, eine Zahl $m \in \{1, \dots, n\}$ und Skalare $\alpha_1, \dots, \alpha_m \neq 0$, sodass genau einer der drei folgenden Fälle zutrifft:

1. $Q$ ist eine **kegelartige Quadrik** (oder auch **kegelige Quadrik**), d.h.
   $\Psi(Q) = \left\{ \begin{pmatrix} u_1 \\ \vdots \\ u_n \end{pmatrix} \in \Bbb R^n \ \middle|\ \sum_{j=1}^{m} \alpha_j u_j^2 = 0 \right\}$
   
2. $Q$ ist eine **Mittelpunktsquadrik**, d.h.
   $\Psi(Q) = \left\{ \begin{pmatrix} u_1 \\ \vdots \\ u_n \end{pmatrix} \in \Bbb R^n \ \middle|\ \sum_{j=1}^{m} \alpha_j u_j^2 = 1 \right\}$

3. $Q$ ist eine **parabolische Quadrik**, d.h. $m \leq n-1$ und
   $\Psi(Q) = \left\{ \begin{pmatrix} u_1 \\ \vdots \\ u_n \end{pmatrix} \in \Bbb R^n \ \middle|\ \sum_{j=1}^{m} \alpha_j u_j^2 + 2u_{m+1} = 0 \right\}$

Die Zahl $m$ entspricht hier dem Rang der zur Quadrik gehörenden symmetrischen Bilinearform.
Das Verfahren, eine Quadrik durch eine affine Isometrie $\Psi$ in eine dieser Formen zu bringen, nennt man auch Hauptachsentransformation.
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt