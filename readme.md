# Caladan Focus

Ambiente minimalista para concentração: música, brown noise e anotações em uma única página, sem servidor e sem distrações.

---

## Funcionalidades

* Anotações com salvamento automático (`localStorage`)
* Player de música do YouTube
* Player de brown noise do YouTube (os dois tocam ao mesmo tempo)
* Relógio em tempo real
* Temas selecionáveis (persistidos no navegador)
* Zero dependências

---

## Temas

Troque pelo seletor no canto superior direito. A escolha fica salva em `localStorage`.

| Tema              | Estilo                                      |
| ----------------- | ------------------------------------------- |
| **shadcn**        | Zinc dark, cards e focus ring no estilo UI  |
| **Solarized Osaka** | Paleta Solarized Dark / Osaka, com glow   |
| **Tokyo Night**   | Azul `#7aa2f7`, fundo `#1a1b26`             |

### Referência rápida de cores

**shadcn**

| Token      | Hex       |
| ---------- | --------- |
| Background | `#09090b` |
| Border     | `#27272a` |
| Primary    | `#fafafa` |
| Text       | `#fafafa` |

**Solarized Osaka**

| Token      | Hex       |
| ---------- | --------- |
| Background | `#00141d` |
| Surface    | `#073642` |
| Border     | `#164b5b` |
| Cyan       | `#2aa198` |
| Blue       | `#268bd2` |
| Text       | `#e8ece9` |

**Tokyo Night**

| Token      | Hex       |
| ---------- | --------- |
| Background | `#1a1b26` |
| Card       | `#16161e` |
| Border     | `#292e42` |
| Blue       | `#7aa2f7` |
| Muted      | `#565f89` |
| Text       | `#c0caf5` |

---

## Layout

```
+--------------------------------------------------------------+
| Caladan Focus          [tema ▾]              data · hora     |
+--------------------------+-----------------------------------+
|                          |                                   |
| Música                   |                                   |
| ┌──────────────────────┐ |                                   |
| │                      │ |                                   |
| └──────────────────────┘ |         Anotações                 |
|                          |                                   |
| Brown Noise              |                                   |
| ┌──────────────────────┐ |                                   |
| │                      │ |                                   |
| └──────────────────────┘ |                                   |
|                          |                                   |
+--------------------------+-----------------------------------+
```

## Persistência

Tudo fica no **Local Storage** do navegador:

| Chave           | Conteúdo              |
| --------------- | --------------------- |
| `focus-notes`   | Texto das anotações   |
| `music-url`     | URL do player de música |
| `noise-url`     | URL do brown noise    |
| `focus-theme`   | Tema ativo            |

Sem login, sem banco, sem sync — os dados duram enquanto o cache do navegador não for limpo.

## Licença

MIT
