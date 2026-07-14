# Mapa Mental da Umbanda — Quiz

Quiz interativo (funil de low ticket) para o produto **App Mapa Mental da Umbanda**.

Página única, sem build: é só `index.html` com HTML, CSS e JS embutidos. Pronta para deploy estático (Vercel, Netlify, etc.).

## Deploy na Vercel
1. Importe este repositório na Vercel.
2. Framework Preset: **Other** (site estático, sem build).
3. A Vercel serve o `index.html` na raiz automaticamente.

## Antes de publicar de verdade
Edite o topo do `index.html`, no bloco `QUIZ_CONFIG`:
- `CHECKOUT`: seu link de afiliado (checkout).
- `FB_PIXEL_ID`: seu Pixel do Facebook (opcional).
- `CLARITY_ID`: seu Microsoft Clarity (opcional).

E substitua os depoimentos marcados com "Depoimento · substituir" por depoimentos reais.

> Observação: por enquanto as imagens, os vídeos e a música de fundo carregam do CDN de origem. Para deixar o quiz 100% independente, baixe esses arquivos para dentro do repositório e ajuste os caminhos.
