# Operadores lógicos com retorno em True/False:
OR, NOT, AND.


# POO: 
Classes com atributos que podem ou não varias, métodos e estados.


# Pilares POO: 
Herança, polimorfismo, encapsulamento e abstração.


# Variáveis:
visibilidade? modificador? tipo nome valorInicial? 
(? nos que não são obrigatórios)

Variável "static" e "final" não altera (CONSTANTE)

Java é case sentitive. $ e _ (a exceção do _ é a constante) devem ser evitados nos nomes de variáveis (e não se inicia nome de variável com números)

Variável começa com letra minuscula, tem nome expressivo (não abreviar coisas que não dá para ter certeza do que é), notaçãoCamelo.

CONSTANTE com letra maiúscula e separada por _.

# Tipos de dados: 
Numeral:
float = 3.14 (f) -No float sempre tem que colocar o (f);
double = 3.14 (d) -Pode ou não colocar o (d);



# Operadores:
int i = ++k; é igual a: i = k + 1;
int j = k--; é igual a: j = k, k = k - 1;


# Casting:
Quando for diminuir o dado para caber no novo tipo, deve ser explicita a necessidade (downcast).

Exemplos:

int i;
long l = 100;
i = (int)l;

float f;
double d = 10.5d;
f = (float) d;

int i;
float f = 10.5f;
i = (int)f; (perda dos dados que estão após o ponto (decimais) = Truncar).

# Método:
visibilidade? tipo? modificador? retorno nome(parametros? (idade)) excecoes? {corpo}

visibilidade = public, rotected, private
tipo = concreto ou abstrato
modificador = static ou final
retorno = tipo dado ou void
nome = nome que é fornecido ao metodo (segue mesmas boas práticas do nome de variável, e deve ser expressivo, mas não longo)
parametros = parametros que pode receber
excecoes = exceções que pode lançar
corpo = código que possui ou vazio

- Para chamar:
NomeDaCLasse.nomeDoMetodo();
nomeDoObjeto.nomeDoMetodo();

assinatura do metodo = nomeIdDoMetodo(parametros); ou,
nomeIdDoMetodo();

