- Created: [[14-05-2026]] 
  Updated:
  Subject: [[Geometria Euclidiana]]
-
- ## 1.2 Teorema: as mediatrizes de um triângulo são concorrentes + círculo circunscrito.
  heading:: 2
  #+BEGIN_QUOTE
  As mediatrizes se encontram em um ponto chamado **circuncentro**, por ser o centro do círculo que **passa** pelos **3 vértices** dos triângulos.
  #+END_QUOTE
  
  **Demonstração**: Seja $D$ o ponto médio do segmento $[BC]$, $E$ o ponto médio do segmento $[AC]$ e ambas mediatrizes concorrem no ponto O. Sendo $F$ o ponto médio do segmento $[AB]$, a terceira mediatriz concorre no ponto O.
  ![image.png](../assets/image_1778782888648_0.png)
	-
	- Sejam os triângulos $BOD$ e $COD$ congruentes pelo caso *LAL*[^1], logo $BO=OC$. Também há os triângulos $AOE$ e $COE$ congruentes pelo caso *LAL*[^2], logo $AO=OC$. Como temos $BO=OC$ e $OP=OC$, então, também temos: $OP=OC=BO$.
	  
	  Sejam os triângulos $AFO$ e $BFO$, pelo caso *LLL*[^3], ambos são congruentes, logo ambos ângulos são iguais $\widehat{AFO}=\widehat{BFO}$. Entretanto, tais ângulos são suplementares, $\widehat{AFO}=\widehat{BFO}=180$, então os ângulos $\widehat{AFO}$ e $\widehat{BFO}$ são retos, logo o segmento $FO$ é parte da mediatriz do segmento $[AB]$, ou seja, **as mediatrizes de um triângulo concorrem num mesmo ponto**.
	  
	  Como a distâncias dos vértices do triângulo são iguais as distâncias do circuncentro então temos que o circuncentro é o centro da circunferência circunscrita ao triangulo $ABC$.
	  ![image.png](../assets/image_1778781610881_0.png){:height 628, :width 1080}
- [^1]: **L** ($BD=DC$), **A** ($90^{o}$), **L** ($OD=OD$)
  [^2]: **L** ($AE=EC$), **A** ($90^{o}$), **L** ($OE=OE$)
  [^3]: **L** ($AF=FB$), **L** ($AO=BO$), **L** ($FO=FO$)