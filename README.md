Huddle Landing Page
Visão Geral
Bem-vindo(a) à minha solução para o desafio Huddle Landing Page with Single Introductory Section do Frontend Mentor! Este projeto foi uma oportunidade incrível para praticar minhas habilidades em HTML e CSS, criando uma página inicial responsiva que se adapta a telas de desktop e mobile. Meu objetivo foi replicar o design fornecido, garantindo um layout limpo, acessível e visualmente atraente.
Demonstração
Aqui está uma demonstração rápida do projeto em ação:
Resultado Final
Desktop (1440px)
Mobile (375px)
Sobre o Projeto
Este projeto faz parte do meu aprendizado em desenvolvimento front-end, realizado como parte de um curso. O desafio consistiu em construir uma página inicial para a Huddle, uma plataforma fictícia de construção de comunidades. A página apresenta:

Um header com o logo da Huddle.
Uma seção hero com uma ilustração, um título, um parágrafo e um botão de registro.
Um footer com ícones sociais (Facebook, Twitter, Instagram).
Layout responsivo, ajustando-se automaticamente entre desktop e mobile.

Designs de Referência
Desktop
Mobile
Como Rodar o Projeto

Clone este repositório:
git clone https://github.com/RFernandes10/huddle-landing-page.git


Abra o arquivo index.html em um navegador web moderno (como Chrome, Firefox ou Edge).

Para testar o layout responsivo, redimensione a janela do navegador ou use as ferramentas de desenvolvedor (tecla F12) para simular uma tela de 375px.


Estrutura do Projeto
huddle-landing-page/
│
├── design/                    # Imagens de referência do design
│   ├── active-states.jpg      # Estados interativos (hover) dos elementos
│   ├── desktop-design.jpg     # Layout de referência para desktop
│   ├── desktop-preview.jpg    # Prévia do layout desktop
│   ├── mobile-design.jpg      # Layout de referência para mobile
│   └── identificando-elementos-visualmente.png  # Imagem com anotações visuais
│
├── screenshots/               # Capturas de tela e vídeo do resultado final
│   ├── desktop-result.png     # Resultado final no desktop
│   ├── mobile-result.png      # Resultado final no mobile
│   └── demo-video.mp4         # Vídeo demonstrativo do projeto
│
├── src/                       # Arquivos do projeto
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
├── index.html                 # Arquivo HTML principal
├── README.md                  # Documentação principal do projeto
└── style-guide.md             # Guia de estilo do projeto

Tecnologias Usadas

HTML5: Estrutura semântica da página.
CSS3: Estilização, layout responsivo com Flexbox e media queries.
Google Fonts: Fontes Poppins (títulos) e Open Sans (corpo do texto).
Font Awesome: Ícones sociais no rodapé.

Desafios e Soluções

Desafio: Criar um layout responsivo que alternasse entre os fundos bg-desktop.svg e bg-mobile.svg.
Solução: Usei um media query (@media (max-width: 375px)) no responsivo.css para mudar o fundo e reorganizar os elementos em uma coluna no mobile.


Desafio: Estilizar os ícones sociais sem SVGs fornecidos pelo desafio.
Solução: Inteirei o Font Awesome via CDN e apliquei efeitos de hover baseados no active-states.jpg.


Desafio: Garantir acessibilidade com contraste de cores e semântica.
Solução: Usei tags semânticas (<header>, <main>, <footer>), atributos alt nas imagens e confirmei que o contraste entre texto branco e fundo violeta atende às diretrizes WCAG (proporção 5.92:1).



O Que Aprendi

Responsividade: Aprofundei meu conhecimento em media queries, ajustando o layout para diferentes tamanhos de tela de forma fluida.
Acessibilidade: Aprendi a importância de usar atributos alt, tags semânticas e verificar o contraste de cores para tornar a página mais inclusiva.
Organização: Estruturei o projeto em pastas (design, src, screenshots), o que facilitou o desenvolvimento e a manutenção.
Documentação: Criei um README.md e um style-guide.md detalhados, reforçando a importância de documentar projetos para colaboração e avaliação.

Créditos

Desafio criado por Frontend Mentor.
Desenvolvido por RFernandes10.

Links Úteis

Desafio no Frontend Mentor
Repositório no GitHub
Google Fonts (Poppins e Open Sans)
Font Awesome (ícones sociais)

