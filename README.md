# Contagem regressiva — Círio Musical 2026, Banda CAJU

Miniaplicativo estático gratuito para GitHub Pages, com foto oficial e botão de compartilhamento no WhatsApp.

## Antes de publicar (IMPORTANTE)

O cartaz informa **19 de outubro de 2026**, mas não apresenta horário de início. Em `index.html`, encontre:

```js
const SHOW_AT = '2026-10-19T20:00:00-03:00';
```

**20:00 é apenas um horário provisório**. Substitua pelo horário correto, mantendo o fuso `-03:00` (Belém).

## Publicar no GitHub Pages

1. Crie um repositório público, por exemplo `cirio-musical-2026`.
2. Envie `index.html` e `cartaz-caju.jpg` para a raiz do repositório.
3. Abra Settings → Pages → Build and deployment → Deploy from a branch.
4. Selecione `main` e `/ (root)` e salve.
5. Aguarde a publicação. Seu link será `https://SEU_USUARIO.github.io/cirio-musical-2026/`.
6. Abra o endereço em um celular e teste o botão **Compartilhar no WhatsApp**.

## Limitação do WhatsApp

O relógio funciona no navegador aberto pelo link, **não como popup ativo dentro do WhatsApp ou story**. O preview do link pode exibir imagem estática após o site estar publicado e com URL de imagem absoluta em `og:image`.
