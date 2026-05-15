- data de início: [[28-03-2026]] 
  data de término: [[28-03-2026]] 
  data de edição:
  referências: [Variáveis, atribuição, e strings](https://python.ic.ufrj.br/aulas/aula-04/index.html)
  linkado com: [[Python]], [[Tipos de dados]]
- ## Variáveis
  heading:: 2
  Maneira simbólica de fazer referência a dados armazenados na memória do computador. Toda variável engloba os seguintes aspectos, semelhantes aos parâmetros de uma função:
  + *Nome (identificador): representação simbólica da variável;*
  + *Valor: o que de fato está armazenado;*
  + *Tipo: o [[Tipos de dados]] que está armazenado nela.*
  
  #+BEGIN_QUOTE
  Uma variável existe apenas dentro da função onde foi definida e não pode ser acessada fora da função.
  #+END_QUOTE
- ## String
  heading:: 2
  **Concatenação**: para concatenar strings usamos ==+==;
  **Replicação**: para replicar strings usamos ==*==;
  + **len()** é usada para saber o <u>tamanho</u> (a quantidade de caracteres) de uma string;
  + **in** é usado para verificar se o que está à esquerda aparece "dentro" da string que está à direita:
  | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
  | Caractere | J | i | s | o | o |
  | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
  | Índice | 0 | 1 | 2 | 3 | 4 |
  #+BEGIN_QUOTE
  ==!!! IMPORTANTE: as strings, assim como os dados numéricos, são dados **imutáveis**.==
  #+END_QUOTE
  **Fatiamento**: separa trechos de uma string;
- ## Tupla 
  heading:: 2
  É uma sequência heterogênea (permite que seus elementos sejam de tipos diferentes). É uma *variável composta*.
  | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
  | Caractere | L | a | l | i | s | a |
  | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
  | Índice | 0 | 1 | 2 | 3 | 4 | 5 |
  | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
  | Índice | -6 | -5 | -4 | -3 | -2 | -1 |
  #+BEGIN_QUOTE
  ==!!! IMPORTANTE: as tuplas, assim como as strings, são dados **imutáveis**.==
  #+END_QUOTE
  + Tuplas devem ser usadas em situações em que não há necessidade de adicionar, remover ou alterar elementos de um grupo de itens.