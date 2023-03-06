# First-Form-World-Daily-News---HTML-CSS-PURE
Olá, esse pequeno projeto de um formulário em html e css puro foi desenvolvido para fins de estudo e prática! O formulário seria para receber noticias diarias pelo email após o usuário se cadastrar, a empresa de jornalismo teria o nome "World Daily News".

A estrutura HTML pode ser descrito da seguinte forma:

- Inicialmente, há uma div com a classe "main_form" que contém um formulário com a classe "element_form". O formulário contém um cabeçalho com o título "Junte-se a World Daily News!" e um parágrafo com uma descrição.
- A seguir, há uma div com a classe "element_logo" que contém uma imagem do logo do site.
- O formulário contém dois campos de entrada com rótulos associados, um para o nome e outro para o e-mail, bem como um botão de envio.
- A seguir, há uma div com a classe "container_terms" que contém um parágrafo com uma descrição dos termos de serviço e um link para mais informações.
- Por fim, há uma div com a classe "element_social_media" que contém links para as redes sociais do site.

Em seguida, o documento CSS que é o estilo da página, pode ser descrito da seguinte forma:

- O primeiro bloco define algumas propriedades básicas para o HTML e o corpo da página, incluindo a remoção das margens e preenchimentos padrão e a definição de uma imagem de fundo que é fixada no lugar e cobre toda a área da página.
- O bloco .main_form define as propriedades para o contêiner do formulário, incluindo a definição de um display flex para centralizar os elementos do formulário, largura e altura automáticas e um preenchimento interno de 60px.
- O bloco .element_form define as propriedades para os elementos do formulário, incluindo um display flex para dispor os elementos em coluna, largura máxima de 300px, altura automática e um preenchimento interno de 2ch. Ele também tem um fundo cinza escuro, borda arredondada e uma sombra que dá uma aparência de profundidade ao formulário.
- O bloco .element_form h1 define as propriedades para o título do formulário, incluindo a margem superior, centralização e tamanho da fonte.
- O bloco .description_of_forms define as propriedades para o texto descritivo que aparece abaixo do título do formulário, incluindo um display flex para centralizar o texto, largura de 300px e altura automática.
- O bloco .element_logo define as propriedades para a imagem do logotipo que aparece acima do título do formulário, incluindo um display flex para centralizar a imagem, largura de 300px e altura de 50px.
- O bloco .element_form label define as propriedades para as etiquetas de rótulo que aparecem acima das entradas de dados do usuário, incluindo a margem superior e o tamanho da fonte.
- O bloco .element_form button define as propriedades para o botão de envio do formulário, incluindo uma transição suave ao passar o mouse, sem borda, um preenchimento interno de 1.4mm e uma margem superior de 5mm. O botão tem uma cor de fundo cinza claro e bordas arredondadas.
- O bloco .element_form input define as propriedades para as entradas de dados do usuário, incluindo uma transição suave ao passar o mouse, sem contorno e uma borda arredondada. Quando a entrada recebe o foco, a borda é alterada para ser mais fina.
- O bloco .conteiner_terms define as propriedades para o texto de termos e condições que aparece abaixo do formulário, incluindo o tamanho da fonte e a justificação do texto. Os links no texto são estilizados com uma cor azul e uma borda inferior que aparece quando o mouse passa sobre eles.
- O bloco .element_social_media define as propriedades para os links das redes sociais que aparecem abaixo do texto dos termos e condições, incluindo um display flex para centralizar os links, largura de 300px e preenchimento interno. Quando o mouse passa sobre os links, eles são ligeiramente opacos.
