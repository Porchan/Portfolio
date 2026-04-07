# FrameCut Studio — Portfólio

Portfólio de edição de vídeo pronto para publicar no **GitHub Pages**.

## 📁 Estrutura de arquivos

```
framecut/
├── index.html            ← página principal
├── assets/
│   ├── css/
│   │   └── style.css     ← todos os estilos
│   └── js/
│       └── main.js       ← traduções, portfólio e animações
└── README.md
```

## 🚀 Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex: `portfolio`)
2. Suba **todos os arquivos e pastas** mantendo a estrutura acima
3. Vá em **Settings → Pages**
4. Em **Source**, selecione `Deploy from a branch`
5. Escolha `main` e pasta `/ (root)` → clique **Save**
6. Aguarde 1-2 minutos — seu site estará em:

```
https://SEU_USUARIO.github.io/portfolio/
```

## ✏️ Personalizações

| O que mudar | Onde |
|---|---|
| Nome/marca | `index.html` — busque `FrameCut` |
| Email e WhatsApp | `index.html` — seção `CONTACT` |
| Redes sociais | `index.html` — `<footer>` |
| Projetos do portfólio | `assets/js/main.js` — array `PROJECTS` |
| Cores | `assets/css/style.css` — variáveis no `:root` |
