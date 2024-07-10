# 02-estudos-html

### ÍNDICE

- [PRINCIPAIS TAGS](#principais-tags)
- [MARCAÇÕES](#marcações)
- [LINKS E IMAGENS](#links-e-imagens)
- [TRABALHANDO COM LISTAS](#trabalhando-com-listas)
- [TRABALHANDO COM TABELA](#trabalhando-com-tabela)
- [TRABALHANDO COM FORMULÁRIOS](#trabalhando-com-formulários)
- [TIPOS DE INPUT](#tipos-de-input)
- [SELECT](#select)
- [TEXTAREA](#textarea)
- [TRABALHANDO COM VÍDEO](#trabalhando-com-video)
- [TRABALHANDO COM IFRAME](#trabalhando-com-iframe)

### LINKS DE VÍDEOS CURSOS E DOCUMENTAÇÃO

- <a href="https://www.youtube.com/playlist?list=PL-u8JWLN6xau0QpzuOTeTI954SsIGEsVA">HTML5 - CSS3 - Referência em Vídeo da Hcode</a>
- <a href="https://www.youtube.com/playlist?list=PLHz_AreHm4dlAnJ_jJtV29RFxnPHDuk9o">Curso de HTML5 Completo</a>
- <a href="https://developer.mozilla.org/en-US/docs/Learn/HTML">Documentação do mozzila developer</a> (_obs: usar em "en-US" para ter o exemplos dos códigos_)
- <a href="https://www.w3schools.com/html/default.asp">Documentação do w3schools </a>

#

### PRINCIPAIS TAGS

<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element" >Documentação Elementos AQUI</a>

- `<!– –>` //Cria um comentário
- `<!– –>` //Cria um comentário
- `<meta></meta>` //Para identificar a página para o buscador e setar informações da página
- `<title></title>` //Para identificar a página. Nunca repita o "tittle" nas páginas para ajudar o buscador
- `<link></link>` //Usado para relacionar o arquivo HTML ao CSS, JS, etc
- `<style></style>` //Css interno
- `<script></script>` //Vincula um JS
- `<div></div>` //Conteúdo em bloco
- `<span></span>` //Conteúdo em linha sem peso semantico, (usado mais para adicionar css e texto, costuma usar dentro de "p")
- `<header></header>` //Para o cabeçalho, pode ter mais de um na página mas com contextos diferentes
- `<nav></nav>` //Para criar menu, para navegação, e para agrupar os links de navegação, podemos repetir independente de onde tiver
- `<main></main>` //Para o conteúdo principal da página
- `<article></article>` //Para conteúdo que faz sentido independente da importância e separar semanticamente para os buscadores
- `<section></section>` //Para separa os blocos da página, separar as seções, não é semanticamente boa mas ainda melhor que "div"
- `<aside></aside>` //para fazer conteúdo "ao lado", um conteúdo secundário, para dar peso semantico
- `<footer></footer>` //Criar um rodapé
- `<h1></h1>` //Para criar título, vai até o "h6" com ordem de importancia, usar apenas um h1
- `<h2></h2>` //Para criar o subtitulo mais importante
- `<p></p>` //Para criar um parágrafo
- `<a></a>` //Para criar links
- `<img></img>` //Para inserir uma imagem
- `<svg></svg>` //vetor
- `<figure></figure>` //Para inserir uma figura e tornar o HTML semantico
- `<br>` //Para quebrar uma linha
- `<button></button>` //Para criar botao, sempre identifique o "type"
- `<form></form>` //Para criar um formulário
- `<input></input>` //Para definir um campo de entrada para o usuário
- `<fieldset</fieldset>` //Para criar um grupo de campos de formulários
- `<select></select>` //Para criar lista suspensa
- `<option></option>` //Para mostrar opções lista suspensa "select"
- `<optgroup></optgroup>` //Para criar grupos dentro de uma lista suspensa "select"
- `<datalist></datalist>` //Para criar auto complete em listas suspensas "select"
- `<textarea></textarea>` //Para colocar texto dentro
- `<output></output>` //Para mostrar resultado de um calculo
- `<meter></meter>` //Para mostrar em gráfico uma medida dentro de um intervalo, ex: espaço em HD usados de 5mb de 15mb
- `<progress></progress>` //Para mostrar o nivel de progresso de uma tarefa
- `<legend></legend>` //Para criar legendas
- `<table></table>` //Para criar tabelas
- `<tr></tr>` //Para criar linha da tabela
- `<td></td>` //Para criar coluna na tabela
- `<thead></thead>` //Para criar o "head" da tabela
- `<th></th>` //Para criar celulas na "head" da tabela, substitui o "td"
- `<tbody></tbody>` //Para criar o body da tabela
- `<tfoot></tfoot>` //Para criar o foot da tabela
- `<details></details>` //cria uma seta para clicar e expandir, é obrigado ter um "summary", peso semantico nas buscas, é melhor que fazer por JS ou CSS
- `<summary></summary>` //usada apenas dentro de "details"
- `<ul></ul>` //Para criar uma lista ordenada
- `<ol></ol>` //Para criar uma lista não ordenada
- `<li></li>` //Para criar um item de uma lista
- `<audio></audio>` //Para imbuir elementos de áudio
- `<video></video>` //Para incorporar conteúdo de vídeo
- `<embed></embed>` //Para embutir um arquivo dentro da página
- `<picture></picture>` //para colocar uma imagem na tela usando "img" e source, bom para tela responsivas, fazendo HTML escolher a fonte de acordo com o tamanho da tela
- `<source></source>` //para usar dentro de "video", "audio" e "picture", usamos ela para dar mais de uma fonte, para dar fontes alternativas
- `<embed></embed>` //Para embutir um arquivo dentro da página
- `<object></object>` //para definir um objeto dentro do HTML, arquivos que não são lidos por padrão (arquivos, video, audio, PDF, java), pode usar tambem dentro de formulário
- `<param></param>` //para definir parametros para TAG "object"
- `<iframe></iframe>` //para imbutir outro HTML dentro do HTML por link ou ".html"
- `<map></map>` //para definir uma area dentro de um elemento onde podemos inserir links, sempre usado com a TAG "area"
- `<area></area>` //para definir uma area dentro do "map"
- `<data></data>` //para associar o texto com algum outro dado, ex: `<data value=1>` camiseta M `<data/>`
- `<time></time>` //para identificar buscadores sobre tempo
- `<code></code>` //para identificar como codigo de computador
- `<iframe></iframe>` //para imbutir outro HTML dentro do HTML por link ou ".html"
- `<dl></dl>` //para definir uma lista com descrição
- `<dt></dt>` //para definir um termo (título) da lista com descrição "dl"
- `<dd></dd>` //para definir uma descrição da lista com descrição "dl"
- `<strong> </strong>` <strong>em negrito</strong>
- `<em> </em>` // Este é um texto <em>em italico</em>
- `<mark> </mark>` // Para marcar o texto como se fosse um marca texto amarelo
- `<small> </small>` // Para deixar o texto pequeno
- `<del> </del>` // Este é um texto <del>que foi removido</del> e substituido por este
- `<ins> </ins>` // Este é um texto <ins>que foi inserido</ins>
- `<sub> </sub>` // Este é um texto <sub>subscript</sub> , ex: O<sub>-2</sub>
- `<sup> </sup>` // Este é um texto <sup>superscript</sup> , ex: X<sup>2</sup>

#

### ATRIBUTOS GLOBAIS

<p class="separador">ATRIBUTOS GLOBAIS (usado em qualquer TAG)</p>

- `class=""` / para adicionar classe do CSS (.)
- `id=""` / para adicionar ID do CSS (#)
- `accesskey=""` / define uma tecla para focar elemento, tecla de atalho
- `contenteditable=""` / conteudo pode ou nao ser editavel (true, false)
- `data-=""` / armazenar dados de um elemento, resgistros invisiveis ao usuario
- `dir=""` / direção do conteudo (auto, ltr, rtl (x to x))
- `draggable=""` / elemento pode ser arrastado (false, true) ex: rrastar arquivos
- `dropzone=""` / aceita elemento draggable (false, true), ex: campo onde recebe arquivos;
- `hidden` / oculta o elemento
- `lang=""` / linguagem do conteudo do elemento, para buscador e tradutor
- `spellcheck=""` / verificar ortografia do elemento escrito pelo usuario
- `translate=""` / se o conteudo pode ou nao ser traduzido
- `tabindex=""` / organiza a tabulação dos formularios (form tabindex="1")
- `title=""` / box informativo que abre com o mouse em cima

  <p class="separador">EVENTOS DO ELEMENTO - TODOS COM PREFIXO "on"</p>
  <p class="separador">EVENTOS DE JANELA DO ELEMENTO</p>

- `afterprint=""` / Disparado quando manda a página ser impressa.
- `beforeprint=""` / Disparado antes de mandar a página ser impressa.
- `beforeunload=""` / Disparado antes do navegador carregar outra página. (o que paginas de anuncios usam para te deixar preso...)
- `error=""` / Disparado quando ocorrer um erro.
- `hashchange=""` / Disparado quando o hash da url da página é alterado (.com.br#alterado).
- `load=""` / Disparado quando toda a página for carregada (a janela carregada).
- `message=""` / Disparado quando ocorrer uma mensagem.
- `offline=""` / Disparado quando o navegador é desconectado da internet.
- `online=""` / Disparado quando o navegador é conectado com a internet.
- `pagehide=""` / Disparado quando a página é ocultada do usuario.
- `pageshow=""` / Disparado quando a página é mostrada ao usuario, inicia apos "onload".
- `popstate=""` / Disparado quando a ocorrência no histórico do navegador é alterada.
- `resize=""` / Disparado quando a janela é redimensionada, largura e altura.
- `storage=""` / Disparado quando o armazenamento do navegador é alterado.
- `unload=""` / Disparado quando o usuário atualiza a página ou fecha a janela.
  
<p class="separador">EVENTOS DE FORMULARIO DO ELEMENTO</p>

- `blur=""` / Disparado quando o foco do elemento é removido.
- `change=""` / Disparado quando termina de altera o valor do elemento, apos prencher um campo do formulario e tirar o foco, o "blur" tambem acontece antes do change
- `contextmenu=""` / Disparado quando o usuário abre o menu de contexto, ex: clicar com botao direito em cima do elemento com "contextmenu".
- `focus=""` / Disparado quando o elemento é focado.
- `input=""` / Disparado quando o elemento recebe uma entrada de valor, sempre que entra dados dentro do elemento
- `invalid=""` / Disparado quando o valor do elemento é inválido.
- `reset=""` / Disparado quando o valor do elemento é redefinido ao estado inicial. ex: button type="reset"
- `search=""` / Disparado quando o elemento input do tipo search é enviado. Escrever em um campo e apertar enter. ex: input="search"
- `select=""` / Disparado quando o valor do elemento é selecionado
- `submit=""` / Disparado quando o formulário é enviado.
<p class="separador">EVENTOS DE TECLADO</p>

- `keydown=""` / Disparado quando a tecla vai para baixo.
- `keypress=""` / Disparado quando a tecla é pressionada.
- `keyup=""` / Disparado quando a tecla é solta.

<p class="separador">EVENTOS DE MOUSE DO ELEMENTO</p>

- `click=""` / Disparado quando o elemento recebe um clique.
- `dblclick=""` / Disparado quando o elemento recebe um clique duplo.
- `mousedown=""` / Disparado quando o botão do clique vai para baixo.
- `mousemove=""` / Disparado quando o cursor do mouse se move sobre o elemento.
- `mouseout=""` / Disparado quando o cursor do mouse NÃO ESTÁ em cima do elemento.
- `mouseover=""` / Disparado quando o cursor do mouse ESTÁ em cima do elemento.
- `mouseup=""` / Disparado quando o botão do clique é solto.
- `wheel=""` / Disparado quando a roda do mouse é rodada.
- `mouseenter=""` / Disparado quando o cursor do mouse entra em cima do elemento.
- `mouseleave=""` / Disparado quando o cursor do mouse sai de cima do elemento.

<p class="separador">EVENTOS DE ARRASTO DO ELEMENTO</p>

- `drag=""` / Disparado quando o elemento é arrastado, é preciso que o elemento seja "draggable".
- `dragend=""` / Disparado quando o elemento para de ser arrastado.
- `dragenter=""` / Disparado quando o elemento arrastado entra em um elemento que permite soltar.
- `dragleave=""` / Disparado quando o elemento arrastado sai de cima de um elemento que permite soltar.
- `dragover=""` / Disparado quando o elemento arrastado passa em um elemento que permite soltar.
- `dragstart=""` / Disparado quando o elemento começa a ser arrastado.
- `drop=""` / Disparado quando o elemento é solto dendro do elemento selecionado.
- `scroll=""` / Disparado quando o scroll é rolado

<p class="separador">EVENTOS DE TRANSFERENCIA</p>

- `copy=""` / Disparado quando o conteúdo do elemento é copiado.
- ` cut=""` / Disparado quando o conteúdo do elemento é recortado.
- `paste=""` / Disparado quando o conteúdo do elemento é colado.

<p class="separador">EVENTOS DE MIDIA DO ELEMENTO</p>

- `abort=""` / Disparado quando o carregamento da mídia é cancelado.
- `canplay=""` / Disparado quando a mídia carregou o suficiente para começar.
- `canplaythrough=""` / Disparado quando a mídia carregou e pode ser reproduzido até o final.
- `cuechange=""` / Disparado quando o texto de uma trilha é alterado.
- `durationchange` / Disparado quando o tamanho total da mídia é alterado.
- `emptied=""` / Disparado quando acontece algum problema e a mídia fica indisponível.
- `ended=""` / Disparado quando a mídia foi consumida até o fim.
- `error=""` / Disparado quando um erro acontece.
- `loadeddata=""` / Disparado quando os dados da mídia são carregados.
- `loadedmetadata=""` / Disparado quando os metadados da mídia são carregados.
- `loadstart=""` / Disparado quando os dados da mídia começam a ser carregados.
- `pause=""` / Disparado quando a mídia é pausada.
- `play=""` / Disparado quando a mídia é começada.
- `playing=""` / Disparado quando depois que a mídia realmente começou.
- `progress=""` / Disparado enquanto o navegador obtém os dados da mídia.
- `ratechange=""` / Disparado quando a taxa de reprodução é alterada.
- `seeked=""` / Disparado quando a busca de dados da mídia terminou.
- `seeking=""` / Disparado quando a busca de dados da mídia está acontecendo.
- `stalled=""` / Disparado quando o navegador não pode buscar os dados de mídia por qualquer motivo.
- `suspend=""` / Disparado quando a busca de dados da mídia é parado antes de ser completamente carregado.
- `timeupdate=""` / Disparado quando a posição da reprodução é alterada.
- `volumechange=""` / Disparado quando o volume do áudio da mídia é alterado.
- `waiting=""` / Disparado quando a mídia é pausada para armazenar mais dados em buffer.

<p class="separador">OUTROS</p>

- `toggle=""` / Disparado quando o usuário abre ou fecha o elemento details.

#

### LINKS E IMAGENS

<a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Creating_hyperlinks">Documentação Hiperlinks AQUI</a> <br />  
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/img">Documentação de Imagens AQUI</a>

- `<a href="../localArquivo">` Link para um arquivo, como para um outro index.html
- `<img src="https://linkdaimagemonline.com" alt="identificadorDaImagem" width="400px" />` Para pegar um link online, onde identificamos um nome se para ele caso não carregue e também já damos um tamanho como opção
- `<img src="../localArquivo" alt="id" width="250px"/>` Buscar imagem dentro de um local no projeto
- `<a href="https://linkDoLocalOnline.com"> <img src="../localArquivo" alt="sorvete" width="250px"> </a>` Vamos pegar um link online e agregar a um arquivo que estamos usando no projeto
- Para criar um link ancora:

```
    <a href="#ancora" id="ancora02"> clique aqui 01 </a>

    <a href="#ancora02"> <img id="ancora" src="../localDaImagem"/> clique aqui 02 </a>

<!-- Quando clicamos no link "clique aqui 01" vamos ser jogados diretamente ao "id='ancora'" e quando clicarmos no
"clique aqui 02" vamos ser levamos até o " id='ancora02'"-->
```

#

### TRABALHANDO COM LISTAS

<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol">Documentação de Listas AQUI</a>

#### Lista não ordenada

```
Exemplo de construção:

    <ul>
      <li>arroz</li>
      <li>feijão</li>
      <li>agua</li>
    </ul>

<!-- Na lista não ordenada vamos ter uma bolinha na frente -->
```

#### Lista ordenada de um ranking

```
Exemplo de construção:

    <ol>
      <li>João</li>
      <li>Julia</li>
      <li>Matheus</li>
    </ol>

<!-- Na lista ordenada vamos ter uma numeração na frente -->
```

#

### TRABALHANDO COM TABELA

<a href="https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics">Documentação de Tabelas AQUI</a>

```
Exemplo de construção:

<table>
    <tr>    <!-- Table rol (linha da tabela) -->
        <th>Nome</th>   <!-- table head (cabeçalho da tabela) -->
        <th>telefone</th>
        <th>email</th>
    </tr>
    <tr> <!-- criar uma nova linha na tabela e por dentro dela o conteúdo preferido -->
        <td>Edio</td> <!-- table date (dados da tabela) -->
        <td>48 969696969</td>
        <td>emailpretendido@hotmail.com</td>
    </tr>
    <tr>
        <td>Matheus</td>
        <td>48 968698968</td>
        <td>outroemailpretendido@hotmail.com</td>
    </tr>
</table>

```

#

### TRABALHANDO COM FORMULÁRIOS

<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form">Documentação de Formulários AQUI</a>

<p>Primeiro devemos definir o método de envio, sendo "GET" ou "POST" e depois adicionar a action.</p>
<p> "action" nada mais é do que o local onde identificamos o link para onde será enviado as informações do "form". Se os dados serão enviados para o mesmo domínio vamos colocar apenas "/loca" se for em outro domínio precisaremos colocar o endereço completo. <br /> *ex1:* "http://programadorbr.com.br/cadastro" (para outro dominio)<br/> 
*ex2:* "/cadastro" (para o próprio dominio) </p>

#### Método "get"

<a href="https://www.dofactory.com/html/method/get">Documentação "get" AQUI</a>

<p>Com o método "get" todas informções serão enviadas para o campo de endereço.</p>

<p> <b>EX:</b> <br /> Aqui pegamos um link de youtube <b> "https://www.youtube.com/results?search_query" </b> que transformamos em um campo de busca usando "get", onde identificamos que <b> "https://www.youtube.com/results?" </b> é a "action", e <b> "search_query"</b> é o "name".
</p>

```
    <form method="get" action="https://www.youtube.com/results?">
      <input id="searchYouTube"  type="text" name="search_query" placeholder="digite aqui" />
      <input type="submit" />
    </form>
<!-- Vamos ter um campo para preencher que quando dermos submit ele irá buscar no youtube-->
```

#### Método "post"

<a href="https://www.dofactory.com/html/method/post">Documentação "post" AQUI</a>

<p>Com o método "post" todas informções serão escondidas. Vamos usar sempre em campo de login.</p>

```
<form method="post" action="/localDoDominio">
    <input id="email" type="text" name="email" />
    <input id="name" type="text" name="name" />
    <input type="submit" />
</form>
<!-- Toda a informação digitada nos campos serão omitidas para os usuários -->
```

#

### TIPOS DE INPUT

<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/text">Documentação AQUI</a>

input <b>"type: text"</b> para usar com texto
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/text">(Documentação AQUI)</a>

```
    <form method="get" action="https://www.youtube.com/results?">
      <input id="" type="text" name="search_query" placeholder="digite aqui" />
      <input type="submit" />
    </form>
```

input <b>"type: checkbox"</b> cria uma checkbox, onde vemos identificar cada um com um valor para quando o item for selecionado o backend entender o que foi atribuído na seleção.
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/checkbox">Documentação AQUI</a>

```
<"-- Com "checkbox" podemos selecionar mais de um item -->
    <form method="get" action="/localDomínio">
      <input id="" type="checkbox" name="curso" value="op1" /> React Native <br />
      <input id="" type="checkbox" name="curso" value="op2" /> React Js  <br />
      <input type="submit" />
    </form>
```

input <b>"type: radio"</b> cria uma caixa de seleção igual o checkbox, onde vemos identificar cada um com um valor para quando o item for selecionado o backend entende o que foi atribuído na seleção. Com "radio" podemos selecionar apenas 1 item por vez e se usar "checked" já vamos deixar um item selecionado automaticamente.
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/radio">Documentação AQUI</a>

```
    <form method="get" action="/localDomínio">
      <input id="" type="radio" name="genero" value="masc" checked /> Masculino <br />
      <input id="" type="radio" name="genero" value="fem" /> Feminino <br />
      <input type="submit" />
    </form>
```

input <b>"type: reset"</b> para resetar todos os campos preenchidos e voltar ao formato padrão do formulário.
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/reset">Documentação AQUI</a>

```
    <form method="get" action="/localDomínio">
      <input id="" type="checkbox" name="curso" value="op1" /> itens 1 <br />
      <input id="" type="checkbox" name="curso" value="op2" /> itens 2 <br />
      <input id="" type="checkbox" name="curso" value="op2" /> itens 3 <br />
      <input id="" type="radio" name="genero" value="masc" checked /> Masculino <br />
      <input id="" type="radio" name="genero" value="fem" /> Feminino <br />
      <input type="reset" value="Limpar" />
      <input type="submit" value="Enviar" />
    </form>
```

input <b>"type: color"</b> Para criar uma caixa de cor onde vai ser enviado exadecimal da cor selecionada
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/color">Documentação AQUI</a>

```
    <form method="get" action="">
      <input type="color" name="cor" /> <br />
      <input type="submit" />
    </form>
```

input <b>"type: password"</b> deixa todo pontilhado e é usado com método "post"
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/password">Documentação AQUI</a>

```
    <form method="post" action="/localDomínio">
      <input id="" type="password" name="senha" placeholder="senha" />
      <input type="submit" />
    </form>
```

input <b>"type: date"</b> para criar uma caixa de data
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/date">Documentação AQUI</a>

```
    <form method="get" action="">
      <input type="date" name="date" /> <!-- Formato padrão --> <br />
      <input type="date" name="date" max="2022-07-20" /> <!-- Com data maxima para selecionar --> <br />
      <input type="datetime-local" name="date" /> <!-- Formato com data e hora --> <br />
      <input type="submit" />
    </form>
```

input <b>"type: file"</b> para enviar arquivo vamos usar "file" e o método tem de ser "post"
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/file">Documentação AQUI</a>

```
    <form method="post" action="">
      <input type="file" name="arquivo" /> <br />
      <input type="reset" name="limpar" value="limpar" />
      <input type="submit" value="enviar" />
    </form>
```

input <b>"type: number"</b> campo exclusivo para números
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/number">Documentação AQUI</a>

```
    <form method="post" action="">
      <input type="number" name="numero" /> formato padrão<br />
      <input type="number" name="numero" min="5" max="10" />
      <input type="submit" value="enviar" />
    </form>
```

input <b>"type: range"</b> Campo para intervalos
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/Input/range">Documentação AQUI</a>

```
    <form method="post" action="">
      <input type="range" name="intervalo" min="-10" max="10" value="0" />
      <input type="submit" value="enviar" />
    </form>
```

input <b>"type: email"</b> para identificar se é um email ou não
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/email">Documentação AQUI</a>

```
    <form method="post" action="/localDomínio">
      <input id="" type="password" name="senha" placeholder="email" />
      <input type="submit" />
    </form>
```

input <b>"type: tel</b> campo para telefones
<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input/tel">Documentação AQUI</a>

```
    <form method="post" action="">
      <input type="tel" name="telefone" /><br />
      <input type="submit" value="enviar" />
    </form>
```

#

### SELECT

<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select">Documentação select AQUI</a>

```
    <form method="get" action="">
      <select name="estado">
        <option value="RJ">Rio de Janeiro</option>
        <option value="SP" selected>São Paulo</option>
        <option value="ES">Espirito Santo</option>
      </select>
      <input type="submit" value="Enviar" />
    </form>
<!-- O valor enviado para o backend é sempre o que está após o "value". Se quiser fixar umas das opções como
padrão vamos colocar o atributo "selected na "option" desejada. -->
```

<br />
Podemos também fazer algumas alterações no "select", como o "size" e o "multiple", onde o "size" vai mostrar 
visualmente o número proposto na formatação e o "multiple" vai deixar selecionar mais de uma opção.

```
    <form method="get" action="">
      <select name="estado" size="4" multiple>
        <option value="RJ">Rio de Janeiro</option>
        <option value="SP" selected>São Paulo</option>
        <option value="ES">Espirito Santo</option>
        <option value="RS">Rio Grande do Sul</option>
        <option value="BH">Bahia</option>
        <option value="SC">Santa Catarina</option>
      </select>
      <input type="submit" value="Enviar" />
    </form>
```

#

### TEXTAREA

<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/textarea">Documentação textares AQUI</a>
<br />

```
    <form method="get" action="">
      <input type="text" name="assunto" placeholder="Assunto" /> <br />
      <textarea
        name="mensagem" cols="30" rows="10" placeholder="Digite aqui">
      </textarea>
      <input type="submit" value="Enviar" />
    </form>
```

#

### TRABALHANDO COM VIDEO

<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/video">Documentação de video AQUI</a><br />

```
    <video controls muted src="./localVideoDentroDoDiretorio" width="500px">
    </video>
<!-- aqui inserimos um vídeo na página com o tamanho setado -->
```

<p><b>Vídeo atributos</b></p>

- `controls` por padrão o "vídeo" vem sem os controles, então colocamos o atributo "controls" para ter
  acesso aos controles.
- `autoplay` serve para ao carregar a página o vídeo já iniciar automaticamente, mas alguns navegadores não
  dão play automático caso tenha som no vídeo, então devemos também usar "muted"
- `loop` toda vez que o vídeo termina de rodar ele inicia novamente
- `poster` para adicionar uma imagem de capa para o vídeo
- `preload` tem 3 opções de valores para ele, "auto" ao carregar a página o vídeo vai começar a carregar na
  memória do computador automaticamente, "none" o vídeo só vai carregar se o usuário der play no vídeo, "metadata"
  quando a página terminar de carregar o vídeo já vai ter alguns dados carregados, como o player, nome de autor,
  etc, os meta dados mas não o conteúdo do vídeo.

#

### TRABALHANDO COM IFRAME

<a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/iframe">Documentação iframe AQUI</a><br />

<p>Usando o iFrame para mostrar o conteúdo de outra página</p>

```
    <iframe class="frame" src="./README.md" frameborder="0"></iframe>
```

<p>iFrame serve para colocar o conteúdo de outra pagina dentro de uma página, ela é muito útil para pôr vídeo de 
outros sites dentro da própria página. No caso do youtube podemos ir em compartilhar (shere) ela terá embed onde 
tem um código iFrame
</p>

```
    <iframe width="560"
        height="315"
        src="https://www.youtube.com/embed/ikUJg2YAX3M"
        title="YouTube video player"
        frameborder="0"
        allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
        allowfullscreen>
    </iframe>
```

## 🚧 _Projeto EM CONSTRUÇÃO_ 🚧
