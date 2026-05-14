# Criativo · Instalação AIOX

Experiência interativa e cinematográfica para apresentação do processo de instalação do **Claude Code**, **Node.js** e **AIOX-SQUAD**.

## Stack

- HTML + CSS + JavaScript vanilla (sem build)
- Fontes: Quicksand, JetBrains Mono, Press Start 2P
- Animações CSS puras + SVG + Canvas (TV static)
- Pan/drag estilo Figma/Miro (mousedown + drag)

## Recursos

- **Botão Claude Code 3D** — pressionável, com glow laranja quando ligado
- **Trilha de luz** descendente até botão Instalação
- **Ramificações orgânicas** verde neon (Pc_install + Node.js)
- **Monitor CRT** com TV static animado em canvas + comando digitado
- **Painel Node.js** com tabs Windows/Mac/Linux
- **Letreiro pixel-art** comemorativo (Press Start 2P + logos correndo)
- **Cena AIOX** completa com botão arcade, trilha lime green e instalação
- **Tutorial passo a passo** com 8 screenshots e finale com confetti

## Como rodar

```bash
open index.html
```

Ou serve em qualquer servidor estático.

## Estrutura

```
.
├── index.html                  # Toda a aplicação
├── claudecode-botao.png        # Botão 3D Claude Code
├── claudecode-logo.png         # Logo pixel-art Claude Code
├── Instalação.png              # Botão Instalação verde
├── nodeJS.png                  # Logo Node.js
├── Pc_install.png              # Monitor CRT vintage
├── aiox-logo.png               # Logo AIOX neon
└── Instalação AIOX/
    ├── 1.png … 8.png           # Screenshots do installer AIOX
```
