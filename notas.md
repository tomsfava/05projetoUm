# Projeto Nº1
## notas
### videoaula nº1
O projeto número um apresentado na primeira videoaula é a criação de um site para uma loja de games,
havia um formulário de 'fale conosco' um 'objeto' 'link' para as redes sociais da loja, uma foto grande
e um texto ao seu lado.\
**Isso é tudo que eu me recordo, vou me inteirando enquanto vou fazendo.**
#### **Tive algumas idéias**:
- um buscador automático de ofertas de games em sites selecionados, programado em _python_
- um botão fixo no canto inferior direito que abre uma pagina de formulário para o fale conosco (ou)
- um menu superior com a página de ofertas, um sobre nós, o fale conosco
### videoaula nº2
O título dessa videoaula é 'Crie o cabeçalho', o resumo da aula diz nela vou compreender os elementos principais que compõem o cabeçalho de um site, além de compreender os conceitos básicos de layout usando Flexbox. \
#### **Lista de ações durante a videoaula**
1. Criar arquivo index.html
2. Pré-configurar o cabeçalho html com o atalho html:5
3. Mudar a linguagem para 'pt-br'
4. Mudar o título da página
5. Configurar o header: h1 com o título da página e ul com links de acesso para o Sobre a loja e para o Contato
6. Criar o arquivo main.css e definir as propriedades de margin, padding e box-sizing do seletor *
7. Definir color e background-color para o seletor header e também para o header li a
8. Definir a largura máxima, centralizar o conteúdo do header através do uso de uma div class container (margin: 0 auto;)
9. Alinhar e espaçar os elementos do container com display:flex;, align-items:center; e justify-content: space-beetween;
### videoaula nº3
compreender a importância de criar sessões bem estruturadas através das tags semânticas HTML, posicionar imagens e texto lado a lado, aplicar margens e espaçamentos, utilizar propriedades de fontes, segmentar elementos atravesses de classes e IDs
#### **Lista de ações durante a videoaula**
1. Criar uma section e dentro dela outro div class container
2. Dentro do container adicionar uma tag img com a imagem da loja
3. Criar outra div para os paragrafos preenchidos com Lorem
4. Dentro da mesma div criar uma nova div com uma ul com tres li com as imagens das logos das marcas de videogame
5. Configurar a altura máxima dos logos para 24px e a exibição em linha através do display:inline;
6. Colocar a imagem e o texto um ao lado do outro com display:flex; reaproveitar a regra para o container do header para o container da section
7. Sobrescrever a propriedade align-items com o valor flex-start
8. Aumentar o espaçamento interno dentro da section
9. Definir as margens dos novos elementos (o professor criou uma nova classe para a imagem que ele queria estilizar sozinha, sem estilizar as logos das marcas, eu resolvi isso adicionando um > ao seletor, evidenciando que a img a ser editada era somente aquela que é filha direta da section, na verdade não deu certo porque a img não era filha direta da section, mas sim da div container, depois que eu corrigi isso deu certo)
10. Procurar fontes do google fonts (o professor já selecionou duas fontes: Roboto e Bungee), copiar o codigo link para meu header e depois estilizar em css
11. Alterar o valor do font-weight dos títulos para normal
12. Alterar a cor do conteúdo da section para o mesmo da cor de fundo do header
13. Adicionar uma margem direita para as logos de 8px
### videoaula nº4
criar uma seção de contato interativa em uma página da web, aplicar estilos de design, criar um formulário funcional
#### **Lista de ações durante a aula**
1. Criar uma nova section
2. Criar a div .container
3. Criar 3 novas divs dentro da div container, uma para o fale conosco, outra para as redes sociais e outra para o endereço fisico da loja
4. Dentro da div de fale conosco criar um formulário com 3 inputs (nome, email, telefone), 1 textarea e 1 botão
5. Na div das redes sociais vamos adicionar 3 links com as imgs dos logos do insta, face e youtube
6. Na div do endereço somente um paragrafo com um endereço ficticio
7. Para estilização adicionamos uma classe a ul dos links para redes sociais e limitamos o height das img dentro de .social-links para 24px
8. Pelo mesmo motivo adicionamos um id a section de contato e configuramos o display do .container dentro dessa section para block, assim o h2 fica acima da div dos conteudos e _eu amo a Tis_
9. A essa div damos a class 'metodos' e essa configuramos para display flex e space-between justify-content
10. Estilizamos o formulário para que os inputs o textarea e o button tenham display block, configuramos a largura para 320px, além da margin-botton e o padding para 8px
11. Removemos a propriedade resize do textarea e padronizamos sua height para 180px
12. Adicionamos margin-botton para o h3 de 16 px
13. Configuramos o botão para ter as cores do site além de adicionarmos o comportamento pointer para o cursor e através do pseudoseletor hover configuramos uma leve mudança de cor para o botão
14. Através do pseudoseletor focus, configuramos a cor da borda dos inputs e textarea ao serem selecionados para a cor do site
15. Criamos um rodapé e adicionamos um rodapé com o símbolo comercial dentro de um paragrafo com a frase todos os direitos reservados
16. Estilizamos o rodapé para as mesmas cores do site
### videoaula nº5
publicar o site para a internet na plataforma vercel; criar repositorio git
#### **Lista de ações durante a aula**
1. Abrir o terminal através de f1 e pesquisar terminal
2. git init, git add ., git commit -m
3. criar repositório no github
4. copiar as instruções
5. realizar push