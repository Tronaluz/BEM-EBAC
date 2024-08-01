
<h1>Projeto de Melhoria de CSS com Metodologia BEM</h1>

<p>Este projeto tem como objetivo a aplicação da metodologia BEM (Block, Element, Modifier) para a estruturação de classes CSS em um documento HTML.</p>

<h2>Objetivo</h2>
<ul>
    <li>Atualizar as classes do HTML utilizando a metodologia BEM.</li>
    <li>Transcrever os estilos para CSS utilizando a estrutura BEM.</li>
    <li>Incluir os arquivos correspondentes no repositório, caso tenha utilizado algum pré-processador (SASS ou LESS).</li>
</ul>

<h2>Estrutura do Projeto</h2>
<div class="project-structure">
<pre><code>projeto/
├── css/
│   ├── estilo.css          # Arquivo CSS transcrito utilizando BEM
│   ├── estilo.scss         # Arquivo SASS (se utilizado)
│   └── estilo.less         # Arquivo LESS (se utilizado)
├── index.html              # Arquivo HTML com classes atualizadas para BEM
└── README.md               # Este arquivo
</code></pre>
</div>

<h2>Como Usar</h2>
<ol>
    <li><b>Clonar o Repositório:</b>
        <pre><code>git clone https://github.com/seu_usuario/seu_repositorio.git
cd seu_repositorio
</code></pre>
    </li>
    <li><b>Trocar para a Branch de Boas Práticas CSS:</b>
        <pre><code>git checkout boas_praticas_css
</code></pre>
    </li>
    <li><b>Abrir o HTML no Navegador:</b>
        <p>Abra o arquivo <code>index.html</code> no seu navegador para visualizar a página com as classes BEM aplicadas.</p>
    </li>
</ol>

<h2>Tecnologias Utilizadas</h2>
<ul>
    <li>HTML5</li>
    <li>CSS3</li>
    <li>SASS (opcional)</li>
    <li>LESS (opcional)</li>
</ul>

<h2>Contribuição</h2>
<p>Contribuições são bem-vindas! Sinta-se à vontade para abrir uma <i>issue</i> ou enviar um <i>pull request</i>.</p>

<h2>Licença</h2>
<p>Este projeto está licenciado sob a <a href="LICENSE">MIT License</a>.</p>

<h2>Exemplo de Classes BEM</h2>

<h3>HTML Original</h3>
<pre><code>&lt;div class="header"&gt;
  &lt;div class="logo"&gt;Logo&lt;/div&gt;
  &lt;nav class="navigation"&gt;
    &lt;ul class="nav-list"&gt;
      &lt;li class="nav-item"&gt;&lt;a href="#"&gt;Home&lt;/a&gt;&lt;/li&gt;
      &lt;li class="nav-item"&gt;&lt;a href="#"&gt;About&lt;/a&gt;&lt;/li&gt;
    &lt;/ul&gt;
  &lt;/nav&gt;
&lt;/div&gt;
</code></pre>

<h3>HTML com BEM</h3>
<pre><code>&lt;div class="header"&gt;
  &lt;div class="header__logo"&gt;Logo&lt;/div&gt;
  &lt;nav class="header__navigation"&gt;
    &lt;ul class="header__nav-list"&gt;
      &lt;li class="header__nav-item"&gt;&lt;a href="#"&gt;Home&lt;/a&gt;&lt;/li&gt;
      &lt;li class="header__nav-item"&gt;&lt;a href="#"&gt;About&lt;/a&gt;&lt;/li&gt;
    &lt;/ul&gt;
  &lt;/nav&gt;
&lt;/div&gt;
</code></pre>

<h3>CSS com BEM</h3>
<pre><code>.header {
  /* estilos para o bloco header */
}

.header__logo {
  /* estilos para o elemento logo dentro do bloco header */
}

.header__navigation {
  /* estilos para o elemento navigation dentro do bloco header */
}

.header__nav-list {
  /* estilos para o elemento nav-list dentro do bloco header */
}

.header__nav-item {
  /* estilos para o elemento nav-item dentro do bloco header */
}
</code></pre>

</body>
</html>
