Front-end Style Guide
Aviso
NÃO É NECESSÁRIO O USO DO GRID NESTE PROJETO, FACILITE.O layout foi implementado usando Flexbox para simplificar a estrutura e garantir responsividade.
Como eu organizo o projeto?
O layout da página é dividido em três seções principais, conforme identificado na imagem abaixo:


Header: Contém o logo da Huddle, alinhado à esquerda.
Main (seção hero): Inclui a ilustração (illustration-mockups.svg) e o conteúdo textual (título, parágrafo e botão "Register"). No desktop, a ilustração fica à esquerda e o texto à direita, usando display: flex. No mobile (até 375px), os elementos são empilhados verticalmente com flex-direction: column.
Footer: Contém os ícones sociais (Facebook, Twitter, Instagram), alinhados à direita no desktop e centralizados no mobile.

Estrutura do Código

O arquivo index.html segue a estrutura semântica com as tags <header>, <main> (com uma <section class="hero">) e <footer>.
Os estilos estão divididos em:
estilos.css: Estilos principais para o layout desktop.
responsivo.css: Ajustes para o layout mobile, usando um media query (@media (max-width: 375px)).



Cores

Violet: hsl(257, 40%, 49%) - Usada como cor de fundo principal e no texto do botão.
Soft Magenta: hsl(300, 69%, 71%) - Usada nos efeitos de hover do botão e dos ícones sociais.

Fontes

Poppins: Usada para títulos (como o <h1>).  
Peso: 600 (semi-bold).  
Exemplo: <h1>Build The Community Your Fans Will Love</h1>.


Open Sans: Usada para o corpo do texto (parágrafos e botão).  
Peso: 400 (regular).  
Exemplo: <p>Huddle re-imagines the way we build communities...</p>.



As fontes são importadas via Google Fonts no index.html.
Ícones
Os ícones sociais no rodapé (Facebook, Twitter, Instagram) são fornecidos pelo Font Awesome.  

Recursos:  
Ícones do FontAwesome  
Font Awesome


Implementação: Incluídos via CDN no index.html e estilizados no estilos.css com efeitos de hover (borda e cor Soft Magenta).

Estilos Adicionais
Tamanhos de Fonte

Título (<h1>): 3rem no desktop, 1.5rem no mobile.
Parágrafo (<p>): 1.1rem no desktop, 0.9rem no mobile.
Botão: 1rem.
Ícones sociais: 1rem.

Espaçamentos

Padding do header e footer: 2rem 4rem no desktop, 1.5rem 2rem (header) e 2rem (footer) no mobile.
Padding da seção hero: 5rem 4rem no desktop, 2rem no mobile.
Espaço entre ilustração e texto na seção hero: gap: 3rem no desktop, margin-bottom: 2rem no mobile.

Efeitos de Hover

Botão "Register": Muda de fundo branco com texto violeta para fundo Soft Magenta com texto branco.
Ícones sociais: Ganham uma borda de 1px e mudam a cor para Soft Magenta.

Notas

O fundo da página usa bg-desktop.svg no desktop e bg-mobile.svg no mobile, aplicado via CSS com background-image.
As cores, fontes e efeitos de hover foram baseados nas imagens de referência (desktop-design.jpg, mobile-design.jpg, active-states.jpg) fornecidas pelo Frontend Mentor.

[...]
Acessibilidade
Atributos alt nas Imagens

Todas as imagens têm atributos alt para melhorar a acessibilidade para leitores de tela:
Logo: <img src="src/images/logo.svg" alt="Huddle Logo">
Ilustração: <img src="src/images/illustration-mockups.svg" alt="Illustration Mockups">



Contraste de Cores

O texto branco (#FFFFFF) sobre o fundo violeta (hsl(257, 40%, 49%), equivalente a #5C548F) tem uma proporção de contraste de 5.92:1, conforme verificado com o WebAIM Contrast Checker. Isso atende às diretrizes WCAG nível AA (mínimo de 4.5:1 para texto normal) e é adequado para legibilidade.

Navegação por Teclado

O botão "Register" (<button>) e os links dos ícones sociais (<a>) são navegáveis por teclado (usando a tecla Tab), garantindo que a página seja utilizável sem mouse.

Semântica HTML

Usei tags semânticas (<header>, <main>, <footer>) para melhorar a estrutura da página para leitores de tela e facilitar a navegação. [...]