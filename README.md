# Jogo do Número Secreto

[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/docs/Web/JavaScript)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/docs/Web/CSS)

🇵🇹 [Português](#português) · 🇬🇧 [English](#english)

---

## Português

Jogo de adivinha em JavaScript: o computador sorteia um número secreto e o jogador
tenta descobri-lo, recebendo pistas de "maior" ou "menor" a cada tentativa.

### Funcionamento

- O número secreto é sorteado entre 1 e 10
- A cada palpite o jogo indica se o número secreto é maior ou menor
- No fim mostra em quantas tentativas o jogador acertou
- Números já sorteados não se repetem enquanto houver alternativas disponíveis
- As mensagens são lidas em voz alta através da biblioteca **ResponsiveVoice**

### Como jogar

Não é preciso instalar nada — basta abrir o ficheiro no navegador:

```bash
git clone https://github.com/ixmjst/numero-aleatorio.git
cd numero-aleatorio
```

Depois abre o `index.html` no browser.

### Estrutura

```
index.html    → Estrutura da página
style.css     → Estilos e layout
app.js        → Lógica do jogo
img/          → Imagens de fundo e ilustrações
```

### Conceitos praticados

- Manipulação do DOM com `querySelector` e `innerHTML`
- Geração de números aleatórios com `Math.random()`
- Arrays e controlo de valores já utilizados
- Estruturas condicionais e funções
- Template strings e operador ternário
- Integração de uma biblioteca externa (síntese de voz)

---

## English

A guessing game in JavaScript: the computer picks a secret number and the player tries
to find it, getting "higher" or "lower" hints on each attempt.

### How it works

- The secret number is drawn between 1 and 10
- Each guess tells the player whether the target is higher or lower
- At the end it reports how many attempts were needed
- Already-drawn numbers are not repeated while alternatives remain
- Messages are read aloud through the **ResponsiveVoice** library

### Playing

Nothing to install — just open the file in a browser:

```bash
git clone https://github.com/ixmjst/numero-aleatorio.git
cd numero-aleatorio
```

Then open `index.html`.

### Concepts practised

- DOM manipulation with `querySelector` and `innerHTML`
- Random number generation with `Math.random()`
- Arrays and tracking used values
- Conditionals and functions
- Template strings and the ternary operator
- Integrating an external library (speech synthesis)

---

<sub>Projeto de aprendizagem · José Simão Tala ([@ixmjst](https://github.com/ixmjst))</sub>
