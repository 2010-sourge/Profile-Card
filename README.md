
# 👤 Profile Card UI — HTML & CSS

Um componente de **cartão de perfil** elegante e responsivo, construído com **HTML e CSS puro**. Ideal para páginas de apresentação, portfólios ou perfis de criadores de conteúdo.

---

## ✨ Preview

O card exibe:
- **Foto de perfil** centralizada com borda circular sobre um banner colorido
- **Nome e cargo/descrição** do usuário
- **Ícones de redes sociais** (Facebook, Twitter, Instagram, YouTube)
- **Botões de ação** — Subscribe e Message
- **Estatísticas** — Likes, Comentários e Compartilhamentos

---

## 🛠️ Tecnologias Utilizadas

- **HTML5** — estrutura semântica do card
- **CSS3** — estilização, bordas arredondadas, sombras e layout Flexbox

---

## 📁 Estrutura do Projeto

```
profile-card/
├── index.html
├── style.css
└── assets/
    └── profile.jpg
```

---

## 🚀 Como Executar

1. Clone ou baixe este repositório
2. Adicione uma imagem de perfil em `assets/profile.jpg`
3. Abra o arquivo `index.html` no seu navegador

Nenhuma instalação ou dependência necessária!

---

## 🎨 Estrutura Visual

```
┌─────────────────────────────┐
│       [Banner Azul]         │
│         ⬤ Foto              │
├─────────────────────────────┤
│        Nome do Usuário      │
│        Cargo / Descrição    │
│                             │
│   [FB]  [TW]  [IG]  [YT]   │
│                             │
│  [Subscribe]   [Message]    │
│                             │
│  ♡ 60k  | 💬 20k | ↩ 12k   │
└─────────────────────────────┘
```

---

## ⚙️ Personalização

Você pode facilmente customizar o card editando o CSS e o HTML:

| Elemento | Como alterar |
|---|---|
| Cor do banner | Altere `background-color` no `.card-header` |
| Foto de perfil | Substitua o `src` da tag `<img>` |
| Nome e cargo | Edite os textos no HTML |
| Redes sociais | Adicione ou remova ícones na seção `.social-icons` |
| Estatísticas | Altere os valores em `.stats` |

---

## 📌 Funcionalidades

- [x] Layout centralizado com Flexbox
- [x] Foto de perfil com borda circular
- [x] Banner de cabeçalho colorido
- [x] Ícones de redes sociais estilizados
- [x] Botões de ação com hover effect
- [x] Estatísticas de engajamento
- [x] Card com sombra suave (`box-shadow`)
- [x] 100% HTML e CSS — sem JavaScript

---

## 🎨 Inspiração

Projeto criado pelo canal **CodingLab**, focado em componentes de UI modernos com HTML e CSS puro.

---

## 📄 Licença

Este projeto é livre para uso educacional e pessoal.
