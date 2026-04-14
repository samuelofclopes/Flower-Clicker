  **Flower Clicker**
================================================================
  
**Este projecto é um jogo do tipo "clicker" feito em Python usando Tkinter e um modulo feito por mim!.**

**O que tem/é o jogo?**

Flower Clicker é um jogo onde o jogador evolui uma flor através de clicks, upgrades e rebirths.

À medida que o nivel do jogador aumenta, a flor transforma‑se e o fundo muda, após cada rebirth novas mecânicas aparecem e o jogo torna‑se cada vez mais dificil.
  
**Qual o objetivo?**
================================================================

clicar para ganhar pontos, subir de nivel usando os pontos, renascer usando o nivel e repetir com novas mecanicas


**Funcionalidades Principais**
================================================================

A evolução da Flor, a flor muda de aparência conforme o nível.

Após o nível 250, transforma‑se numa árvore. - ( Quando chega a arvore, é porque o rebirth está quase a chegar! )

Nível especial: 143 desbloqueia uma flor com temática do amor, uma referencia escondida...

**Como funciona o sistema de pontos**
================================================================

Um click normal na tecla espaço: ganha pontos.

Melhorar o “MORE POINTS UPD”: aumenta os pontos por click no espaço.

Textos animados mostram os pontos ganhos.

Quantos mais upgrades fizer, maior vai sendo o custo do proximo upgrade.

Eu usei uma expoente simples: x = x^1.25 e x = x^1.75 dependendo do upgrade.

(Orgulho de ter cido eu mesmo a fazer, com a minha cabeça! hahaha)

**Sistema de Rebirth**
================================================================

Rebirth 1: desbloqueia pontos por click no botão direito do rato.

Rebirth 2: desbloqueia folhas caindo e pontos por folha apanhada.

**As folhas e estrelas cadentes**
================================================================
As estrelas cadentes aparecem aleatoriamente no céu. - (Não dão bonus nenhum, apenas decoração visual)

As folhas caem quando o jogador atinge Rebirth 2.

Ao clicar nas folhas dá pontos extra.

**A música de Fundo**
================================================================

A música de fundo foi feita em loop usando winsound. - (Pensei em usar o Pygame, mas eu não queria criar dependencias)


**O sistema de save automático**
================================================================

O jogo salva automaticamente a cada 30 segundos, usando o módulo personalizado bib_saves.

**As imagens utilizadas**
================================================================

O jogo utiliza várias imagens externas:

12 sprites de flores

3 sprites de árvores

Ícone da loja

Sprite de estrela cadente

Todos eles foram feitos manualmente por mim, por isso não teem uma "otima" qualidade, foi a minha primeira vez a mexer com pixelart e com sprites.

**Sobre o .zip**
================================================================

O .zip é a pasta com todos os itens do repositório e o ficheiro .exe do jogo! 
Ele foi feito com o "py_to_exe" integrado no python, infelizmente, tal como o winsound, não funciona fora do windows...
