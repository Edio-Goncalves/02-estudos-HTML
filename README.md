# 02-estudos-html

Estudos e exercícios

### TAGS

- `<h1>Titulo h1</h1>` //Título mais iportante da página
- `<h2>Titulo h2</h2>` //Subtitulo mais importante
- `<h3>Titulo h3</h3>` //Importância subsequente, vai até h6
- `<p>Parágrafo</p>` //Parágrafo
- `<br />` //Quebra linha
- `<div> <div/>` //Para criar um container genérico para conteúdo de fluxo
- `id="identificador"` //Para criarmos um ID
- `class="identificador"` //Para criarmos uma classe
- `<form> </form>` //Para criar um formulário

### MARCAÇÕES

- `<strong> </strong>` <strong>em negrito</strong>
- `<em> </em>` Este é um texto <em>em italico</em>
- `<mark> </mark>` Para marcar o texto como se fosse um marca texto amarelo
- `<small> </small>` Para deixar o texto pequeno
- `<del> </del>` Este é um texto <del>que foi removido</del> e substituido por este
- `<ins> </ins>` Este é um texto <ins>que foi inserido</ins>
- `<sub> </sub>` Este é um texto <sub>subscript</sub> , ex: O<sub>-2</sub>
- `<sup> </sup>` Este é um texto <sup>superscript</sup> , ex: X<sup>2</sup>

### LINK E IMAGENS

- `<a href="../localArquivo">` Link para um arquivo, como um outro index.html
- `<img src="https://linkdaimagemonline.com" alt="identificadorDaImagem" width="400px" />` Para pegar um link online, onde identificamos um nome caso ela não carregue e já damos um tamanho como opção
- `<img src="../localArquivo" alt="id" width="250px"/>` Buscar imagem dentro de um local no projeto
- `<a href="https://linkDoLocalOnline.com"> <img src="../localArquivo" alt="sorvete" width="250px"> </a>` Vamos pegar um link online e agregar a um arquivo que estamos usando no projeto
- Para criar um link ancora:

```
    <a href="#ancora" id="ancora02"> clique aqui 01 </a>

    <a href="#ancora02"> <img id="ancora" src="../localDaImagem"/> clique aqui 02 </a>

<!-- Quando clicamos no link "clique aqui 01" vamos ser jogados diretamente ao "id='ancora'" e quando clicarmos no
"clique aqui 02" vamos ser levamos até o " id='ancora02'"-->
```

### TRABALHANDO COM LISTAS

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

### TRABALHANDO COM TABELA

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

### TRABALHANDO COM FORMULÁRIOS

<p>Primeiro devemos definir o metodo de envio, sendo "GET" ou "POST" e depois adicionar a action.</p>
<p> "action" nada mais é do que o local onde identificamos o link para onde será enviado as informações do "form". Se os dados serão enviados para o mesmo domínio vamos colocar apenas "/loca" se for em outro domínio precisaremos colocar o endereço completo. <br /> *ex1:* "http://programadorbr.com.br/cadastro" (para outro dominio)<br/> 
*ex2:* "/cadastro" (para o próprio dominio) </p>

#### Método "get"

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

<p>Com o método "post" todas informções serão escondidas. Vamos usar sempre em campo de login.</p>

```
<form method="post" action="/localDoDominio">
    <input id="email" type="text" name="email" />
    <input id="name" type="text" name="name" />
    <input type="submit" />
</form>
<!-- Toda a informação digitada nos campos serão omitidas para os usuários -->
```

#### Tipos de input

input <b>"type: text"</b> para usar com texto

```
    <form method="get" action="https://www.youtube.com/results?">
      <input id="" type="text" name="search_query" placeholder="digite aqui" />
      <input type="submit" />
    </form>
```

input <b>"type: password"</b> deixa todo pontilhado e é usado com metodo "post"

```
    <form method="post" action="/localDomínio">
      <input id="" type="password" name="senha" placeholder="senha" />
      <input type="submit" />
    </form>
```

input <b>"type: email"</b> para identificar se é um email ou não

```
    <form method="post" action="/localDomínio">
      <input id="" type="password" name="senha" placeholder="email" />
      <input type="submit" />
    </form>
```

input <b>"type: checkbox"</b> cria uma checkbox, onde vemos identificar cada um com um valor para quando o item for selecionado o backend entende o que foi atribuido na seleção.

```
<"-- Com "checkbox" podemos selecionar mais de um iten -->
    <form method="get" action="/localDomínio">
      <input id="" type="checkbox" name="curso" value="op1" /> React Native <br />
      <input id="" type="checkbox" name="curso" value="op2" /> React Js  <br />
      <input type="submit" />
    </form>
```

input <b>"type: radio"</b> cria uma caixa de seleção igual o checkbox, onde vemos identificar cada um com um valor para quando o item for selecionado o backend entende o que foi atribuido na seleção. Com "radio" podemos selecionar apenas 1 item por vez e se usar "checked" já vamos deixar um iten selecionado automaticamente.

```
    <form method="get" action="/localDomínio">
      <input id="" type="radio" name="genero" value="masc" checked /> Masculino <br />
      <input id="" type="radio" name="genero" value="fem" /> Feminino <br />
      <input type="submit" />
    </form>
```

input <b>"type: reset"</b> para resetar todos os campos preenchidos e voltar ao formato padrão do formulário.

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

## 🚧 _Projeto EM CONSTRUÇÃO_ 🚧
