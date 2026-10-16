# 🎬 MovieCity - Landing Page

A **MovieCity** é uma landing page responsiva de um serviço fictício de streaming de filmes, construída com **React**, **Vite** e **CSS puro**. O projeto foi desenvolvido como um exercício prático de componentização, estilização manual e adaptação de layouts para múltiplos dispositivos.

---

## 🛠️ Tecnologias Utilizadas

* **React 19**: Biblioteca para construção de interfaces baseadas em componentes.
* **Vite 7**: Servidor de desenvolvimento rápido e *bundler* de produção.
* **JavaScript (ESM)**: Lógica do projeto e componentes.
* **CSS Puro**: Estilização global, animações e responsividade com *media queries* (sem bibliotecas de UI).
* **ESLint**: Padronização e análise estática de código.

---

## 🚀 Funcionalidades e Destaques

* **Design Responsivo**: Adaptado para monitores, tablets e smartphones.
* **Menu Hambúrguer**: Animação do menu de navegação em telas menores feita exclusivamente com CSS.
* **Grid de Filmes**: Apresentação de pôsteres com efeitos de *hover* e transição.
* **Acessibilidade**: Atributos `aria-label` e `aria-expanded` implementados no menu mobile.

---

## 📁 Estrutura de Pastas

```text
01_landinpage/
├── public/
│   └── vite.svg            # Favicon
├── src/
│   ├── assets/             # Imagens dos pôsteres de filmes
│   ├── components/
│   │   ├── Header.jsx      # Cabeçalho com navegação e menu mobile
│   │   ├── Main.jsx        # Seção principal e grid dos cards
│   │   └── Home.jsx        # Container principal da página
│   ├── App.jsx             # Renderiza o componente Home
│   ├── index.css           # Estilos globais e media queries
│   └── main.jsx            # Ponto de entrada do React
├── index.html              # HTML raiz
├── package.json
└── vite.config.js

---

## ⚙️ Pré-requisitos

Antes de rodar o projeto localmente, certifique-se de ter instalado:
* **Node.js**: Versão `20.19+` ou `22.12+`.
* **npm** (já incluso com o Node.js).
