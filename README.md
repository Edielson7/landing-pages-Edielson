README para Minha Página Web

Este arquivo README fornece uma visão geral e instruções para utilizar a página web desenvolvida com
HTML e CSS.
===================================================================================
Visão Geral

Esta página web é uma estrutura básica com diversas seções, demonstrando conceitos de HTML e CSS para
a criação de layouts responsivos e interativos. Ela inclui um menu lateral responsivo, seções de introdução,
listagem de trabalhos ("Top 3" e "Works"), uma galeria de imagens, uma tabela de preços e um formulário
de contato.

===================================================================================
As tecnologias principais utilizadas são:

• HTML (HyperText Markup Language): Utilizado para estruturar o conteúdo da página, organizando
as seções, textos, imagens, links e o formulário. A semântica do HTML5 é empregada com
elementos como "<header>", "<nav>", "<main>", "<aside>", "<footer>" e "<section>.

• CSS (Cascading Style Sheets): Utilizado para estilizar a aparência da página, controlando o layout
(com Grid Layout), tipografia (com fontes do Google Fonts), cores, espaçamentos e a
responsividade para diferentes tamanhos de tela (com Media Queries).
O objetivo desta página é servir como um modelo ou demonstração de diferentes elementos e layouts web
construídos com HTML e CSS.
Conteúdo do Arquivo

===================================================================================
Este projeto contém os seguintes arquivos:

• index.html: O arquivo HTML principal que define a estrutura e o conteúdo da página.
• Css/style.css: O arquivo CSS que contém todas as regras de estilo para a página, organizado em
seções para facilitar a manutenção.
• Imagem/logo.jpg: Imagem utilizada como logotipo no menu lateral.
• Imagem/introimg.svg: ImagemSVG utilizada na seção de introdução e contato.
• Imagem/css.png, Imagem/html.png, Imagem/javascript.png, Imagem/sql.png, Imagem/java.png,
Imagem/php.png: Imagens utilizadas na seção de galeria.

===================================================================================
Como Utilizar

Para visualizar esta página web, siga estas instruções:
1. Clone ou baixe o repositório (se aplicável): Se este código estiver em um repositório Git, você pode
cloná-lo para o seu computador usando o comando:
Bash
git clone [URL_do_repositório]
Caso contrário, baixe os arquivos diretamente.

2. Abra o arquivo index.html: Navegue até a pasta onde os arquivos foram salvos e abra o arquivo
index.html com o seu navegador de internet preferido (Google Chrome, Mozilla Firefox, Safari,
etc.).

3. Visualize a página: O navegador interpretará o arquivo HTML e aplicará os estilos definidos no
arquivo Css/style.css para exibir a página web com o layout e a aparência desejados.Estrutura do HTML
O arquivo index.html está estruturado da seguinte forma:

• <!DOCTYPE html> e <html lang="pt-BR">: Declaração do tipo de documento e definição do idioma
principal da página como Português do Brasil.

• <head>: Contém metadados importantes como codificação de caracteres (UTF-8), configuração da
viewport para responsividade, título da página (<title>), link para o arquivo CSS (<link
rel="stylesheet" href="Css/style.css">), e links para as fontes "Inter" e "Open Sans" do Google
Fonts.

• <body>: Contém todo o conteúdo visível da página:

o Menu Lateral (<aside class="menu">): Um menu responsivo que pode ser aberto e
fechado usando um checkbox (<input id="close-menu">) e uma label associada. Contém
um logotipo, navegação com links para as diferentes seções da página e desaparece em
telas menores, sendo acessível através do ícone "≡".

o Espaçamento do Menu (<div class="menu-spacing">): Utilizado para evitar que o
conteúdo principal seja sobreposto pelo menu fixo.

o Seção de Introdução (<section id="home" class="intro">): Apresenta um título e um texto
introdutório, juntamente com uma imagem ilustrativa.

o Seção de Introdução de Texto (<section id="intro">): Contém um título "Introdução" e
alguns parágrafos de texto de exemplo.

o Seção "Top 3 jobs" (<section id="top3" class="grid-one">): Exibe três artigos em um
layout de grid, com títulos e descrições de exemplo.

o Seção de Galeria (<section id="gallery">): Apresenta uma galeria de imagens em um
layout de grid.

o Seção "Works" (<section id="grid02" class="grid-one">): Similar à seção "Top 3", exibe
mais três artigos em um layout de grid.

o Seção de Preços (<section id="preco">): Contém um título "Preço", um texto de exemplo e
uma tabela de preços responsiva.

o Espaçamento do Menu (outro <div> class="menu-spacing">): Outro espaçamento para a
seção de contato.

o Seção de Contato (<section id="contato" class="intro">): Apresenta um título "Contato",
um texto de exemplo, uma imagem e um formulário de contato com campos para nome,
sobrenome, e-mail e mensagem.

o Rodapé (<footer class="footer">): Exibe uma mensagem de direitos autorais ou
informações sobre o desenvolvedor.

o Botão "Voltar ao Topo" (<a class="back-to-top" href="#">): Um link fixo no canto inferior
direito que permite ao usuário retornar ao topo da página.

===================================================================================
Estilização com CSS

O arquivo Css/style.css fornece a estilização completa da página, incluindo:
• Reset de Estilos: Garante uma base consistente para todos os navegadores.

• Estilos Globais: Define a tipografia base (fontes, tamanho, cor, line-height), cor de fundo do corpo e estilos para títulos (h1 a h6) e parágrafos (p).

• Layout Principal: Define classes para planos de fundo (.main-bg, .white-bg) e para o conteúdo
principal (.main-content) com largura máxima e margens centralizadas.

• Seções (.section): Define um espaçamento vertical padrão para as seções da página.

• Seção de Introdução (.intro-content): Utiliza Grid Layout para organizar o texto e a imagem lado a
lado em telas maiores e empilhados em telas menores (com Media Query).

• Menu Lateral (.menu, .close-menu, etc.): Estiliza o menu lateral responsivo, incluindo sua posição
fixa, transição, layout interno e a lógica de mostrar/ocultar com o checkbox e a label.

• Grid Layout (.grid-one, .grid): Define um layout de grid responsivo para as seções "Top 3", "Works"
e Galeria.

• Galeria (.gallery-img): Estiliza as imagens da galeria com largura máxima e efeito de hover.

• Tabela de Preços (.responsive-table, table, th, td, etc.): Estiliza a tabela de preços e a torna
responsiva com overflow horizontal em telas menores.

• Formulário de Contato (.contact-form, .form-grid, .form-group, etc.): Estiliza o formulário de
contato com um layout de grid para os campos e estilos para labels, inputs, textarea e botão de
envio.

• Rodapé (.footer): Estiliza o rodapé com alinhamento centralizado e tamanho da fonte menor.

• Botão "Voltar ao Topo" (.back-to-top): Estiliza o botão fixo para retornar ao topo da página com
uma transição suave.

• Media Queries: Ajusta o layout e a apresentação de diferentes elementos para telas com largura
máxima de 800px e 600px, garantindo a responsividade da página.

===================================================================================
Créditos

• Fontes "Inter" e "Open Sans" fornecidas pelo Google Fonts.
