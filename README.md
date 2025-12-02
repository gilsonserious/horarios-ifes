# 📅 Sistema de Horários - Ifes Campus São Mateus

![Ifes Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/a/a0/Ifes_Logo.svg/200px-Ifes_Logo.svg.png)

> Um visualizador de horários simples, rápido e responsivo para a comunidade acadêmica do Ifes Campus São Mateus.

![Badge License](https://img.shields.io/badge/license-MIT-green)
![Badge Version](https://img.shields.io/badge/version-2025%2F2-blue)
![Badge Tech](https://img.shields.io/badge/tech-HTML%20%7C%20CSS%20%7C%20JS-orange)

---

## 📋 Índice

- [Sobre o Projeto](#-sobre-o-projeto)
- [Funcionalidades](#-funcionalidades)
- [Layout e Design](#-layout-e-design)
- [Estrutura de Arquivos](#-estrutura-de-arquivos)
- [Como Executar](#-como-executar)
- [Como Atualizar os Dados](#-como-atualizar-os-dados)
- [Tecnologias Utilizadas](#-tecnologias-utilizadas)
- [Créditos](#-créditos)

---

## 📖 Sobre o Projeto

Este projeto foi desenvolvido para facilitar a visualização das grades horárias de aulas. Ao invés de procurar em extensos arquivos PDF, o usuário pode selecionar rapidamente o filtro desejado (Turma, Professor ou Sala) e visualizar a imagem correspondente imediatamente.

O sistema foi construído para ser leve, rodando inteiramente no navegador (Client-Side), sem necessidade de banco de dados complexo ou backend.

---

## ✨ Funcionalidades

* **Filtros Dinâmicos:** Seleção cruzada por Turmas, Professores e Salas.
* **Limpeza Automática:** Ao selecionar um filtro, os outros são resetados para evitar confusão.
* **Responsividade Total:** Funciona perfeitamente em Desktop, Tablets e Smartphones.
* **Tratamento de Erros:** Exibe mensagens amigáveis caso uma imagem não seja encontrada.
* **Identidade Visual:** Segue estritamente a paleta de cores oficial do Ifes (Vermelho e Verde).

---

## 🎨 Layout e Design

O projeto utiliza a identidade visual oficial do Instituto Federal:

| Cor | Hex | Uso |
| :--- | :--- | :--- |
| 🔴 **Vermelho** | `#cd191e` | Cabeçalho, Bordas de erro, Rodapé |
| 🟢 **Verde** | `#2f9e41` | Detalhes, Foco, Links |
| ⚫ **Escuro** | `#333333` | Textos, Fundo do Rodapé |
| ⚪ **Claro** | `#f9f9f9` | Fundo da página |

---

## 📂 Estrutura de Arquivos

Para que o sistema funcione, a estrutura de pastas deve ser rigorosamente mantida:

```text
/ (Raiz do Projeto)
│
├── index.html           # Arquivo principal
├── icones/
│   └── unnamed.webp     # Imagem padrão de espera
│
├── turmas/              # Imagens das turmas (.jpg)
│   ├── turma_page-0001.jpg
│   ├── turma_page-0002.jpg
│   └── ...
│
├── professores/         # Imagens dos professores (.jpg)
│   ├── Professor_page-0001.jpg
│   ├── Professor_page-0002.jpg
│   └── ...
│
└── salas/               # Imagens das salas (.jpg)
    ├── Sala_page-0001.jpg
    ├── Sala_page-0002.jpg
    └── ...
