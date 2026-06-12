# 🎯 Focus Room

Uma página ambiente minimalista para te ajudar a focar. Limpa, sem distrações, com relógio ao vivo, data, música de fundo, suporte a múltiplos idiomas e alternância entre tema claro e escuro.

---

## ✨ Funcionalidades

- 🕐 **Relógio ao vivo** — canto superior direito, atualiza a cada segundo
- 📅 **Data** — centralizada na tela, formatada conforme o idioma selecionado
- 🌍 **Múltiplos idiomas** — English, Español, Français, Português, 한국어
- 🎵 **Música de fundo** — liga e desliga áudio ambiente
- 🌙 **Tema claro/escuro** — alternância manual, preferência salva automaticamente
- 💾 **Configurações persistentes** — idioma e tema salvos via localStorage

---

## 📁 Estrutura do Projeto

```
focus-room/
├── index.html
├── css/
│   └── base.css
├── javascript/
│   └── script.js
└── assets/
    └── music.mp3
```

---

## 🚀 Rodando Localmente

Basta abrir o `index.html` no navegador — sem build, sem dependências.

> **Dica:** Use um servidor local (como o [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) do VS Code) para evitar restrições do navegador no autoplay de áudio.

---

## 🎵 Trocando a Música

Substitua o arquivo `assets/music.mp3` por qualquer `.mp3` de sua escolha. Mantenha o mesmo nome, ou atualize o caminho no `index.html`:

```js
const audioElement = new Audio("assets/seu-arquivo.mp3");
```

---

## 🛠️ Tecnologias

- HTML, CSS e JavaScript puro — sem frameworks
- [Font Awesome 6](https://fontawesome.com/) — ícones
- [Roboto Mono](https://fonts.google.com/specimen/Roboto+Mono) — tipografia

---

## 📄 Licença

MIT — livre para usar e modificar.
