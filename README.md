# Site-Creatures — GitHub Pages

Esta versão foi convertida de Django para um site estático compatível com GitHub Pages.

## Publicar

1. Copie o conteúdo desta pasta para o repositório `xChrisRVx/Site-Creatures`.
2. Faça commit e push para a branch `main`.
3. No GitHub, abra **Settings → Pages**.
4. Em **Build and deployment**, escolha **Deploy from a branch**.
5. Selecione `main` e `/ (root)` e clique em **Save**.
6. Aguarde alguns minutos. O endereço esperado é:
   `https://xChrisRVx.github.io/Site-Creatures/`

## Imagens

O ZIP original enviado para esta conversão não continha as imagens/CSS/JS que os templates Django referenciavam. Por isso, esta versão usa cards visuais gerados em CSS. Se você tiver as imagens originais, coloque-as em `assets/` e podemos substituir os cards pelos GIFs reais.

## Estrutura

- `index.html`: escolha de idioma
- `br.html`: versão em português
- `en.html`: versão em inglês
- `css/style.css`: visual responsivo
- `js/script.js`: busca, contagem e tema escuro/claro
- `.nojekyll`: evita processamento Jekyll
