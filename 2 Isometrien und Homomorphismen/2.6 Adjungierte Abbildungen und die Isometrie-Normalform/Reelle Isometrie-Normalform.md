
TARGET DECK
Lineare Algebra II

Reelle Isometrie-Normalform
--
## Definition
***
![[Pasted image 20240614081540.png]]
## Random Eigenschaften die dir bei Reellen Isometrie-Normalformen helfen:
***
1. Bei Basiswechel ist die Spur invariant
2. Bei Basiswechsel sind die Eigenwerte Invariant
3. Die Winkel in der komplexen Isometrie-Normalform sind die selben wie in der Reellen
4. Ist $A\in\Bbb R^{n\times n}$, und ist $\lambda\in\Bbb C$ ein EW von A, so ist auch $\bar\lambda$ ein EV von A.
## Wie bestimmt man die Reelle Isometrie-Normalform?
***
Nie vergessen: alle Drehkästchen müssen einen Winkel zwischen $0$ und $\pi$ haben!
### 1. Spurtrick:
Man beobachtet, dass die Spur bei Basiswechel erhalten bleibt (Lineare Algebra 1 5.5). Also können wir bei kleineren Matrizen manchmal die Spur unserer Matrix damit vergleichen, wie sie in der Isometrie-Normalform aussehen kann und daraus Schlüsse ziehen.
#### Beispiel:
Was ist die reefle Isometrienormalform von $\varphi: V\rightarrow V,\varphi\begin{pmatrix} 1 \\ 0 \end{pmatrix}=\begin{pmatrix} 0 \\ -1 \end{pmatrix}, \varphi\begin{pmatrix} 0 \\ 1\end{pmatrix}=\begin{pmatrix} 1 \\ 0 \end{pmatrix}$.
$\implies M_{E,E}(\varphi)=\begin{pmatrix} 0 & 1 \\ -1 & 0\end{pmatrix}\implies  Spur(\varphi)=0$.
$\implies$ Die Spur der Isometrienormalform muss auch $0$ sein, also ist sie $\begin{pmatrix} 1 & 0 \\ 0 & -1 \end{pmatrix}$ oder $D_\alpha$ mit $2cos(\alpha)=0$.
Da $\begin{pmatrix} 1 & 0 \\ 0 & -1 \end{pmatrix}$ keine reellen Eigenwerte hat, kann $\begin{pmatrix} 1 & 0 \\ 0 & -1 \end{pmatrix}$ nicht die Isometrienormalform sein.
### 2. Trick mit der Transponierten
Es sei Matrix $A\in\Bbb R^{n\times n}$
- $A$ hat EW 1 $\iff$ $A+A^T$ hat EW 2
- $A$ hat EW -1 $\iff$ $A+A^T$ hat EW -2
- $A$ hat das Paar $e^{i\alpha}$ und $e^{-i\alpha}$ als EW $\iff$ $A+A^T$ hat den doppelten EW $2cos(\alpha)$.
#### Beispiel:
$A=\begin{pmatrix} 0&0&1&0 \\ 0&0&0&1 \\ -1&0&0&0 \\ 0&-1&0&0 \end{pmatrix}, \varphi:\Bbb R^4\rightarrow\Bbb R^4,\varphi(x)=Ax$- Welche Isometrienormalform hat $\varphi$?
$B:=A+A^T=0,p_B(X)=\det\begin{pmatrix} X&0&0&0 \\ 0&X&0&0 \\ 0&0&X&0 \\ 0&0&0&X \end{pmatrix}=X^4\implies B$ hat nur EW 0.
**Transpositionstrick**: INF von $\varphi$ ist $\begin{pmatrix} D_\alpha&\\&D_\alpha \end{pmatrix}$ mit $2\cos(\alpha)=0$, also $\alpha=\frac \pi 2$
## Wie findet man eine passende Orthonormalbasis B?
***
Gegeben $A\in\Bbb R^{n\times n}$ mit $\varphi:\Bbb R^n\rightarrow\Bbb R^n,\varphi(x)=Ax$.
1. Bestimme alle EW von $A$ (z.b. mit dem Transponiertrick)
2. Falls $A$ die EW $-1$ oder $1$ hat, bestimme Orthonormalbasen $B_1$ von $E_1(A)$ und $B_{-1}$ von $E_{-1}(A)$.
3. Für jede EW-paar $\underbrace{e^{i\alpha}}_{=\lambda_j},\underbrace{e^{-i\alpha}}_{=\bar\lambda_j}$ mit $0<\alpha_k<\pi$:
	1. Bestimme Orthonormalbasis $(v_1,\dots,v_t)$ von $E_{\lambda_j}(\varphi_\Bbb C)$. (! Auch komplexe Vektoren erlaubt!)
	2. Setze $a_k:=Re(v_k)$ und $b_k:=Im(v_K)$
	3. Setze $\widetilde{a_k}:=\frac {a_k}{||a_k||}$  und $\widetilde{b_k}:=\frac {b_k}{||b_k||}$
	4. $B_{\lambda_j}:=(\widetilde{a_1},\widetilde{b_1},\dots,\widetilde{a_t}\widetilde{b_t})$ ist ONB von $E_{\lambda_j}(\varphi_\Bbb C)+E_{\bar\lambda_j}(\varphi_\Bbb C)$
	5. $\implies B:=B_1\cup B_{-1}\cup B_{\lambda_1}\cup\dots\cup B_{\lambda_m}$.   
### Beispiel:
$\textbf{Beispiel:}$
$A = \begin{pmatrix} 0&0 & 1 & 0 \\ 0&0&0&1 \\ 0&-1& 0& 0\\0&-1&0&0\end{pmatrix}$, hat EQ $\lambda_1 = \underbrace{e^{i \frac{\pi}{2}}}_{=i}, \bar\lambda_1 = \underbrace{e^{-i \frac{\pi}{2}}}_{=i}$
$E_{\lambda_1}(A) = E_{i}(A) = \ker(A - i\Bbb 14) =^{[...]} LH \left(\begin{pmatrix} 0 \\ -i \\ 0 \\ 1 \end{pmatrix},\begin{pmatrix} -i \\ 0 \\ 1 \\ 0 \end{pmatrix}\right)$$v_1 = \frac{1}{\sqrt{2}} \begin{pmatrix} 0 \\ -i \\ 0 \\ 1 \end{pmatrix} , \; v_2 = \frac{1}{\sqrt{2}} \begin{pmatrix} -i \\ 0 \\ 1\\0 \end{pmatrix}$,bilden ONB von $E_{\lambda_i}(A)$ 
$a_1 = \text{Re}(v_1) = \frac{1}{\sqrt{2}} \begin{pmatrix} 0 \\ 0 \\ 0 \\ 1 \end{pmatrix}, \quad b_1 = \text{Im}(v_1) = \frac{1}{\sqrt{2}} \begin{pmatrix} 0 \\ -1 \\ 0 \\ 0 \end{pmatrix}$$a_2 = \text{Re}(v_2) = \frac{1}{\sqrt{2}} \begin{pmatrix} 0 \\ 0 \\ 1\\0 \end{pmatrix}, \quad b_2 = \text{Im}(v_2) = \frac{1}{\sqrt{2}} \begin{pmatrix} -1 \\ 0 \\ 0\\0 \end{pmatrix}$
$B = (\widetilde b_1,\widetilde a_1,\widetilde b_2,\widetilde a_2)$ ist gesuchte ONB von A $A \widetilde{b_1} = \begin{pmatrix} 0 \\ 0 \\ 0\\1 \end{pmatrix} =\widetilde{a_1}, \quad A \widetilde{b_2} = \begin{pmatrix} 0 \\ 0\\1 \\ 0 \end{pmatrix} \widetilde{a_2}$ 
$A \widetilde{a_1} = \begin{pmatrix} 0 \\ 1 \\ 0\\0 \end{pmatrix} =\widetilde{-b_1}, \quad A \widetilde{a_2} = \begin{pmatrix} 1 \\ 0\\0 \\ 0 \end{pmatrix} \widetilde{-b_2}$
$\implies M_{B,B}(A) = \begin{pmatrix} 0 & -1 & 0&0 \\ 1 & 0 & 0&0 \\ 0 & 0 & 0&-1\\0&0&1&0 \end{pmatrix}$. ist Isometrienormalform ✅ 
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt
