# All My Links (Rafael) – Static + Tailwind CDN

Site 100% estático (apenas HTML). Estilos com Tailwind via CDN. Ideal para GitHub Pages.

## Editar

- Troque sua foto em `assets/avatar.jpg` (ou use `assets/avatar.svg`).
- Edite os textos/links diretamente em `index.html`.

## Rodar local

Abra `index.html` no navegador. Não há build.

## Deploy com GitHub Pages (CI já incluso)

1. Crie um repositório e envie os arquivos (branch `main`).
2. Vá em Settings → Pages → Source: "GitHub Actions".
3. A cada push na `main`, o workflow `.github/workflows/gh-pages.yml` publica o site.

Pronto. Também funciona em Netlify, Vercel, Cloudflare Pages, etc.
