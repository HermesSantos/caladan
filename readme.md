# 🎧 Focus Space

Um ambiente minimalista para concentração, criado para reduzir distrações e manter tudo o que você precisa em uma única página.

A ideia é simples: em vez de abrir diversas abas para música, ruído ambiente e anotações, o **Focus Space** reúne tudo em uma interface limpa inspirada na paleta **Solarized Osaka Dark**.

---

## ✨ Funcionalidades

* 📝 Área de anotações com salvamento automático (`localStorage`)
* 🎵 Player de música do YouTube
* 🌧️ Player de Brown Noise do YouTube
* ▶️ Os dois vídeos podem tocar ao mesmo tempo
* 🕒 Relógio em tempo real
* 🌙 Interface escura inspirada no Solarized Osaka
* 💾 Não requer servidor ou banco de dados

---

## 📷 Layout

```
+--------------------------------------------------------------+
| Focus Space                                   13:42          |
+--------------------------+-----------------------------------+
|                          |                                   |
| 🎵 Música                |                                   |
| ┌──────────────────────┐ |                                   |
| │                      │ |                                   |
| └──────────────────────┘ |                                   |
|                          |                                   |
| 🌧 Brown Noise          |         📝 Anotações               |
| ┌──────────────────────┐ |                                   |
| │                      │ |                                   |
| └──────────────────────┘ |                                   |
|                          |                                   |
|                          |                                   |
+--------------------------+-----------------------------------+
```

---

## 🚀 Como usar

Clone o repositório:

```bash
git clone https://github.com/seu-usuario/focus-space.git
```

Entre na pasta:

```bash
cd focus-space
```

Abra o arquivo `index.html` em qualquer navegador moderno.

Não é necessário instalar dependências nem executar um servidor.

---

## 💾 Persistência

As anotações são armazenadas automaticamente utilizando o **Local Storage** do navegador.

Isso significa que:

* não há login;
* não há banco de dados;
* não há sincronização;
* os dados permanecem disponíveis enquanto o cache do navegador não for apagado.

---

## 🎵 Sons incluídos

### Música

https://www.youtube.com/watch?v=gOwbMN0JswA

### Brown Noise

https://www.youtube.com/watch?v=RqzGzwTY-6w

---

## 🎨 Paleta

Inspirado em:

* Solarized Dark
* Solarized Osaka

Principais cores utilizadas:

| Cor        | Hex       |
| ---------- | --------- |
| Background | `#00141d` |
| Surface    | `#073642` |
| Border     | `#164b5b` |
| Cyan       | `#2aa198` |
| Blue       | `#268bd2` |
| Text       | `#e8ece9` |

---

## 📁 Estrutura

```
.
└── index.html
```

Todo o projeto está contido em um único arquivo:

* HTML
* CSS
* JavaScript

---

## 🛣️ Roadmap

* [ ] Controle de volume dos players
* [ ] Pomodoro
* [ ] Checklist
* [ ] Editor Markdown
* [ ] Fullscreen
* [ ] Atalhos de teclado
* [ ] Modo Zen
* [ ] Temas (Gruvbox, Catppuccin, Nord...)
* [ ] Sons adicionais (chuva, lareira, floresta, café, vento)

---

## 📄 Licença

Este projeto é disponibilizado sob a licença MIT.
