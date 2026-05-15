- [#A] Created: [[19-04-2026]] 
  Updated:
  Sources: <ins>Khan Academy</ins> 
  Subject: [[Vetores no R2 e R3]]
- ## Soma de vetores algebricamente
  heading:: 2
  + **Propriedades da adição:**
  I) *Comutativa*: $$\overrightarrow{a}+\overrightarrow{b}=\overrightarrow{b}+\overrightarrow{a}$$
  
  II) *Associativa*: $$(\overrightarrow{a}+\overrightarrow{b})+\overrightarrow{c}=\overrightarrow{a}+(\overrightarrow{b}+\overrightarrow{c})$$
  
  III) *Elemento neutro*: $$\overrightarrow{a}+\overrightarrow{0}=\overrightarrow{0}+\overrightarrow{a}=\overrightarrow{a}$$
  
  IV) *Elemento oposto*: $$\overrightarrow{a}+(-\overrightarrow{a})=\overrightarrow{a}-\overrightarrow{a}=\overrightarrow{0}$$
  
  Duas Formas de representar uma **soma de vetores**:
  $$\overrightarrow{a}+\overrightarrow{b}=(6, -2) + (-4, 4)\implies(6+(-4)),(-2)+4)\implies\overrightarrow{a}+\overrightarrow{b}=(4, 2)\newline\newline\text{ou}\newline\newline\overrightarrow{a}+\overrightarrow{b}=\begin{bmatrix} 6 \\ -2\end{bmatrix}+\begin{bmatrix} -4 \\ 4\end{bmatrix}\implies\begin{bmatrix} 6+(-4) \\ (-2)+4\end{bmatrix}\implies\overrightarrow{a}+\overrightarrow{b}=\begin{bmatrix} 4 \\ 2\end{bmatrix}$$
  
  + ==**Polar para retangular**==
  $$\overrightarrow{a}+\overrightarrow{b}=(a_x, a_y) + (b_x, b_y)\implies(x\times\cos{(\text{ângulo }a_x)}+(y\times\cos{(\text{ângulo }b_x})), (x\times\sin{(\text{ângulo }a_y)}+(y\times\sin{(\text{ângulo }b_y}))$$
- ## Multiplicação Vetorial
  heading:: 2
  #+BEGIN_QUOTE
  **Propriedades da Multiplicação**
  
  *I. Comutativa*: $$\overrightarrow{a}\times\overrightarrow{b}=\overrightarrow{b}\times\overrightarrow{a}$$;
  *II. Distributiva*: $$\overrightarrow{a}\times(\overrightarrow{b}+\overrightarrow{c})=\overrightarrow{a}\times\overrightarrow{b}+\overrightarrow{a}\times\overrightarrow{c}$$ 
  #+END_QUOTE
  
  Duas Formas de representar uma **multiplicação vetorial**:
  I. $$\overrightarrow{a}\times{x}=(a_x, a_y)\times{x}\implies(a_x\times{x},a_y\times{x})\implies\overrightarrow{a}\times{x}=(a_xx,x_yx)$$
  
  II. $$\overrightarrow{a}\times{x}=\begin{bmatrix} a_x \\ a_y\end{bmatrix}\times{x}\implies\begin{bmatrix} a_x\times{x} \\a_y\times{x}\end{bmatrix}\implies\overrightarrow{a}\times{x}=\begin{bmatrix} a_xx \\ a_yx\end{bmatrix}$$
- ## Ângulos
  heading:: 2
  $$\overrightarrow{a}\times\overrightarrow{b}=|\overrightarrow{a}|\times|\overrightarrow{b}|\times\cos\theta\space\space\text{ ou }\space\space\cos\theta=\frac{\overrightarrow{a}\times\overrightarrow{b}}{|\overrightarrow{a}|\times|\overrightarrow{b}|}$$
  
  I. Se $$\overrightarrow{a}\times\overrightarrow{b}<0\implies\theta>90^o$$;
  II. Se $$\overrightarrow{a}\times\overrightarrow{b}=0\implies\theta=90^o$$;
  I. Se $$\overrightarrow{a}\times\overrightarrow{b}>0\implies\theta<90^o$$;
- ## Combinação linear
  heading:: 2
  O vetor $$c$$ é a combinação dos vetores $$a$$ e $$b$$ se pudermos escrever:
  $$c=\beta\times{a}+\alpha\times{b}$$
- {{colored-text #d9d898, "this is a test text, which should be colored"}}