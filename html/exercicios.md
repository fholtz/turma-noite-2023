<details>
<summary>Aula 11 - dia 18 de Abril: Listas e exercício em sala</summary>

- 01
  - Criar uma pasta com o nome de exercicios_html (dentro da sua pasta com seu nome).
  - Dentro dessa pasta, criar um arquivo principal com o nome de index.html
  - Na página index deve conter um título, os módulos do curso de programação (informática básica, html, css, javascript, php, sql)
  - Inserir um texto simples, com o propósito do curso.
- 02
  - Na mesma pasta dos exercícios de HTML, criar 1 arquivo para cada módulo listado.
  - Para cada novo arquivo, deve ter uma breve descrição sobre o módulo (pesquisar na internet)
  - Na página principal, deve ter um link para cada módulo, que leve para o arquivo do módulo do curso. Exemplo:
    - No index.html terá um link css, ao clicar nesse link, precisa abrir uma nova página que você criou, chamado modulo_css.html
- 03
  - Organizar todo o código, com identação correta.
  - Inserir uma lista de cada, já estudada, em alguma página criada. (a critério do aluno)
  - Organizar as páginas com as tags semânticas corretas. 
    - Exemplo:
      - rodapé - footer;
      - Cabeçalho - header;
      - Título - H1
</details>
<details>
<summary>Aula 11 - Apoio para Exercío em sala</summary>

- Utilizar no exercício
## Tags Semânticas
~~~
  - H1, h2 … h6         => Tag de título
  - <header></header>   => Define o cabeçalho
  - <main></main>       => Define o conteúdo principal da página
  - <footer></footer>   => Rodapé
  - <section></section> => Define seção genérica da pg
  - <article></article> => Define conteúdo independente
  - <aside></aside>     => Define algo relacionado
  - <nav></nav>         => Define a navegação principal
  - <ol></ol>           => Lista ordenada
  - <ul></ul>           => Lista não ordenada
  - <li></li>           => Elementos da lista
  - <p></p>             => Define parágrafo
  - <a></a>             => Define ancoras 
  - <details></details> => Detalhes adicionais
  - <summary></summary> => Utilizada no details
  - <address></address> => Informações de contato
~~~
## Tags SEM Semântica
~~~
  - <span></span>     => Genérica para texto
  - <br>              => Pula linha
  - <hr>              => Uma separação
  - <i></i>           => destaca uma parte do texto
  - <strong></strong> => negrita parte do texto
~~~
## Tags de Mídia
~~~
 - <progress></progress>
 - <audio></audio>
 - <video></video>
 - <source>
 - <img>
~~~
## Atributos
~~~
- href=””
 - Target=””
 - src=””
 - controls
 - id=””
 - class=””
 - value=””
 - max=””
~~~
</details>

<details>
<summary>Exercício Aula dia 25 de Abril: Listas e exercício em sala</summary>

- 01
  - Criar uma um link, na página principal, que leve para uma nova página que você irá criar agora, com o nome tabela.html
  - Nessa página, crie um título com o nome ‘Lista de Alunos do curso de programação’
  - Crie uma tabela com 'Nome', 'exercício', 'data de início', 'data prevista entrega'
    - Onde no nome, precisa ter o nome do aluno que está fazendo o exercício. Caso seja uma dupla, precisa ser uma célula mesclada
    - Data de início, será a data de hoje.
    - Data prevista, a data da próxima aula.
    - 
- 02
  - Após criado a tabela com todos os alunos, deixar o seu nome, um link clicável, e redirecionar para outra página, com o nome detalhes_aluno.html
  - Nessa nova página, terá uma nova tabela com algumas informações sobre você ou a dupla.
  - Informações básicas:
    - Nome, email, nome github, idade
  - Caso esteja fazendo em dupla, faça 2 tabelas, 1 para cada aluno.
  - 
- 03  Desafio
  - Colocar estilização na tabela (cores);
</details>

<details>
<summary>Exercício Aula dia 25 de Abril - Apoio para Exercío em sala</summary>
## Tags

~~~
  - <thead></thead> => (table header) Esta tag representa o cabeçalho da tabela, geralmente composta por células título;
  - <tr></tr>       => (table row) tag define uma linha em uma tabela HTML;
  - <td></td>       => (table data) tag define uma célula normal em uma tabela HTML;
  - <tbody></tbody> => (table body) Essa tag representa o corpo da tabela;
  - <tfoot></tfoot> => (table footer) Essa tag representa o rodapé da tabela;
~~~

## Atributos

~~~
  - colspan => mesclagem de colunas;
  - rowspan => Mesclagem de linhas;
~~~

## Desafio

~~~
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <style>
    table {
        border-collapse: collapse;
        background: #FFFFF0;

    td {
        border: 1px solid black;

    th {
        border: 1px solid black;
        background: #F0FFF0;
    }
  </style>
</head>
~~~
</details>