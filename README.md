# Coloquem informações do projeto aqui!

Huddle Landing Page
Descrição
Este projeto é uma solução para o desafio "Huddle Landing Page with Single Introductory Section" do Frontend Mentor. O objetivo foi criar uma página inicial responsiva, com um layout que se adapta a telas de desktop e mobile, usando HTML e CSS. A página apresenta uma seção introdutória com uma ilustração, texto, um botão de registro e links para redes sociais no rodapé.
Resultado Final
Desktop
Mobile
Designs de Referência
Desktop
Mobile
Pré-requisitos

Um navegador web moderno (como Chrome, Firefox ou Edge).
Não há dependências adicionais, pois o projeto usa apenas HTML e CSS.

Como Rodar o Projeto

Clone ou baixe este repositório para o seu computador.
Abra o arquivo index.html em um navegador web.
Para testar o layout responsivo, redimensione a janela do navegador ou use as ferramentas de desenvolvedor (tecla F12) para simular uma tela de 375px (layout mobile).

Estrutura do Projeto
huddle-landing-page/
│
├── design/                    # Pasta com imagens de referência do design
│   ├── active-states.jpg      # Estados interativos (hover) dos elementos
│   ├── desktop-design.jpg     # Layout de referência para desktop
│   ├── desktop-preview.jpg    # Prévia do layout desktop
│   ├── mobile-design.jpg      # Layout de referência para mobile
│   └── identificando-elementos-visualmente.png  # Imagem com anotações visuais
│
├── screenshots/               # Pasta com capturas de tela do resultado final
│   ├── desktop-result.png     # Resultado final no desktop
│   └── mobile-result.png      # Resultado final no mobile
│
├── src/                       # Pasta com os arquivos do projeto
│   ├── css/                   # Estilos CSS
│   │   ├── reset.css          # Reset de estilos padrão do navegador
│   │   ├── estilos.css        # Estilos principais (desktop)
│   │   └── responsivo.css     # Ajustes para layout mobile
│   └── images/                # Imagens usadas na página
│       ├── bg-desktop.svg     # Fundo para desktop
│       ├── bg-mobile.svg      # Fundo para mobile
│       ├── favicon-32x32.png  # Favicon da página
│       ├── illustration-mockups.svg  # Ilustração principal
│       └── logo.svg           # Logo da Huddle
│
└── index.html                 # Arquivo HTML principal

Tecnologias Usadas

HTML5: Estrutura da página.
CSS3: Estilização e layout responsivo.
Google Fonts: Fontes Poppins (títulos) e Open Sans (corpo do texto).
Font Awesome: Ícones sociais no rodapé.

Desafios e Soluções

Desafio: Garantir que o layout fosse responsivo, alternando entre os fundos bg-desktop.svg e bg-mobile.svg para desktop e mobile.
Solução: Usei um media query (@media (max-width: 375px)) no arquivo responsivo.css para ajustar o fundo e reorganizar os elementos em uma coluna no mobile.


Desafio: Estilizar os ícones sociais para corresponder ao design, que não fornecia SVGs próprios.
Solução: Usei o Font Awesome para os ícones e adicionei efeitos de hover com base no active-states.jpg.


Desafio: Garantir que as fontes Poppins e Open Sans fossem aplicadas corretamente e correspondessem ao design.
Solução: Importei as fontes via Google Fonts e confirmei sua aplicação usando as ferramentas de desenvolvedor do navegador.



O Que Aprendi

Organização: Aprendi a importância de organizar os assets em pastas separadas (design e images), o que facilitou o desenvolvimento e a manutenção do projeto.
Responsividade: Descobri como usar media queries para criar layouts responsivos, ajustando o fundo, o layout e os tamanhos de fonte para diferentes tamanhos de tela.
Boas Práticas: Adicionei comentários ao código HTML e CSS para facilitar a manutenção, o que me ensinou a pensar na legibilidade e na colaboração em projetos futuros.
Acessibilidade: Usei atributos alt nas imagens, aprendendo como isso melhora a acessibilidade e o SEO da página.

Créditos

Desafio criado por Frontend Mentor.
Desenvolvido por Roberto Fernandes Fonseca.

Links Úteis

Desafio no Frontend Mentor
Google Fonts (para Poppins e Open Sans)
Font Awesome (para ícones sociais)