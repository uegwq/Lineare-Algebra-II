
TARGET DECK
Lineare Algebra II

Kreuzprodukt bzw. Vektorprodukt
--
## Definition
***
Es ist im allgemeinen zwischen zwei Vektoren kein Produkt definiert, aber es gibt im $\Bbb R^3$ zwei solcher Produkte, die eine wichtige Rolle spielen. Das ist zuerst einmal das Kreuzprodukt: $$\times:\Bbb R^3\times \Bbb R^3\rightarrow \Bbb R^3$$ und das Skalarprodukt: $$<\cdot,\cdot>:\Bbb R^3\times \Bbb R^3\rightarrow \Bbb R, <(x_1,x_2,x_3),(y_1,y_2,y_3)\mapsto x_1y_1+x_2y_2+x_3y_3$$, welches zwei Vektoren auf einen Skalar abbildet.
## Defininierende Eigenschaften des Skalarproduktes:
***
Damit ein Skalarprodukt ein Skalarprodukt ist, muss es die folgenden Eigenschaften erfüllen:
1. Die Abbildung $<.,.>$ ist linear in der ersten komponente, also du kannst summen in der 1. komponente usw rausziehen
2. Die Abbildung ist konjugiert Symetrisch, d.h. $\bar{<v,w>}=<w,v>$
3. Die Abbildung ist positiv definit, also $<v,v>\ge 0$.
## Eigenschaften
***
Das Kreuzprodukt von Zwei Vektoren aus $\Bbb R^3$ ist wieder ein Vektor aus $\Bbb R^3$, welcher Senkreicht auf den beiden Ursprünglichen Vektoren steht. Für seine Länge gilt:
$||v\times w||=||v||||w||\sin(\angle(v,w))$. Für das Skalarprodukt gilt dann magischerweise:
$<v,w>=||v||||w||\cos(\angle(v,w))$. Daraus folgt, dass zwei Vektoren Orthogonal sind, wenn ihr Skalarprodukt null ist.
Zudem folgt folgende Formel für das Skalarprodukt eines Vektors mit sich selbst:
$<v,v>=||v||||v||\cos(\angle(v,v))=||v||||v||*1=||v||^2$.
Das Skalarprodukt $\Bbb R^3$ ist bilinear, aber nicht alternierend.
## Siehe auch
***
* [[Skalarprodukt]]