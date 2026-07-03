# Portfolio — Inês Lopes Costa

Site de portfolio pessoal para Inês Lopes Costa, profissional de comunicação corporativa e marketing digital.

## Tecnologias

- HTML5 semântico
- CSS3 (custom properties, grid, flexbox, animações)
- JavaScript vanilla (Intersection Observer, sem dependências)
- Google Fonts (Playfair Display + Inter)

## Deploy — GitHub Pages

1. Push este repositório para o GitHub
2. Ir a **Settings → Pages**
3. Selecionar **Source: Deploy from a branch**
4. Selecionar **Branch: main** (ou `master`), pasta **/ (root)**
5. O site ficará disponível em `https://<username>.github.io/<repo-name>/`

## Personalização

### Alterar a foto de perfil
Substituir `profile-picture.png` na raiz do projeto. A imagem pode ter qualquer dimensão — o CSS usa `object-fit: cover` para adaptar automaticamente.

### Alterar conteúdos
Editar diretamente o `index.html`. O conteúdo está organizado por secções com comentários claros.

## Estrutura

```
├── index.html              ← Página principal
├── css/
│   └── style.css           ← Design system e estilos
├── js/
│   └── main.js             ← Interações e animações
├── profile-picture.png     ← Foto de perfil
└── README.md
```
