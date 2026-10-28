# MindUp — site

Página de contato da MindUp (link da bio do Instagram). Arquivo único, sem dependências: é só subir `index.html` e `favicon.svg`.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (ex.: `mindup`).
2. Envie os arquivos `index.html` e `favicon.svg` para o repositório.
3. No repositório, vá em **Settings → Pages**.
4. Em **Source**, escolha **Deploy from a branch**, branch `main`, pasta `/ (root)` e clique em **Save**.
5. Em 1 ou 2 minutos o site fica no ar em `https://SEU-USUARIO.github.io/mindup/`.
6. Coloque esse link na bio do Instagram.

## WhatsApp

No fim do `index.html`, dentro do `<script>`:

```js
const WHATSAPP = "559884097838";   // 55 + DDD + número, só dígitos
const BASE = "Olá! Vim pelo Instagram da MindUp e gostaria de saber mais sobre os serviços.";
```

- Os botões gerais usam a mensagem `BASE`.
- Os cartões de formato mandam "...gostaria de saber mais sobre **Slides animados**." (o nome vem do atributo `data-wa` de cada cartão).
