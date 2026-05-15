- data de início: [[22-03-2026]] 
  data de término:
  data de edição:
  referências: [Tipos de dados](https://python.ic.ufrj.br/aulas/aula-03/index.html), [Tipos de variáveis disponíveis no Python](https://pythonacademy.com.br/blog/tipos-de-variaveis-no-python), [Tipo de dados booleanos (Visual Basic)](https://learn.microsoft.com/pt-pt/dotnet/visual-basic/language-reference/data-types/boolean-data-type), [Estruturas Condicionais em Python: if, elif e else](https://universopython.com/blog/estruturas-condicionais-python-if-elif-else)
  linkado com: [[Python]]
- ## Números
  heading:: 2
  1. ==Inteiro ou **int**:== é composto por caracteres numéricos **inteiros**, ou seja, não há pontos ou vírgulas;
  *Exemplos: 0, -1* 
  2. ==Ponto flutuante ou **float**:== é composto por caracteres números **decimais**;
  *Exemplos: 1., 3E3, 25., -.5, 25e0*
  *[[E notation]]*
  3. ==Número complexo ou **complex**:== usado para representar número **complexo** - geralmente aparece em cálculos geométricos e científicos.
  *Exemplos: 1j, 1+0j*
- ## String
  heading:: 2
  1. ==String ou **str**:== geralmente utilizada para representar palavras, frases ou textos. O Python vai interpretar com string qualquer **sequência de texto que está entre aspas**, sejam essas **simples ou duplas**.
  *Exemplos: 'dois', "2", '2.2e1', "1+5j", 'False'*
  1.1 **Concatenação (+)**: junta duas strings em um único objeto;
  *Exemplo: 'a' + 'b' = 'ab', '11' + '3' = '113', int("12") + 4 = 16*
  1.2 **Autocontenação sucessiva (*)**: faz o operador * repetir o conteúdo sequencial.
  *Exemplo: "ab" * 3 = 'ababab'*
- ## Boleanos
  heading:: 2
  1. ==Booleano ou **bool**==: contém valores que podem ser apenas **True** ou **False**, sendo esses operadores lógicos.
  
  1.1 **Números**: zero (0) é **False**, **True** é todo o resto;
  1.2 **String**: " " ou ' ' é **False**, **True** é todo o resto.
	- **Operadores Lógicos**
	  + **not** (negação): inverte o valor lógico de uma expressão ou valor booleanos.
	  *Exemplo: not True = False, not 9 = False*
	  + **and** (e): retorna True <u>apenas</u> se ambos forem True.
	  *Exemplo:  6 > 5 and 7 > 6 = True, 4 > 5 and 7 >6 = False*
	  + **or**: retorna True se pelo menos um deles for True. Retorna False apenas quando ambos forem False.
	- ## Tabela da verdade
	  heading:: 2
	  | A | B | **not** A | **not** B | A **or** B | A **and** B | 
	  | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
	  | False | False | True | True | False | False |
	  | False | True | True | False | True | False |
	  | True | False | False | True | True | False |
	  | True | True | False | False | True | True |
	- ## Estruturas Condicionais
	  heading:: 2
	  + **if**: permite a escolha de ações para uma situação encontrada;
	  + **else**: permite executar algo caso a condição não for atendida e, mesmo assim, é preciso realizar outra ação;
	  + **elif**: permite exercutar múltiplas condições para verificar.