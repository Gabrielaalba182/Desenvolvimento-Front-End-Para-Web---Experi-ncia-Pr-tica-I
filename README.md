 # 🌍 Instituto Esperança — Plataforma Web de Apoio a ONGs

## 🧭 Objetivo Geral
Desenvolver uma **plataforma web completa e profissional** que permita a ONGs gerenciar suas atividades, divulgar projetos, captar recursos e engajar voluntários, aplicando, de forma integrada, todos os conceitos estudados nas quatro unidades da disciplina.

---

## 📁 Estrutura do Projeto

├── index.html # Página inicial — sobre a organização e contato
├── projetos.html # Página de projetos sociais e doações
├── cadastro.html # Página de cadastro com formulário interativo
│
├── css/
│ └── style.css # Estilos globais e responsivos
│
├── js/
│ └── masks.js # Máscaras e validações nativas para CPF, telefone e CEP
│
└── images/
└── hero.jpg # Imagem de capa (placeholder)

---

## ⚙️ Recursos e Técnicas Utilizadas

- **HTML5 Semântico:** uso de `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.
- **Hierarquia de Títulos:** estruturada de forma lógica (`<h1>` até `<h3>`).
- **Formulário Completo (HTML5):**
  - Campos: Nome, Email, CPF, Telefone, Data de Nascimento, Endereço, CEP, Cidade e Estado.
  - Validação nativa com `required`, `type`, `pattern` e `maxlength`.
  - Máscaras de entrada via JavaScript (CPF, telefone e CEP).
  - Agrupamento semântico com `<fieldset>` e `<legend>`.
- **Acessibilidade:** uso de `aria-label`, `alt` e `label for`.
- **Boas práticas de SEO e performance:** meta tags, lazy loading e imagens otimizadas.
- **CSS puro:** design limpo e responsivo, com container centralizado e espaçamento uniforme.
