# REAAT – Landing Page

Landing page da **Rede de Educação Ambiental do Alto Tietê (REAAT)**.

Página estática (HTML + Tailwind via CDN + Google Fonts). Não precisa de build.

## Estrutura

```
index.html      página completa
assets/logo.png     símbolo da REAAT (PNG transparente)
assets/favicon.png  ícone da aba do navegador
```

## Rodar localmente

Abra o `index.html` no navegador, ou sirva a pasta:

```bash
python3 -m http.server 8000
```

## Publicar no GitHub Pages

1. Repositório → **Settings → Pages**
2. *Source*: **Deploy from a branch** → `main` / `(root)`
3. O site fica em `https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/`

## Pendências

- Trocar os placeholders de foto por imagens reais (nascente, educadores, ações, especialistas).
- Preencher nomes e biografias dos especialistas.
- Trocar os links `#` (LinkedIn, Instagram, WhatsApp, artigos) pelos reais.
- Conectar o formulário de contato a um serviço de envio (hoje só valida no navegador).
