# Tradutor Morse / Morse Translator

> 🌐 Bilingual PT/EN — toggle language anytime with the EN/PT button.

A fully bidirectional Morse code translator that runs entirely in the browser with no dependencies.

---

## 🇧🇷 Português

### O que é
Tradutor bidirecional Morse ↔ Texto que roda 100% no navegador, sem instalação, sem servidor, sem dependências externas.

### Como usar
1. Abra `index.html` em qualquer navegador moderno.
2. **Texto → Morse**: Digite texto na caixa da esquerda; o Morse aparece automaticamente à direita.
3. **Morse → Texto**: Digite sinais Morse (pontos e traços) na caixa da direita; o texto aparece à esquerda.
4. **⇄ Inverter**: Clique no botão central para trocar o conteúdo entre os painéis.
5. **▶ Tocar**: Clique em *Tocar* para ouvir o Morse em áudio via beeps. Ajuste a velocidade (WPM) com o slider.
6. **Copiar**: Copie o código Morse para a área de transferência com um clique.
7. **Tabela de Referência**: Expanda para ver todos os caracteres suportados.

### Funcionalidades
- Tradução bidirecional em tempo real (Texto → Morse e Morse → Texto)
- Reprodução de áudio via Web Audio API com WPM ajustável (5–40 WPM)
- Suporte a letras (A–Z), números (0–9) e pontuação básica (`.`, `,`, `?`, `!`)
- Contador de caracteres em tempo real
- Toggle de idioma PT/EN
- Tabela de referência expansível
- Atalhos de teclado: `Alt+P` (tocar/parar), `Alt+L` (trocar idioma)
- Zero dependências — funciona offline

---

## 🇺🇸 English

### What it is
A fully bidirectional Morse ↔ Text translator that runs 100% in the browser — no install, no server, no external dependencies.

### How to use
1. Open `index.html` in any modern browser.
2. **Text → Morse**: Type text in the left box; Morse appears automatically on the right.
3. **Morse → Text**: Type Morse signals (dots and dashes) in the right box; text appears on the left.
4. **⇄ Swap**: Click the center button to swap content between panels.
5. **▶ Play**: Click *Play* to hear the Morse as audio beeps. Adjust speed (WPM) with the slider.
6. **Copy**: Copy the Morse code to clipboard in one click.
7. **Reference Table**: Expand to see all supported characters.

### Features
- Real-time bidirectional translation (Text → Morse and Morse → Text)
- Audio playback via Web Audio API with adjustable WPM (5–40 WPM)
- Supports letters (A–Z), numbers (0–9), and basic punctuation (`.`, `,`, `?`, `!`)
- Real-time character counter
- PT/EN language toggle
- Expandable reference table
- Keyboard shortcuts: `Alt+P` (play/stop), `Alt+L` (toggle language)
- Zero dependencies — works offline

---

## How to run / Como rodar

Just open the file:

```bash
# No build step needed!
open index.html        # macOS
xdg-open index.html    # Linux
start index.html       # Windows
```

Or drag `index.html` into any browser window.

---

## License / Licença

MIT © 2026 Jonathan Ferreira Soares
