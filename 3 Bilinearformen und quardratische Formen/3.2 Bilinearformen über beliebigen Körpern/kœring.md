
TARGET DECK
Lineare Algebra II

[kœri]ing
--
![[Pasted image 20240703084302.png]]
## Definition
***
Dt. Schönfinkeln.
Bilinearformen sind keine lineare Abbildungen und deshalb können wir es nicht so epic mit den ganzen Tools aus der Linearen Algebra untersuchen. Wenn wir aber eine Variable sozusagen "festhalten", dann erhalten wir eine Abbildung, die einfacher handzuhaben ist.
Also
$f:X\times Y\rightarrow Z$. Wenn wir z.B. $y\in Y$ festhalten, erhalten wir die Funktion $f(\cdot,y):X\rightarrow Z$. Man schreibt auch:
$f^\vee Y\rightarrow Z^X, y\mapsto f(\cdot,y)$.
## Bilinearformen dann
***
Es sei V ein Vektorraum über einem Körper $\Bbb K$. 
Wie Defintion 3.1.1 eingeführt bezeichnen wir den Dualraum von V mit V ∗ := HomK(V,K). 
1. Es sei $β : V ×V → \Bbb K$ eine Bilinearform auf $V$. Dann ist für jeden Vektor $w ∈ V$ die Abbildung $β(·,w) : V → \Bbb K, v \mapsto β(v,w)$ linear, d.h. $β(·,w) ∈ V ^∗$ . 
2. Es sei $β : V ×V → \Bbb K$ eine Bilinearform auf $V$. Dann ist $β^ ∨ : V → V ^∗ , w \mapsto β(·,w)$ linear. Jede Bilinearform auf $V$ lässt sich also natürlich auf eine lineare Abbildung von $V$ nach $V^ ∗$ abbilden. 
3. Die Abbildung, die eine Bilinearform $β$ auf $β ^∨$ abbildet, ist ein Isomorphismus von $\Bbb K$-Vektorräumen: $Bil(V,\Bbb K) → Hom(V,V^ ∗ ), β \mapsto β ^∨$ .
## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt