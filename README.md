# Formulário de Cadastro

Este projeto é um algoritmo simples desenvolvido em **Portugol**, que simula um **formulário de cadastro** para coletar dados básicos de um usuário.

## 📌 Descrição
O programa solicita ao usuário as seguintes informações:
- Nome
- Endereço
- Idade
- Altura

Após a coleta, esses dados podem ser armazenados ou usados em etapas posteriores (exemplo: exibição em tela, gravação em arquivo, etc.).

## 🛠 Tecnologias Utilizadas
- **Portugol Studio** (ou qualquer compilador de Portugol compatível)
- Lógica de programação estruturada

## 🚀 Como Executar
1. Instale o [Portugol Studio](http://lite.acad.univali.br/portugol/).
2. Copie o código do algoritmo para um novo arquivo `.por`.
3. Execute o programa dentro do Portugol Studio.
4. Insira os dados solicitados no console.

## 📄 Código-Fonte

```portugol
Algoritmo "formulario de cadastro"
// Disciplina   : [Linguagem e Lógica de Programação]
// Professor    : Antonio Carlos Nicolodi
// Descrição    : Algoritmo que coleta informações de cadastro
// Autor(a)     : Nome do(a) aluno(a)
// Data atual   : 13/08/2025

Var
   nome: caractere
   endereco: caractere
   altura: real
   idade: inteiro

Inicio
   escreva("Informe seu nome: ")
   leia(nome)

   escreva("Informe seu endereço: ")
   leia(endereco)

   escreva("Informe sua idade: ")
   leia(idade)

   escreva("Informe sua altura: ")
   leia(altura)
Fimalgoritmo
