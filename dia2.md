#  Dia 2 - Variáveis e Tipos de Dados (Visualg)

Hoje vamos aprender um dos pilares da programação:
 **Variáveis**

---

#  O que é uma variável?

Uma variável é um espaço na memória do computador que guarda informações.

 Exemplo simples:
- nome = "Erica"
- idade = 200

É como uma caixa que guarda dados.

---

#  Tipos de Dados

Em Visualg usamos principalmente:

##  Inteiro
Números sem casas decimais
```visualg
idade: inteiro
```

##  Real
Números com casas decimais
```visualg
altura: real
```

##  Literal (texto)
```visualg
nome: literal
```

##  Lógico (booleano)
```visualg
ativo: logico
```

---

#  Declarando Variáveis

```visualg
var
nome: literal
idade: inteiro
altura: real
```

---

#  Primeiro Exemplo

```visualg
algoritmo "variaveis"

var
nome: literal
idade: inteiro

inicio

nome <- "Erica"
idade <- 20

escreval("Nome: ", nome)
escreval("Idade: ", idade)

fimalgoritmo
```

---

#  Explicação

## `var`
Onde declaramos as variáveis.

## `<-`
Significa “recebe”.

## `escreval`
Mostra o conteúdo na tela.

---

#  Entrada de Dados (leia)

Agora o utilizador pode inserir dados:

```visualg
algoritmo "entrada_dados"

var
nome: literal
idade: inteiro

inicio

escreva("Digite seu nome: ")
leia(nome)

escreva("Digite sua idade: ")
leia(idade)

escreval("Olá ", nome, "! Você tem ", idade, " anos.")

fimalgoritmo
```

---

#  Exercícios

##  Exercício 1
Crie um algoritmo que:
- peça o nome do utilizador
- peça a idade
- mostre os dois na tela

---

##  Exercício 2
Crie um algoritmo que:
- peça 2 números inteiros
- mostre a soma deles

---

##  Exercício 3 (Desafio)
Crie um algoritmo que:
- peça nome
- peça idade
- peça altura
- mostre tudo formatado

---

#  Dica Importante

 Variáveis são usadas em TODOS os programas.

Sem elas, não existe programação real.

---

#  Resumo do Dia

Hoje aprendemos:
-  O que são variáveis
-  Tipos de dados
-  Como declarar variáveis
-  Como usar `leia`
-  Como armazenar dados

---

#  Próxima Aula (Dia 3)

Vamos aprender:
- Operadores matemáticos
- Soma, subtração, multiplicação e divisão
- Primeiros cálculos no Visualg

---

# 👩 Autora

## Erica Tatiana 

GitHub:
https://github.com/ericatatiana

---

## ⭐ “Variáveis são a base para guardar informação na programação.”
