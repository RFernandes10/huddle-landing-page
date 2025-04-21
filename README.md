![Demonstração do Projeto](https://github.com/RFernandes10/huddle-landing-page/blob/master/src/video/Animação-tela-projeto.gif?raw=true)


# 🚀 Huddle Landing Page

Landing page responsiva e acessível da plataforma fictícia **Huddle**, desenvolvida com **HTML** e **CSS**. Este projeto foi criado como parte do desafio **[Huddle Landing Page with Single Introductory Section](https://www.frontendmentor.io/challenges/huddle-landing-page-with-single-introductory-section-B_2Wvxgi0)** do Frontend Mentor, com foco em **design limpo**, **acessibilidade** e **responsividade**.

---

## 🎯 Desafio do Projeto

Criar uma landing page estática para a **Huddle**, utilizando apenas HTML e CSS, com os seguintes objetivos:

- ✅ Layout fiel ao design fornecido (desktop e mobile).
- ✅ Responsividade com media queries.
- ✅ Acessibilidade com uso de semântica e contraste adequado.
- ✅ Interatividade mínima com efeitos de hover.

---

## 📦 Tecnologias Utilizadas

- 🌐 **HTML5** – Estrutura semântica da página.
- 🎨 **CSS3** – Estilização com Flexbox e media queries.
- 🖋️ **Google Fonts** – Fontes *Poppins* (títulos) e *Open Sans* (texto).
- 🖼️ **Font Awesome** – Ícones sociais interativos no rodapé.

---

## ✨ Funcionalidades

- 📱 **Design Responsivo** para mobile (375px) e desktop (1440px).
- ♿ **Acessibilidade** com tags semânticas, `alt` nas imagens e contraste adequado (5.92:1).
- 🌄 **Imagens de Fundo Dinâmicas** alternando entre `bg-desktop.svg` e `bg-mobile.svg`.
- 🔗 **Ícones Sociais com Hover** com bordas e cores customizadas.
- 🧩 **Estrutura CSS Modular** separando reset, estilos principais e responsividade.

---

## 📁 Estrutura do Projeto

```bash
📦 huddle-landing-page
┣ 📂 design
┃ ┣ 📜 active-states.jpg
┃ ┣ 📜 desktop-design.jpg
┃ ┣ 📜 desktop-preview.jpg
┃ ┣ 📜 mobile-design.jpg
┃ ┗ 📜 identificando-elementos-visualmente.png
┣ 📂 screenshots
┃ ┣ 📜 desktop-result.png
┃ ┣ 📜 mobile-result.png
┃ ┗ 📜 demo-animation.gif
┣ 📂 src
┃ ┣ 📂 css
┃ ┃ ┣ 📜 reset.css
┃ ┃ ┣ 📜 estilos.css
┃ ┃ ┗ 📜 responsivo.css
┃ ┣ 📂 images
┃ ┃ ┣ 📜 bg-desktop.svg
┃ ┃ ┣ 📜 bg-mobile.svg
┃ ┃ ┣ 📜 favicon-32x32.png
┃ ┃ ┣ 📜 illustration-mockups.svg
┃ ┃ ┗ 📜 logo.svg
┣ 📜 index.html
┣ 📜 README.md
┣ 📜 style-guide.md
┗ 📜 .gitignore

---


## 🛠️ Desafios e Soluções

### Alternância de fundos (desktop/mobile)
**Desafio:** Mudar imagem de fundo conforme a resolução.  
**Solução:** Media query com `@media (max-width: 375px)` para alterar `background-image`.

---

### Ícones sociais sem SVGs fornecidos
**Desafio:** Ícones não estavam incluídos no desafio.  
**Solução:** Integração com CDN do Font Awesome e aplicação de estilo com hover seguindo o design.

---

### Acessibilidade no design
**Desafio:** Garantir acessibilidade com HTML puro.  
**Solução:** Tags semânticas (`<header>`, `<main>`, `<footer>`), atributos `alt`, contraste testado conforme WCAG (5.92:1).

---

## 📚 O Que Aprendi

- **Responsividade** com media queries e Flexbox.
- **Acessibilidade** com semântica e contraste de cores.
- **Organização de arquivos** e pastas para projetos escaláveis.
- **Documentação** com markdown claro e estruturado.

---

## 🤝 Créditos

- 💡 **Desafio por:** [Frontend Mentor](https://www.frontendmentor.io/)
- 🛠️ **Desenvolvido por:** [RFernandes10](https://github.com/RFernandes10)

---

## 🔗 Links Úteis

- [🔗 Desafio no Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-single-introductory-section-B_2Wvxgi0)
- [🔗 Repositório no GitHub](https://github.com/RFernandes10/huddle-landing-page)
- [🔗 Google Fonts – Poppins e Open Sans](https://fonts.google.com/)
- [🔗 Font Awesome – Ícones Sociais](https://fontawesome.com/)

