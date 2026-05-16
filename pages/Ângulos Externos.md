public:: true

- Created: [[May 16th, 2026]] 
  Updated:
  Subject: [[Geometria Euclidiana]]
-
- ## Definição
  Um ângulo externo de um triângulo é o ângulo suplementar de um ângulo do triângulo.
  O ângulo $\widehat{DCA}$ é um dos ângulos externos do triângulo $ABC$. Um triângulo tem seis ângulos externos.
  ![image.png](../assets/image_1778957301154_0.png)
- ## 1. Teorema
  #+BEGIN_QUOTE
  O ângulo externo de um triângulo é maior do que cada um dos ângulos do triângulo que não lhe são adjacentes.
  #+END_QUOTE
  **Demonstração**: seja um triângulo $ABC$ e o ângulo externo $\widehat{ACD}$. Mostre que o ângulo $\widehat{ACD}$ é maior do que o ângulo $\widehat{BAC}$ sendo $E$ o ponto médio do segmento $[AC]$, trançando a semirreta $[BE)$, e o ponto $F$ desta semirreta tal que $E$ seja também o ponto médio do segmento $[BF]$.
  ![image.png](../assets/image_1778958405773_0.png)
	- Comparando os triângulos $ABE$ e $CEF$ temos que os ângulos $\widehat{AEB}$ e $\widehat{CEF}$ são opostos pelo vértice e são, portanto, iguais. Temos também, por construção, $AE=EC$ e $BE=EF$.
	  
	  Pelo caso *LAL* os triângulos $AEB$ e $CEF$ são congruentes e, portanto, $\widehat{BAC}=\widehat{ACF}$. O ponto $F$ está no interior do ângulo $\widehat{ACD}$[^1]. A semirreta $[BE)$ é interior ao ângulo $ABC$, pois $E$ está no segmento $AC$ o que significa que o ponto $F$ está do mesmo lado do que $A$ em relação à reta $(BC)$.
	  
	  Os pontos $B$ e $F$ são de lado oposto em relação à reta $(AC)$. Os pontos $B$ e $D$ são também de lado oposto em relação à reta $(AC)$. Logo o ponto $F$ é do mesmo lado do que $D$ em relação à reta $(BD)$, a semirreta $[AF)$ é interior ao ângulo $\widehat{ACD}$.
	  
	  Como o ângulo $\widehat{ACF}$ está dentro do ângulo $\widehat{ACD}$, o ângulo $\widehat{ACD}$ é maior do que o ângulo $\widehat{ACF}$ e, portanto, o ângulo $\widehat{ACD}$ é maior do que o ângulo $\widehat{BAC}$.
	  ![image.png](../assets/image_1778961402027_0.png)
- ## 2. Teorema
  #+BEGIN_QUOTE
  Para todo triângulo, a soma de dois ângulos do triângulo é menor do que dois ângulos retos.
  #+END_QUOTE
  **Demonstração**: seja um triângulo $ABC$. Vamos mostrar que a soma do ângulo $\widehat{BAC}$ e do ângulo $\widehat{BCA}$ é menor do que dois ângulos retos.
- Pelo teorema precedente,