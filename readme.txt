# ⚔️ Brazilian Fighter

> **Brazilian Fighter** é um jogo de luta retrô em 2D desenvolvido para navegador (HTML5 Canvas & JavaScript), inspirado em clássicos do arcade como *Mortal Kombat* e *Street Fighter*, trazendo como protagonistas grandes figuras da história do Brasil.

---

## 📌 Sobre o Jogo

O jogo coloca personagens históricos em embates épicos ambientados em cenários marcantes do passado nacional. Desenvolvido em um único arquivo HTML standalone, ele não exige bibliotecas externas, servidores ou instalações complexas.

### 🌟 Destaques
- **Estética Arcade / Synthwave / Retro:** Interface estilizada com fontes pixeladas (`Press Start 2P`), HUD detalhado e molduras de pedra.
- **Dublagem em Balões de Diálogo:** Frases de efeito marcantes acionadas ao executar golpes especiais.
- **Inteligência Artificial Adaptativa:** A cada vitória em sequência (Win Streak), a CPU ganha +3% de velocidade e dano.
- **Melhor de 3 Rounds:** Sistema dinâmico de marcação de pontos e K.O.

---

## 🎮 Controles

| Ação | Menu de Seleção | Durante a Luta (P1) |
| :--- | :--- | :--- |
| **Mover / Selecionar** | `W` `A` `S` `D` ou `Setas` | `A` (Esquerda) / `D` (Direita) |
| **Pular** | - | `W` ou `Seta para Cima` |
| **Confirmar** | `ENTER` ou `ESPAÇO` | - |
| **Ataque Leve** | - | `J` *(Gera +15% de Especial)* |
| **Ataque Especial** | - | `K` *(Requer Barra Azul em 100%)* |

---

## 👥 Elenco de Lutadores (Fighters)

| Personagem | Frase do Especial (Quote) |
| :--- | :--- |
| **D. Pedro I** | *"Independência ou Morte!"* |
| **D. Pedro II** | *"A educação é a base do progresso."* |
| **José Bonifácio** | *"O Brasil precisa de ciência e virtude."* |
| **Zumbi dos Palmares** | *"Liberdade não se concede, se conquista!"* |
| **Luís Gama** | *"A lei deve ser igual para todos!"* |
| **Marechal Deodoro** | *"A República é o destino do Brasil!"* |
| **Regente Feijó** | *"Precisamos manter a ordem e a unidade."* |
| **Ventura Mina** | *"Liberdade para o povo!"* |
| **André Rebouças** | *"A engenharia constrói pontes para a liberdade."* |
| **Maria Quitéria** | *"Pelo Brasil defenderemos nossa Pátria!"* |

---

## 🏛️ Cenários Históricos

1. **Proclamação da Independência (1822)**
2. **Chegada da Família Real (1808)**
3. **Aclamação de D. Pedro I**
4. **Mercado de Escravos - Séc. XIX**
5. **Revolta dos Malês (1835)**
6. **Abolição da Escravatura (1888)**
7. **Proclamação da República (1889)**
8. **Random** *(Escolha aleatória)*

---

## 🛠️ Estrutura do Projeto

```text
.
├── BrasilFighter.exe.html      # Motor principal do jogo (HTML5 + CSS + JS Engine)
├── cenario1.png ... cenario7.png # Imagens de fundo dos cenários
├── sprites_pose_*.png          # Sprites dos personagens em pose neutra
├── sprites_andar_*.png         # Sprites de caminhada
├── sprites_atacar_*.png        # Sprites de animação de ataque
├── sprites_dano_*.png          # Sprites ao sofrer impacto
└── README.md                    # Documentação do projeto