# 🧊 Sistema de Gerenciamento de Clientes  
### 📁 Implementação em C utilizando Mapa Hash com Encadeamento

Este projeto apresenta um **sistema completo de gerenciamento de clientes**, desenvolvido em **C**, empregando um **Mapa Hash (Hash Table)** com **tratamento de colisões por encadeamento**.  
O objetivo é demonstrar uma estrutura associativa eficiente, organizada e escalável, permitindo armazenar, buscar e gerenciar clientes de forma dinâmica.

Além do código-fonte, o repositório também inclui uma **página visual moderna** em HTML/CSS/JS para exibição sintática do arquivo `.c`, com animações, contador de linhas, botões de copiar/baixar e destaque de sintaxe.

Acesso à página: ([https://gabrielalme14-arch.github.io/hash-map-codigo/])
---

## 🚀 Funcionalidades do Sistema

- Cadastro de clientes  
- Busca por nome  
- Remoção  
- Exibição de todos os registros  
- Menu interativo  
- Função hash eficiente  
- Tratamento de colisões por encadeamento em lista ligada  
- Organização modular por structs e funções

---

## 🧩 Estruturas Utilizadas

### 🔹 `struct Cliente`
Representa um cliente, contendo:
- Nome
- ID
- Telefone
- Ponteiro para o próximo (encadeamento)

### 🔹 `struct Mapa`
Representa a hash table:
- Vetor de ponteiros
- Tamanho da tabela
- Função de hashing
- Funções auxiliares (inserção, busca, remoção, exibição)

---

## 🛠 Tecnologias Envolvidas

**Linguagem:**  
- C (padrão ANSI/ISO)

**Estruturas de Dados:**  
- Hash Table  
- Listas Encadeadas  
- Alocação dinâmica

**Extras do Projeto:**  
- Página HTML estilizada com destaque de sintaxe  
- JavaScript para renderização do código  
- Animações CSS  
- Botão de cópia e download do arquivo  
- Favicon personalizado HMC

---

## 📸 Prévia da Página de Código-Fonte

A interface inclui:
- Janela simulando editor de código  
- Números de linha  
- Destaque colorido por classes  
- Contadores automáticos de:
  - Linhas  
  - Funções  
  - `structs`  
  - Status de funcionalidade  
- Botões:
  - **Copiar código**
  - **Baixar arquivo .c**

---

