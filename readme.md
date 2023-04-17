<h1 align="center">Site - Coffe Shops Tia Rosa</h1>

<p align="center" display="inline-block">

<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"  alt="top-language"/>
<img src="https://img.shields.io/badge/CSS-239120?&style=for-the-badge&logo=css3&logoColor=white" alt="top-language"/>
<img src="https://img.shields.io/badge/JavaScript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E"/>
</p>

<p>
    <h1 align="center"> Proposta do Projeto</h1>
    <p>  O projeto foi criado para a disciplina de Construção do Frontend, com o objetivo de conhecer a empresa e os produtos. </p>
    <p> As imagens para criação do site foram feitas no Canva e estão armazenadas dentro de uma pasta com os nomes: LogoCoffe.jpg, prod1.png, e venda.png.</p>
    <p> Após a pesquisa da situação problema, optei por criar um site funcional com as informações voltadas à empresa. A mesmo tempo informa-se a possibilidade de realização da compra do produto através da criação de uma loja virtual.  Todos os textos e imagens são de autoria própria, realizado por meio de pesquisas.</p>
    <br>

 **Cores e Fontes usadas no Site**
 

 - Background: #1B1007 e o Branco: #fffff
 - Tipo de fonte usada: inherit


 **Criação da Página Home**


 <p>Após criar um novo documento, dentro da tag html
 colocamos um parâmetro "lang=pt-br" indicando que o site está em português. Logo em seguida usei a tag *title* para definir um titúlo para a página do site: Tia Rosa Coffe Shops.</p>
<p>Na tag *meta* , o charset= “utf-8” informa ao navegador que o idioma do site está em português, permitindo que ele aceite palavras com acentos e cedilhas.</p>
<p>Para que o navegador possa exibir o estilo do site, assim como cor de página, fonte, espaçamento é necessário informar o caminho do arquivo. Para isso dentro da nossa página html criamos a tag link. Essas tags são usadas para indicar uma página, uma imagem, um vídeo. </p>
<p>Dentro da tag body que é onde definimos todo corpo do site, usei uma tag chamada section para cada parte associada ao menu, pois, assim facilita a organização do conteúdo.</p>
<p>Dentro da primeira section criei uma class="menu" para criar as abas do menu e também para definir o estilo dentro do documento estilo.css.Já no documento estilo.css foi criado uma tag .menu li representa a criação de uma lista não ordenada
para crição de um menu horizontal. A tag '.menu li' a faz com que seja aplicado um novo estilo para as ancoras dos menus. Âncoras representadas pela tag a são utilizadas para direcionar um conteúdo dentro de uma mesma página.
A tag figure foi usada para inserir a imagem logo fictício da empresa Coffe Shops Tia Rosa.</p>


**Criação Menu Sobre**

<p>Dentro da tag h2  foi criado um id ="Conheca_a_Nossa_Empresa" vinculado ao menu Sobre. Os id's podem ser usados somente uma vez dentro de uma página html. No documento estilo.css os Id's são representados pelo simbolo sustenido #. 
O elemento 'p' é usado para marcação do paragráfo. E o elemento  para pular linhas dentro de um documento html. </p>

**Criação Menu Produto**

<p>Em produtos criei uma tag section vinculada a uma class="container". Os container's em html são usados para
agrupar elementos. No caso do site usei para colocar uma imagem ao lado do texto.
Dentro da tag section também tem o id="Tipos_de_Graos" que está vinculado ao menu produto. O
elemento p está armazenando o texto de explicação do mesmo.</p>

**Criação Menu Loja Virtual**

<p>Para essa parte criei uma tag section vinculada a uma class ="container-venda". Os container's em html são usados para agrupar elementos. No caso do site usei para colocar uma imagem ao lado do texto.</p>
<p>Dentro dessa section também foi criado a div com o id="comprar" que está vinculado a Loja Virtual. As div's são usadas para agrupar elementos. Nesse caso optei por usar a div para atribuir um estilo diferente para "comprar".</p>
<p>Foi criado também um button que está vinculado a class="btn". Esse botão é demonstrativo. Mas, você poderia inserir um link de uma página personalizada de compras. Foi criado um subtítulo h3 para melhor visualização dos produtos.</p>

**Criação do Menu Fale Conosco**

<p>Para a criação do formulário de contato usei uma tag chamada  tabelas que exibem elementos dispostos em linhas e colunas. Dentro de cada tr usado para as linhas criamos um td vinculado a id's diferentes. Foram criados o idNome, idEmail, idAssunto, idMensagem.</p>
<p>Foi criado um button vinculado a uma validação de envio usando a linguagem JavaScript. Para fazer a validação de envio de mensagem com sucesso foi criado a tag script. Foi criado a função "onclick", ou seja, toda vez que o usuário clicar no botão ele receberá um alerta informando que a mensagem foi enviada com sucesso.</p>

**Rodapé**

<p>Foi criado a tag footer para criação do rodapé. E um h4 para destacar a mensagem do rodapé.</p>
