
TARGET DECK
Lineare Algebra II

Wichtige Eigenschaften von Vektoren in R
--
## Winkel zwischen senkrechten Vektoren
***
Wenn der Winkel zwischen zwei Vektoren genau $π/2 = 90°$ beträgt, sind die beiden Vektoren orthogonal: $$∀v,w ∈ \Bbb R^3 \setminus\{0\} : v ⊥ w : \iff \angle (v,w) = π/2.$$
## Über das Kreuzprodukt
Das Kreuzprodukt $v × w$ von $v \not= 0$ und $w \not = 0$ steht senkrecht auf $v$ und $w$ und für die Norm gilt:
	$||v ×w|| = ||v|| ||w||sin(\angle (v,w)).$ 
Für das Skalarprodukt $〈v,w〉$ gilt:
	$〈v,w〉 = ||v|| ||w||cos(\angle (v,w)).$
Da die Normen $||v||$ und $||w||$ für Vektoren $v, w \neq 0$ immer positiv sind, richtet sich das Vorzeichen von $\langle v, w \rangle$ nur nach dem Kosinus des eingeschlossenen Winkels, d.h. 
$\forall v,w \in \mathbb{R}^3 \setminus \{0\} : \langle v, w \rangle > 0 \iff \cos(\angle(v, w)) > 0 \iff \angle(v, w) < \frac{\pi}{2}$$\forall v,w \in \mathbb{R}^3 \setminus \{0\} : \langle v, w \rangle = 0 \iff \cos(\angle(v, w)) = 0 \iff \angle(v, w) = \frac{\pi}{2}$
$\forall v,w \in \mathbb{R}^3 \setminus \{0\} : \langle v, w \rangle < 0 \iff \cos(\angle(v, w)) < 0 \iff \angle(v, w) > \frac{\pi}{2}$
Es gilt also: Zwei Vektoren $v, w \in \mathbb{R}^3 \setminus \{0\}$ sind genau dann orthogonal, wenn ihr Skalarprodukt $0$ ist:
$v \perp w \iff \langle v, w \rangle = 0.$
Außerdem folgt aus der obigen Formel für das Skalarprodukt folgende Formel für das Skalarprodukt eines Vektors mit sich selbst: $〈v,v〉 = ||v|| ||v||cos(\angle (v,v)) = ||v||||v|| =||v||^ 2$ .

## Siehe auch
***
* Hier immer spezifischer Werden. Z.b. Abbildung linkt zu arten von Abbildungen und nicht umgekehrt