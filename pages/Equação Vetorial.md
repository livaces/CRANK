public:: true

- Created: [[May 22nd, 2026]] 
  Updated:
  Subject: [[Vetores no R2 e R3]] 
  Tags:
-
- ## Vetor Diretor
  Vetor diretor é **qualquer** vetor **não nulo** que dá a **direção** de uma reta $r$.
- ## Equação vetorial
  #+BEGIN_CENTER
  $\overbrace{(x,y,z)}^{\text{destino}}=\overbrace{(a,b,c)}^{\text{ponto de partida}}+t\overbrace{(d,e,f)}^{\text{vetor diretor}}$
    
  ou 
   
  $X=x_0+t\times\overrightarrow{v}$
   
  #+END_CENTER
  OBS.: É válida se $x_0$ e $\overrightarrow{v}$ forem vetores em $R^{n}$ e se $\overrightarrow{v}$ for não nulo.
- ## Equações Paramétricas
  As incógnitas *x*, *y* e *z* estão em função do parâmetro **t**.
  $$(x,y,z)=(a,b,c)+(t\times{d},t\times{e},t\times{f})\implies(x,y,z)=(a+td,b+te,c+tf)\implies\begin{cases}
  x=a+td \\
  y=b+te \\
  z=c+tf
  \end{cases}$$
  #+BEGIN_NOTE
  *Exemplo: A reta* $r$ *passa pelos pontos* $A=(-4, -2, 1)$ *e* $B=(2,5,0)$.
  $$\overrightarrow{AB}=B-A=(2-(-4),5-(-2),0-1)=(6,7,-1)\implies\begin{cases}
  x=-4+t6 \\
  y=-2+t7 \\
  z=1+t(-1)
  \end{cases}\implies\begin{cases}
  x=-4+6t \\
  y=-2+7t \\
  z=1-t
  \end{cases}$$
  #+END_NOTE
- ## Equação Simétrica
  A forma dimétrica só é válida quando $d\not=0$, $e\not=0$ e $f\not=0$.
  $$\begin{cases}
  x=a+td \\
  y=b+te \\
  z=c+tf
  \end{cases}\implies{t}=\frac{x-a}{d},t=\frac{y-b}{e},t=\frac{z-c}{f}\implies{t}=t=t\implies\frac{x-a}{d}=\frac{y-b}{e}=\frac{z-c}{f}$$