# Portfólio — Márcio Gomes (2022)

Meu primeiro portfólio pessoal, feito em julho de 2022 quando eu estava começando no Front-End: uma página única em HTML com estilos escritos em SCSS (Sass).

> 📦 **Projeto de estudo — não recebe mais atualizações.**
> A versão atual do portfólio está em [portfolio-marcio-gomes](https://github.com/marcio-sgomes/portfolio-marcio-gomes) (publicada em <https://portfolio-marcio-gomes.vercel.app>).

🌐 Versão publicada deste estudo: <https://marcio-sgomes.github.io/portifolio/> (GitHub Pages, branch `master`) e <https://portifolio-bay.vercel.app>.

## O que tem aqui

Página de rolagem única com menu de navegação por âncoras e as seções:
**home** (banner), **pitch** (vídeo do YouTube), **about**, **project** (projetos de exemplo), **curriculum** (CV em PDF embutido) e **contact**, além de um rodapé com ícones de redes sociais.

## Tecnologias

- HTML5
- SCSS (Sass) organizado em parciais (`_banner.scss`, `_about.scss`...) e compilado para `assets/css/style.css`
- Live Server (extensão do VS Code) para desenvolvimento

## Estrutura

```text
index.html          # página única
assets/
├── sass/           # código-fonte dos estilos (style.scss importa as parciais)
├── css/            # CSS compilado usado pela página (não edite à mão)
├── img/            # fotos, ícones e imagens dos projetos
└── files/          # currículo em PDF
```

## Como abrir

1. Clone o repositório: `git clone https://github.com/marcio-sgomes/portifolio.git`
2. Abra o `index.html` no navegador — ou, no VS Code, clique com o botão direito no arquivo e escolha **Open with Live Server** (porta 5501).
3. Para alterar os estilos, edite os arquivos em `assets/sass/` e recompile, por exemplo:
   ```bash
   npx sass assets/sass/style.scss assets/css/style.css
   ```
