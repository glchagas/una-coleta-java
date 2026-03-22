# 🚀 Sistema de Recrutamento Espacial (Java + Scanner)

Este projeto tem como objetivo demonstrar o uso da classe `Scanner` em Java por meio de uma simulação divertida: um **sistema de recrutamento de tripulantes para uma missão espacial**.

## 🧠 Conceito

A classe `Scanner` é utilizada para capturar dados digitados pelo usuário no terminal. Neste projeto, ela funciona como o **sistema de entrada da nave**, permitindo coletar diferentes tipos de informações dos candidatos.

## 🎯 Objetivo

Simular um processo de recrutamento onde o programa coleta dados de um candidato a astronauta, utilizando diferentes métodos da classe `Scanner`.

## 🛠️ Tecnologias utilizadas
Java
java.util.Scanner
📚 O que você aprende aqui
Como importar e utilizar a classe Scanner
Como capturar diferentes tipos de dados do usuário
Como interagir com o usuário via terminal
Como organizar entradas e saídas em um programa simples
⚠️ Atenção
Após usar métodos como nextInt() ou nextDouble(), pode ser necessário limpar o buffer com nextLine() antes de ler textos novamente.
O método nextBoolean() aceita apenas true ou false.

## 📌 Possíveis melhorias
Validação de dados inseridos pelo usuário
Menu interativo
Armazenamento dos candidatos em lista
Interface gráfica (GUI)

## 📥 Tipos de dados capturados

Durante a execução, o sistema solicitará:

- 📝 **Texto** → Nome do candidato (`nextLine()`)
- 🔢 **Números inteiros** → Idade (`nextInt()`)
- 📊 **Números decimais** → Altura (`nextDouble()`)
- ✅ **Booleano (true/false)** → Possui experiência prévia? (`nextBoolean()`)

## 🧪 Exemplo de execução

```bash
=== SISTEMA DE RECRUTAMENTO ESPACIAL ===

Digite seu nome:
> João Silva

Digite sua idade:
> 29

Digite sua altura:
> 1.75

Possui experiência em missões espaciais? (true/false):
> true

=== DADOS DO CANDIDATO ===
Nome: João Silva
Idade: 29
Altura: 1.75
Experiência: true
```
## 👨‍🚀 Autor
Projeto desenvolvido para fins educacionais, com foco no aprendizado da linguagem Java.
