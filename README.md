# supertrunfonov

# 🃏 Super Trunfo de Cidades - Nível Novato

Este é um projeto simples em linguagem C que simula o cadastro de cartas do jogo Super Trunfo com foco em cidades brasileiras. Foi desenvolvido como parte de um desafio para iniciantes, com o objetivo de praticar leitura, armazenamento e exibição de dados.

---

## ✅ Objetivo

Permitir ao usuário cadastrar **duas cartas** do Super Trunfo contendo informações de cidades, e exibir essas informações de forma organizada na tela.

---

## 🛠️ Tecnologias e Ferramentas

- Linguagem C
- Compilador `gcc`
- Terminal / Console
- GitHub

---

## 🧠 O que foi praticado

- Leitura de dados via `scanf`
- Armazenamento em variáveis simples
- Exibição de dados formatada com `printf`
- Uso de `char`, `int`, `float` e arrays de caracteres (strings)

---

## 📋 Informações de cada carta

Cada carta possui os seguintes campos:

- **Estado**: Uma letra de 'A' a 'H' (`char`)
- **Código da Carta**: Ex: A01, B03 (`char[]`)
- **Nome da Cidade**: Ex: São Paulo (`char[]`)
- **População**: Número de habitantes (`int`)
- **Área (em km²)**: Tamanho da cidade (`float`)
- **PIB**: Produto Interno Bruto em bilhões de reais (`float`)
- **Número de Pontos Turísticos**: (`int`)

---

## 📦 Como compilar e executar

### Usando o terminal com `gcc`:

```bash
# Compile o código
gcc super_trunfo.c -o super_trunfo

# Execute o programa
./super_trunfo
