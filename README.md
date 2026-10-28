# portal-rolante

Portal de entrada dos projetos sobre Rolante/RS, para `rolanters.com.br`. Site estático (HTML + CSS), sem build nem backend.

## Rodar local

```bash
npx serve .
```

## Adicionar um produto

1. Copiar os SVGs `mark.svg` e `mark-dark.svg` da marca (em `identidade-rolante/marca/<slug>/assets/`) para `assets/<slug>/`.
2. Copiar um bloco `<a class="cartao">` em `index.html` e trocar slug, nome, subdomínio e descrição.

## Tema

Claro/escuro via `data-theme` no `<html>`, escolhido por um script inline no `<head>` (antes da primeira pintura). A escolha fica em `localStorage['rolanters-theme']`. No mobile (< 640px) o tema é sempre escuro e o botão some.

## Marca

Segue o Sistema de Marcas Rolante (repo `identidade-rolante`): uma cor de acento, Inter, sem sombras nem gradientes, cartões com raio 14 e borda 1px. O portal não tem símbolo nem favicon próprios, por decisão.

## Publicação

Ainda não publicada. Quando for: GitHub Pages pela branch `main` (raiz) e arquivo `CNAME` com `rolanters.com.br`.
