# Portfólio — Matthäus de Paula

Portfólio pessoal em HTML/CSS/JS puro, apresentando experiência em automação de dados fiscais
(Python, SQL Server, PowerShell) e formação em Engenharia de Software.

## Estrutura

- `index.html` — conteúdo do site
- `style.css` — estilos
- `script.js` — menu mobile e ano dinâmico no rodapé
- `imagens/` — foto de perfil

## Rodar localmente

Abra `index.html` diretamente no navegador, ou sirva com um servidor simples:

```bash
python3 -m http.server
```

## Deploy

Publicado via GitHub Pages pelo workflow `.github/workflows/deploy.yml`, que roda a cada push
na `main` e também pode ser disparado manualmente (aba Actions → Deploy to GitHub Pages →
Run workflow).

Para isso funcionar, em **Settings → Pages** o campo **Source** precisa estar como
**GitHub Actions**.
