# FrameCut Studio — Portfólio

Portfólio pessoal de edição de vídeo, construído com HTML, CSS e JavaScript puro. Pronto para publicar no GitHub Pages.

## 📁 Estrutura

```
framecut-portfolio/
├── index.html              ← Página principal
├── assets/
│   ├── css/
│   │   └── style.css       ← Todos os estilos
│   └── js/
│       └── main.js         ← Traduções, animações e lógica
└── README.md
```

## 🚀 Como publicar no GitHub Pages

1. Crie um repositório no GitHub (ex: `meu-portfolio`)
2. Faça upload de todos os arquivos para a branch `main`
3. Vá em **Settings → Pages**
4. Em **Source**, selecione `Deploy from a branch`
5. Escolha a branch `main` e a pasta `/ (root)`
6. Clique em **Save**

Seu site estará disponível em:
`https://SEU_USUARIO.github.io/meu-portfolio/`

## ✏️ Personalizações principais

### Trocar nome/marca
Em `index.html`, busque por `FrameCut` e substitua pelo seu nome ou marca.

### Atualizar contato
Em `index.html`, seção `CONTACT`, atualize:
- Email
- WhatsApp
- Localização

### Adicionar projetos reais
Em `assets/js/main.js`, encontre o array `projects` e substitua os itens com seus projetos reais.

### Atualizar links das redes sociais
Em `index.html`, no `<footer>`, substitua os `href="#"` pelos links das suas redes.

## 🎨 Tecnologias
- HTML5 semântico
- CSS3 com variáveis customizadas
- JavaScript vanilla (sem frameworks)
- Google Fonts: Cormorant Garamond + Plus Jakarta Sans
- Suporte a PT-BR e EN com troca dinâmica de idioma
