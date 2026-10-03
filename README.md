# Dio_Desafio-01_Forma-o-HTML-Web-Developer-
Formação HTML Web Developer - Desafio 01 - Criar pagina com TAG utilizada durante as Aulas.

_______________________________________________________________________________________________________________________

Projeto de aprendizagem ativa com NotebookLM

Autor: Washington Pires




<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>Guia de Tags HTML</title>
</head>
<body id="topo">

    <!-- ÍNDICE -->
    <h1>Índice de Tags HTML</h1>
    <p>Selecione uma tag abaixo para ver a explicação:</p>
    <ul>
        <li><a href="#h1">h1</a></li>
        <li><a href="#h2">h2</a></li>
        <li><a href="#h3">h3</a></li>
        <li><a href="#h4">h4</a></li>
        <li><a href="#h5">h5</a></li>
        <li><a href="#h6">h6</a></li>
        <li><a href="#p">p</a></li>
        <li><a href="#mark">mark</a></li>
        <li><a href="#small">small</a></li>
        <li><a href="#i">i</a></li>
        <li><a href="#u">u</a></li>
        <li><a href="#strong">strong</a></li>
        <li><a href="#ol">ol</a></li>
        <li><a href="#ul">ul</a></li>
        <li><a href="#li">li</a></li>
        <li><a href="#a">a</a></li>
        <li><a href="#hr">hr</a></li>
        <li><a href="#sub">sub</a></li>
        <li><a href="#sup">sup</a></li>
        <li><a href="#blockquote">blockquote</a></li>
        <li><a href="#font">font</a></li>
        <li><a href="#del">del</a></li>
        <li><a href="#abbr">abbr</a></li>
    </ul>

    <hr>

    <!-- H1 -->
    <h2 id="h1">&lt;h1&gt; a &lt;h6&gt;</h2>
    <p>As tags de heading (título) definem a hierarquia de títulos na página. <strong>&lt;h1&gt;</strong> é o título principal e <strong>&lt;h6&gt;</strong> é o de menor importância. Cada nível representa um grau de importância.</p>
    <p>Exemplo:</p>
    <h1>Título Nível 1</h1>
    <h2>Título Nível 2</h2>
    <h3>Título Nível 3</h3>
    <h4>Título Nível 4</h4>
    <h5>Título Nível 5</h5>
    <h6>Título Nível 6</h6>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/h1">Referência MDN - h1</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- P -->
    <h2 id="p">&lt;p&gt;</h2>
    <p>A tag <strong>&lt;p&gt;</strong> define um parágrafo. Ela agrupa linhas de texto e insere espaços verticais antes e depois do conteúdo, separando blocos de texto de forma semântica.</p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/p">Referência MDN - p</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- MARK -->
    <h2 id="mark">&lt;mark&gt;</h2>
    <p>A tag <strong>&lt;mark&gt;</strong> destaca um trecho de texto como relevante, semelhante a um marca-texto. O navegador geralmente exibe o texto com um fundo amarelo.</p>
    <p>Exemplo: <mark>Este texto está destacado com a tag mark.</mark></p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/mark">Referência MDN - mark</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- SMALL -->
    <h2 id="small">&lt;small&gt;</h2>
    <p>A tag <strong>&lt;small&gt;</strong> representa texto em menor tamanho, usado para letras miúdas, avisos ou menções legais. Não altera a importância semântica do conteúdo.</p>
    <p>Exemplo: <small>Este texto aparece em tamanho reduzido.</small></p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/small">Referência MDN - small</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- I -->
    <h2 id="i">&lt;i&gt;</h2>
    <p>A tag <strong>&lt;i&gt;</strong> representa texto em itálico, usado para termos técnicos, expressões estrangeiras, pensamentos ou ênfase estilística sem implicar importância.</p>
    <p>Exemplo: <i>Este texto está em itálico.</i></p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/i">Referência MDN - i</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- U -->
    <h2 id="u">&lt;u&gt;</h2>
    <p>A tag <strong>&lt;u&gt;</strong> aplica um sublinhado não decorativo a texto. É usada para indicar que o texto tem uma razão não estilística, como erros ortográficos ou palavras em chinês.</p>
    <p>Exemplo: <u>Este texto está sublinhado.</u></p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/u">Referência MDN - u</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- STRONG -->
    <h2 id="strong">&lt;strong&gt;</h2>
    <p>A tag <strong>&lt;strong&gt;</strong> indica que o texto tem importância, seriedade ou urgência. O navegador o exibe em negrito por padrão, mas o foco é semântico (acessibilidade e SEO).</p>
    <p>Exemplo: <strong>Este texto tem importância forte.</strong></p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/strong">Referência MDN - strong</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- OL -->
    <h2 id="ol">&lt;ol&gt;</h2>
    <p>A tag <strong>&lt;ol&gt;</strong> (ordered list) cria uma lista ordenada, onde os itens são numerados automaticamente (1, 2, 3...). Útil para sequências, rankings ou passos.</p>
    <p>Exemplo:</p>
    <ol>
        <li>Primeiro item</li>
        <li>Segundo item</li>
        <li>Terceiro item</li>
    </ol>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/ol">Referência MDN - ol</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- UL -->
    <h2 id="ul">&lt;ul&gt;</h2>
    <p>A tag <strong>&lt;ul&gt;</strong> (unordered list) cria uma lista não ordenada, onde os itens aparecem com marcadores (bullet points). Útil para listas sem sequência definida.</p>
    <p>Exemplo:</p>
    <ul>
        <li>Item A</li>
        <li>Item B</li>
        <li>Item C</li>
    </ul>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/ul">Referência MDN - ul</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- LI -->
    <h2 id="li">&lt;li&gt;</h2>
    <p>A tag <strong>&lt;li&gt;</strong> (list item) representa um item individual dentro de uma lista (<strong>&lt;ol&gt;</strong> ou <strong>&lt;ul&gt;</strong>). É obrigatória para compor qualquer lista.</p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/li">Referência MDN - li</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- A -->
    <h2 id="a">&lt;a&gt;</h2>
    <p>A tag <strong>&lt;a&gt;</strong> (anchor) cria hiperlinks para outras páginas, seções da mesma página (âncoras), e-mails ou downloads. O atributo <strong>href</strong> define o destino do link.</p>
    <p>Exemplo: <a href="https://www.w3schools.com/html/">Visite a W3Schools</a></p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/a">Referência MDN - a</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- HR -->
    <h2 id="hr">&lt;hr&gt;</h2>
    <p>A tag <strong>&lt;hr&gt;</strong> insere uma linha horizontal (divisor temático) no conteúdo. É uma tag de fechamento único (auto-fechante) e indica uma mudança de tema na seção.</p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/hr">Referência MDN - hr</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- SUB -->
    <h2 id="sub">&lt;sub&gt;</h2>
    <p>A tag <strong>&lt;sub&gt;</strong> exibe o texto como subscrito (abaixo da linha base). Comum em fórmulas químicas como H<sub>2</sub>O.</p>
    <p>Exemplo: H<sub>2</sub>O</p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/sub">Referência MDN - sub</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- SUP -->
    <h2 id="sup">&lt;sup&gt;</h2>
    <p>A tag <strong>&lt;sup&gt;</strong> exibe o texto como sobrescrito (acima da linha base). Comum em expoentes matemáticos como x<sup>2</sup>.</p>
    <p>Exemplo: x<sup>2</sup> = 4</p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/sup">Referência MDN - sup</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- BLOCKQUOTE -->
    <h2 id="blockquote">&lt;blockquote&gt;</h2>
    <p>A tag <strong>&lt;blockquote&gt;</strong> indica que o conteúdo é uma citação extensa de outra fonte. O navegador aplica margens laterais por padrão. Pode ser usada com o atributo <strong>cite</strong> para indicar a origem.</p>
    <p>Exemplo:</p>
    <blockquote cite="https://www.w3.org/">
        A World Wide Web is a vast information space in which the resources are identified by URIs.
    </blockquote>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/blockquote">Referência MDN - blockquote</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- FONT -->
    <h2 id="font">&lt;font&gt;</h2>
    <p>A tag <strong>&lt;font&gt;</strong> é uma tag <mark>obsoleta</mark> (descontinuada no HTML5) que controlava cor, tamanho e família da fonte via atributos. Hoje em dia, use CSS no lugar. Mantida aqui apenas para fins de estudo.</p>
    <p>Exemplo (obsoleto): <font color="red" size="5">Texto em vermelho e grande</font></p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/font">Referência MDN - font</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- DEL -->
    <h2 id="del">&lt;del&gt;</h2>
    <p>A tag <strong>&lt;del&gt;</strong> indica texto que foi <em>removido</em> ou editado (exibido com linha de strikethrough). É semântica e pode indicar a data da edição com o atributo <strong>datetime</strong>.</p>
    <p>Exemplo: <del>Preço antigo: R$ 99,90</del></p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/del">Referência MDN - del</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <!-- ABBR -->
    <h2 id="abbr">&lt;abbr&gt;</h2>
    <p>A tag <strong>&lt;abbr&gt;</strong> representa uma abreviação ou sigla. Ao passar o mouse, o navegador exibe a forma completa (definida no atributo <strong>title</strong>) como tooltip.</p>
    <p>Exemplo: <abbr title="HyperText Markup Language">HTML</abbr> é a linguagem de marcação da web.</p>
    <p>📎 <a href="https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/abbr">Referência MDN - abbr</a></p>
    <p><a href="#topo">voltar</a> ao índice</p>

    <hr>

    <p><small>&copy; 2026 - Projeto de estudo - Tags HTML Básicas</small></p>

</body>
</html>   
