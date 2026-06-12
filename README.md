# 🌌 Wallpaper Animados

> Uma coleção de wallpapers dinâmicos e interativos construídos com tecnologias web. Leves, performáticos e totalmente compatíveis com **Wallpaper Engine**, **Lively Wallpaper** e navegadores modernos.

![License](https://img.shields.io/github/license/EduardoHolkem/WallpapersAnimados?style=flat-square)
![Stars](https://img.shields.io/github/stars/EduardoHolkem/WallpapersAnimados?style=flat-square)
![Issues](https://img.shields.io/github/issues/EduardoHolkem/WallpapersAnimados?style=flat-square)

---

## 📖 Sobre o Projeto

Este repositório é um laboratório de experimentação visual. O objetivo é criar fundos de tela que não sejam apenas vídeos em loop, mas **experiências renderizadas em tempo real** via código.

Utilizando **HTML5 Canvas**, **CSS3** e **JavaScript puro**, os wallpapers são otimizados para consumir o mínimo de CPU/GPU possível, mantendo a fluidez de 60fps e a alta resolução.

---

## 🖼️ Galeria de Wallpapers

Aqui estão as criações disponíveis no repositório:

### 🐺 Jon Snow - Winter is Coming
Um ambiente gélido e imersivo inspirado em Game of Thrones.
- **Destaques:** Neve com efeito Parallax (camadas de profundidade), animação de respiração orgânica no personagem e relógio digital minimalista.
- **Estilo:** Atmosférico / Dark.
- **Pasta:** `/Jon-Snow/`
- **Preview:** ![Jon Snow Preview](Jon-Snow/preview.jpg)

*(Para adicionar novos wallpapers, basta criar uma nova seção aqui)*

---

## 🚀 Como Instalar e Usar

Todos os projetos seguem o mesmo padrão de instalação:

### ⚙️ No Wallpaper Engine (Recomendado)
1. Abra o **Wallpaper Engine**.
2. Clique em **"Criar wallpaper"** $\rightarrow$ Selecione **"Web"**.
3. Navegue até a pasta do wallpaper escolhido e selecione o arquivo `index.html` (ou `project.json`).
4. Aplique e aproveite.

### 🌈 No Lively Wallpaper (Open Source)
1. Abra o **Lively Wallpaper**.
2. Arraste a pasta do wallpaper escolhido para dentro da biblioteca do programa.
3. Defina-o como seu fundo de tela ativo.

### 🌐 No Navegador
Basta abrir o arquivo `.html` de qualquer wallpaper em seu navegador favorito para visualizar em tela cheia.

---

## 🛠️ Stack Técnica

Para garantir que os wallpapers sejam leves e compatíveis com qualquer sistema, utilizo:

- **HTML5 Canvas:** Para renderização de partículas e efeitos matemáticos complexos.
- **CSS3 Animations:** Para movimentos suaves, transições e efeitos de brilho (glow).
- **Vanilla JavaScript:** Lógica pura, sem dependências ou frameworks pesados, garantindo carregamento instantâneo.
- **Responsive Design:** Todos os wallpapers se ajustam automaticamente a resoluções Full HD, 4K e UltraWide.

---

## 📁 Organização do Repositório

```text
Wallpaper-Animados/
├── Jon-Snow/               # Pasta do Wallpaper do Jon Snow
│   ├── index.html          # Código principal
│   ├── project.json        # Configuração Wallpaper Engine
│   └── JonSnow.png         # Assets de imagem
