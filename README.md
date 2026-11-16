# 🚀 Jogo Space Shooter

## 📖 Sobre o Projeto

O **Jogo Space Shooter** é um clássico jogo de nave espacial estilo *arcade* 2D desenvolvido para navegador, criado como parte de um desafio prático da **[Digital Innovation One (DIO)](https://dio.me)**.

O objetivo principal da aplicação é colocar em prática conceitos fundamentais de desenvolvimento web e lógica de programação utilizando **HTML5**, **CSS3** e **JavaScript puro (Vanilla JS)** para manipular o DOM, controlar animações de elementos na tela, gerenciar disparos de laser, gerar inimigos aleatórios e detectar colisões em tempo real.

---

## ✨ Funcionalidades

- **Tela Inicial Interativa:** Botão **START** para iniciar a partida e carregar os elementos do cenário.
- **Controle da Nave Espacial:** Movimentação vertical (para cima e para baixo) dentro dos limites da área de jogo.
- **Sistema de Disparos:** Lançamento de projéteis (lasers) para interceptar e destruir as naves inimigas antes que atravessem a tela.
- **Geração Aleatória de Inimigos:** Surgimento contínuo e dinâmico de inimigos em diferentes posições verticais.
- **Detecção de Colisões:**
  - **Laser x Inimigo:** Destrói a nave inimiga atingida com efeito visual de explosão.
  - **Nave do Jogador x Inimigo (ou passagem pela defesa):** Encerra a partida (**Game Over**) e retorna à tela inicial.

---

## 🎮 Como Jogar

Utilize o teclado para pilotar sua nave e defender o espaço:

| Tecla | Ação |
| :--- | :--- |
| ⬆️ **Seta para Cima** | Move a nave para cima |
| ⬇️ **Seta para Baixo** | Move a nave para baixo |
| **Barra de Espaço (`Space`)** | Dispara o laser contra os inimigos |

---

## 🛠️ Tecnologias Utilizadas

Com base na estrutura do repositório, o projeto foi desenvolvido sem dependências externas, utilizando apenas tecnologias nativas da web:

- **HTML5 (`index.html`):** Estruturação da área principal do jogo, botões de controle e elementos visuais.
- **CSS3 (`style.css`):** Estilização do cenário espacial, posicionamento absoluto da nave, lasers, inimigos e animações.
- **JavaScript (`script.js`):** Lógica principal do jogo, captura de eventos do teclado (`keydown`), manipulação dinâmica de elementos no DOM, intervalos de movimentação e verificação de colisões.
- **Assets Gráficos (`img/`):** Sprites da nave heroína, naves inimigas, laser, explosão e plano de fundo espacial.

---

## 📂 Estrutura de Arquivos

```text
jogo_space-shooter/
├── img/              # Imagens e sprites do jogo (nave, inimigos, fundo, laser e explosão)
├── index.html        # Estrutura HTML principal da tela do jogo
├── style.css         # Folha de estilos, layout e visual do cenário
├── script.js         # Lógica de movimentação, tiros, geração de inimigos e colisões
└── README.md         # Documentação do projeto
```

---

## 🚀 Como Executar o Projeto na Sua Máquina

Por se tratar de uma aplicação front-end estática (HTML, CSS e JavaScript puro), **não é necessário instalar Node.js, servidores ou dependências externas** para executar o jogo.

### Pré-requisitos

- Um navegador web atualizado (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, etc.).
- **[Git](https://git-scm.com)** instalado (opcional, caso queira clonar via terminal em vez de baixar o arquivo ZIP).

### Passo a passo

1. **Clone o repositório:**
   ```bash
   git clone https://github.com
   ```
   *(Alternativamente, clique no botão **Code > Download ZIP** no GitHub e extraia a pasta no seu computador).*

2. **Acesse a pasta do projeto:**
   ```bash
   cd jogo_space-shooter
   ```

3. **Execute o jogo no navegador:**
   - **Opção 1 (Direto pelo arquivo):** Abra a pasta do projeto no explorador de arquivos do seu sistema e dê um **duplo clique** em `index.html` para abri-lo no seu navegador.
   - **Opção 2 (Via Live Server no VS Code):** Abra a pasta no [Visual Studio Code](https://visualstudio.com), clique com o botão direito sobre o arquivo `index.html` e selecione **"Open with Live Server"**.

---

## 🤝 Contribuição

Contribuições são sempre bem-vindas! Se você quiser aprimorar o jogo (adicionando contador de pontos, sistema de vidas ou efeitos sonoros):

1. Faça um **Fork** deste repositório.
2. Crie uma **Branch** para sua melhoria (`git checkout -b feature/NovaFuncionalidade`).
3. Faça o **Commit** das suas alterações (`git commit -m 'Adiciona contador de pontuação'`).
4. Faça o **Push** para a branch (`git push origin feature/NovaFuncionalidade`).
5. Abra um **Pull Request**.

---

## 👨‍💻 Autor

Desenvolvido por **[marceloxm](https://github.com/marceloxm)** durante os estudos na **Digital Innovation One (DIO)**.

