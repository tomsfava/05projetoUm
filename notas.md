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