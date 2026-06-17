# 🎮 PyBlocks – Aprenda Programando

O **PyBlocks** é uma aplicação interativa e gamificada voltada para o ensino introdutório de lógica de programação e da sintaxe básica da linguagem Python. Através de uma narrativa prática baseada em um problema do mundo real — o cálculo do desperdício de água em vazamentos —, o usuário é guiado desde a interpretação lógica até a escrita de código real.

---

## 🚀 Estrutura do Aplicativo e Fases

O projeto é estruturado de forma linear e salva o progresso do usuário localmente para garantir a continuidade da experiência.

### 🏢 1. Tela Inicial / Dashboard (`index.html`)
* **Gerenciamento de Perfil:** Sistema de identificação local que armazena o nome do usuário no `localStorage`.
* **Painel de Missões:** Exibição dinâmica do progresso do usuário (Fases Bloqueadas / Desbloqueadas).
* **Animações de Conclusão:** Efeitos visuais de celebração ao concluir a jornada.

### 🧩 2. Fase 1: Pensamento Lógico (`fase1.html`)
* **Conceito:** Introdução aos algoritmos através de blocos lógicos estruturados.
* **Mecânica:** O jogador entende a sequência correta de execução (Início, Entrada de Dados, Processamento e Condição) para calcular litros de água perdidos.
* **Suporte:** Chatbot integrado para tirar dúvidas em tempo real sobre a função de cada bloco.

### 💻 3. Fase 2: Tradução para Código (`fase2.html`)
* **Conceito:** Transição da lógica visual para a sintaxe real do Python.
* **Mecânica:** Fixação de comandos essenciais como `input()`, conversão de tipos com `int()`, operadores aritméticos (`*`), estruturas condicionais (`if`) e a importância da indentação.

### ✍️ 4. Fase 3: Desafio Prático (`fase3.html`)
* **Conceito:** Consolidação do conhecimento através da escrita autônoma de código.
* **Mecânica:** Um editor de código embutido com validação inteligente de sintaxe e simulação de console de execução.

---

## 🛠️ Tecnologias Utilizadas

O projeto foi desenvolvido utilizando tecnologias web nativas para garantir o máximo de desempenho e portabilidade:

* **HTML5:** Estruturação semântica de todas as telas.
* **CSS3:** Interface moderna estilo "cyberpunk / dark mode", tipografia limpa (`Inter` e `JetBrains Mono`) e layout totalmente responsivo para celulares.
* **JavaScript (ES6):** Manipulação dinâmica do DOM, controle de estado do jogo, sistema de persistência (`localStorage`) e lógica de validação de desafios.

---

## 🌐 Como Jogar (Web & Mobile)

### Versão Web (GitHub Pages)
O projeto está configurado para rodar diretamente no navegador através do GitHub Pages.

### Versão Mobile Nativa
Este projeto utiliza o **Capacitor** para encapsular a aplicação web em um aplicativo nativo Android (`.apk`).
