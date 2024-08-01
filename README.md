# Projeto de Melhoria de CSS com Metodologia BEM

Este projeto tem como objetivo a aplicação da metodologia BEM (Block, Element, Modifier) para a estruturação de classes CSS em um documento HTML.

## Objetivo

- Atualizar as classes do HTML utilizando a metodologia BEM.
- Transcrever os estilos para CSS utilizando a estrutura BEM.
- Incluir os arquivos correspondentes no repositório, caso tenha utilizado algum pré-processador (SASS ou LESS).

## Estrutura do Projeto

A estrutura do projeto segue a seguinte organização:

projeto/
├── css/
│ ├── estilo.css # Arquivo CSS transcrito utilizando BEM
│ ├── estilo.scss # Arquivo SASS (se utilizado)
│ └── estilo.less # Arquivo LESS (se utilizado)
├── index.html # Arquivo HTML com classes atualizadas para BEM
└── README.md # Este arquivo


## Como Usar

1. **Clonar o Repositório:**
   ```bash
   git clone https://github.com/seu_usuario/seu_repositorio.git
   cd seu_repositorio

Trocar para a Branch de Boas Práticas CSS:
git checkout boas_praticas_css

Abrir o HTML no Navegador:

Abra o arquivo index.html no seu navegador para visualizar a página com as classes BEM aplicadas.

Memória atualizada
Claro, vou ajustar o README para remover as partes que mencionam as etapas específicas do curso. Aqui está o README atualizado:

markdown
Copiar código
# Projeto de Melhoria de CSS com Metodologia BEM

Este projeto tem como objetivo a aplicação da metodologia BEM (Block, Element, Modifier) para a estruturação de classes CSS em um documento HTML.

## Objetivo

- Atualizar as classes do HTML utilizando a metodologia BEM.
- Transcrever os estilos para CSS utilizando a estrutura BEM.
- Incluir os arquivos correspondentes no repositório, caso tenha utilizado algum pré-processador (SASS ou LESS).

## Estrutura do Projeto

A estrutura do projeto segue a seguinte organização:

projeto/
├── css/
│ ├── estilo.css # Arquivo CSS transcrito utilizando BEM
│ ├── estilo.scss # Arquivo SASS (se utilizado)
│ └── estilo.less # Arquivo LESS (se utilizado)
├── index.html # Arquivo HTML com classes atualizadas para BEM
└── README.md # Este arquivo

bash
Copiar código

## Como Usar

1. **Clonar o Repositório:**
   ```bash
   git clone https://github.com/seu_usuario/seu_repositorio.git
   cd seu_repositorio
Trocar para a Branch de Boas Práticas CSS:

bash
Copiar código
git checkout boas_praticas_css
Abrir o HTML no Navegador:

Abra o arquivo index.html no seu navegador para visualizar a página com as classes BEM aplicadas.
Tecnologias Utilizadas
HTML5
CSS3
SASS (opcional)
LESS (opcional)
Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir uma issue ou enviar um pull request.

Licença
Este projeto está licenciado sob a MIT License.

HTML Original
<div class="header">
  <div class="logo">Logo</div>
  <nav class="navigation">
    <ul class="nav-list">
      <li class="nav-item"><a href="#">Home</a></li>
      <li class="nav-item"><a href="#">About</a></li>
    </ul>
  </nav>
</div>

HTML com BEM
<div class="header">
  <div class="header__logo">Logo</div>
  <nav class="header__navigation">
    <ul class="header__nav-list">
      <li class="header__nav-item"><a href="#">Home</a></li>
      <li class="header__nav-item"><a href="#">About</a></li>
    </ul>
  </nav>
</div>

CSS com BEM
.header {
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
