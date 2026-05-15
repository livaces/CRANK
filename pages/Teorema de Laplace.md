- [#A] Created: [[22-04-2026]] 
  Updated:
  Sources: [Teorema de Laplace, Ester Velasquez](https://youtu.be/Yb2cHMO20mI?si=YcheOcdmurIFMBh1) 
  Subject: [[Vetores no R2 e R3]]
  
  #+BEGIN_QUOTE
  O determinante de uma matriz A (quadrada de ordem n) é igual à soma dos produtos dos elementos de uma linha (ou coluna) e de seus respectivos cofatores.
  #+END_QUOTE
  
  ==Considerações importantes==
  $$i=\begin{bmatrix}
  a_{11} \\
  b_{21} \\
  c_{31} \\
  \end{bmatrix}
  \space\space{,}\space\space
  j=\begin{bmatrix}
  a_{12} \\
  b_{22} \\
  c_{32} \\
  \end{bmatrix}
  \space\space{,}\space\space
  k=\begin{bmatrix}
  a_{13} \\
  b_{23} \\
  c_{33} \\
  \end{bmatrix}
  \space\space{,}\space\space
  l=\begin{bmatrix}
  a_{11} & a_{12} & a_{13} \\
  \end{bmatrix}
  \space\space{,}\space\space
  m=\begin{bmatrix}
  b_{21} & b_{22} & b_{23} \\
  \end{bmatrix}
  \space\space{,}\space\space
  n=\begin{bmatrix}
  c_{31} & c_{32} & c_{33} \\
  \end{bmatrix}$$
  
  Temos, portanto:
  $$A=\begin{bmatrix}
  a_{11} & a_{12} & a_{13} \\
  b_{21} & b_{22} & b_{23} \\
  c_{31} & c_{32} & c_{33} \\
  \end{bmatrix}$$
  
  Pelo **Teorema de Laplace**:
  
  $$\text{det }{A}=a_{11}\times\underbrace{(-1)^{l+i}}_{\text{cofator}}\times\underbrace{\begin{bmatrix}
  b_{22} & b_{23} \\
  c_{32} & c_{33} \\
  \end{bmatrix}}_{\text{menor complementar}}+a_{12}\times(-1)^{l+j}\times\begin{bmatrix}
  b_{21} & b_{23} \\
  c_{31} & c_{33} \\
  \end{bmatrix}+a_{13}\times(-1)^{l+k}\times\begin{bmatrix}
  b_{21} & b_{22} \\
  c_{31} & c_{32} \\
  \end{bmatrix}$$