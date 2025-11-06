## 4 station spatiale

Une station spatiale de masse M est reliée à un contrepoids de masse M/4 par un câble tendu de 200 mètres de longueur et de masse négligeable. Le tout est en rotation autour du centre de masse. Quelle doit être la vitesse angulaire de rotation pour que les occupants de la station spatiale ressentent une "gravité artificielle" égale à la gravité terrestre ?

Masse station spatiale: $M$
Contrepoids station spatiale: $M/4$
$d=200$ m

Si on place la station spatiale et son contrepoids sur un même axe et que la station spatiale est à $x=0$:
$$
x_{cm}=\frac{\sum x_im_i}{\sum m_i}=\frac{0+200(M/4)}{M+M/4}=\frac{200M}{4(1.25M)}
=40\\
\bold a_r=-\omega^2R\bold e_r	\\
\omega=\sqrt{\frac{-\bold a_r}{R\bold e_r}}
=\sqrt{\frac{9.81 \bold e_r}{R\bold e_r}}
=\sqrt{\frac{9.81}{R}}	\\
R_M=40	\\
R_{M/4}=200-40=160	\\
\omega_M=\sqrt{\frac{9.81}{40}}=0.4952	\\
$$
La station spatiale doit tourner à $0.4952$ rad/s

## 3 Mouvement linéaire

Vous êtes dans une cabine d'ascenseur. Est-il possible que votre poids soit négatif ? Si oui, comment ?

Il est impossible que le poids soit négatif puisque le poids est un synonyme pour force gravitationnelle. Cette dernière est déterminée par la formule suivante: $F_g=\frac{MmG}{R^2}$ où toutes les variables sont strictement positives. Il est donc impossible que le poids soit négatif. Cependant la poids apparent peut être négatif si la cabine d'ascenseur accélère vers le bas à un taux supérieur à $9.81$ N/kg.
$$
\bold F_{app}=\sum \bold F=\bold F_g+\bold F=m\bold g+m\bold a=m(g-a)\bold e
$$

## 2 Mouvement de rotation

Deux masses $m_1=15$ et $m_2=10$ kg sont reliées par un câble tendu de 16m de longueur. Dans le référentiel du centre de masse, tout le système est en rotation à 2 tour toutes les 10 secondes, autour d'un axe perpendiculaire au câble. Calculez la tension dans le câble.
$$
\omega=\frac{2}{10}2\pi=\frac{2\pi}{5}	\\
\\
x_{cm}=\frac{\sum x_im_i}{\sum m_i}=\frac{0+(16)(10)}{15+10}=\frac{160}{25}=6.4
$$
pour $m_1$:
$$
\bold F_{cent}=m_1\omega^2R_1\hat{\bold e}_r
=(15)(2\pi/5)^2(6.4)\hat{\bold e}_r
=15.36\pi^2\hat{\bold e}_r
$$
pour $m_2$:
$$
\bold F_{cent}=m_2\omega^2R_2\hat{\bold e}_r
=(10)(2\pi/5)^2(16-6.4)\hat{\bold e}_r
=15.36\pi^2\hat{\bold e}_r
$$
Dans ce cas, $\bold T=\bold F_{cor}=15.36\pi^2\hat{\bold e}_r$

