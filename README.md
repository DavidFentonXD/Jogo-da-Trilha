Este é um projeto da disciplina **Programação II**, sob orientação do Prof. Dr. Alcides Xavier Benicasa, que consiste na implementação do tradicional jogo de tabuleiro **Trilha** (também conhecido como *Nine Men’s Morris*, *Jogo do Moinho* ou *Merels*), utilizando as linguagens **C/C++**.

## 📜 Regras e Funcionamento

### 🎯 Objetivo
Reduzir o número de peças do adversário para menos de três **ou** bloqueá-lo para que não possa realizar movimentos.

### 🎲 Jogadores
- Dois jogadores
- Cada um recebe 9 peças de uma cor diferente (18 no total)

### 🧩 Fases do Jogo

#### 🟢 Fase 1 — Colocação das Peças
- Os jogadores se alternam posicionando suas 9 peças em locais livres do tabuleiro.
- Ao formar uma **trilha** (linha de 3 peças), o jogador pode **remover uma peça do adversário**.
- Não é permitido remover peças que estão em trilha, a menos que todas as peças restantes do oponente estejam.

#### 🔄 Fase 2 — Movimentação
- Com todas as peças no tabuleiro, os jogadores movem suas peças para posições **adjacentes** livres.
- Ao formar trilha novamente, podem remover uma peça do oponente (seguindo a regra anterior).

#### 🆓 Fase 3 — Movimento Livre
- Quando um jogador tiver apenas 3 peças restantes, ele pode mover para qualquer posição livre (sem restrição de adjacência).

### 🏁 Condições de Vitória
- O adversário possui apenas 2 peças restantes.
- O adversário está bloqueado e não pode se mover.

### ⚖️ Empate
- Ambos os jogadores têm 3 peças e nenhum moinho é formado após 10 jogadas consecutivas.

## 💻 Como Executar

### ✅ Requisitos
- Compilador C/C++ (GCC, Clang, Dev-C++, Code::Blocks, etc.)

## 👨‍💻 Equipe

Projeto desenvolvido pela **Equipe 4** da disciplina de Programação II – Prof. Dr. Alcides Xavier Benicasa.

**Integrantes:**
- Ana Julia Barbosa Fontes De Souza
- Bernardo Santos Silva
- David Santos Silvino
- Kaua Eduardo Andrade De Lima
- Paulo Italo Santos Costa

