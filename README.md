# 2º Projeto de Linguagens de Programação II 2019/2020

## [Repo Git - Projeto](https://github.com/JBernardoRebelo/Projeto2_LPII_Fernandez_Rebelo)

## Autores

### *[João Rebelo - a21805230](https://github.com/JBernardoRebelo)*

- Implementação do *Game Engine* na criação no jogo.
- Geração procedimental da *dungeon* e colocação de respetivos
componentes na mesma tal como a sua renderização.
- Criação de classes que compõem o jogo.
- Ficheiro README e UML.
- XML das classes do jogo.

### *[Miguel Fernández - a21803644](https://github.com/MizuRyujin)*

- Implementação e manutenção do *Game Engine*.
- Comportamento dos inimigos.
- Controlador do jogador.
- XML do *Game Engine*. *Doxyfile*.

## Design Patterns utilizados

Gameloop;

Component;

Composite;

Observer Pattern;

### **O que foi implementado:**

- Implementação o Game Loop e o Update Method.
- Duas threads: a thread principal do jogo (que executa o game loop) e uma thread para ler input do utilizador.
- Mecânicas base do jogo original:
  - Movimento ´WASD´;
  - 1 Ataque *skill*;
  - 1 Inimigo atacável que ataca;
  - 1 *dungeon* explorável gerada procedimentalmente;
  - XP que se ganha ao matar inimigo e sistema de níveis e stats que se
incrementam;
  - Ter algum tipo de ecrã inicial com opção no menu onde são explicadas
  as regras e indicados os controlos do jogo;
  - Menu de escolha de classes com 2 classes,  warrior e rogue;

## Diagrama UML

![](DiabloUml.png)

## Referências

### *[.NET API](https://docs.microsoft.com/en-us/dotnet/api/?view=netcore-2.2)*

- *[Vector2 Struct](https://docs.microsoft.com/en-us/dotnet/api/system.numerics.vector2?view=netframework-4.8)*
- *[Finalizers ](https://docs.microsoft.com/en-us/dotnet/csharp/programming-guide/classes-and-structs/destructors)*
- *[GC.Collect Method](https://docs.microsoft.com/en-us/dotnet/api/system.gc.collect?view=netframework-4.8)*

### *[Stack overflow](https://stackoverflow.com/)*

- *[Remove Item in Dictionary based on Value](https://stackoverflow.com/questions/1636885/remove-item-in-dictionary-based-on-value)*
- *[Detect collision between a moving object and an immobile one](https://stackoverflow.com/questions/3195495/detect-collision-between-a-moving-object-and-an-immobile-one)*
- *[Destroy an object in C#](https://stackoverflow.com/questions/25764965/destroy-an-object-in-c-sharp/25765055)*

# André

## **Instruções:**

- Escrever "credits" ou 'c' para os creditos;
- Escrever "exit" ou 'e' para sair; 
- Pressionar qualquer tecla no menu inicial para começar:
  - Escrever o nome da classe desejada;
  - De seguida o nome do jogador;
- No jogo:
  - Atacar inimigos para ganhar XP e subir de nível;
  - Eliminar todos os inimigos causa vitória e morrer causa derrota;

## Controlos

- 'WASD' para mover o personagem;
- 'Space' para atacar;
- 'C' para mostrar detalhes do personagem;
- 'E' para abrir portas e entrar na respetiva sala;
- (Por agora) Escrever a opção pretendida dentro de menus;

### **Mecânicas omitidas de desenvolvimento que poderiam ser implementados**

- Sistema de inventário e Lojas/Transações de Gold
  - De momento só existe 1 item possível e é a _Short Sword_ usada para atacar;
- Classe _Sorcerer_;
- Restantes _stats_ de classe;
- Interações e existência de NPC's;
- Controlo e ataque de jogador com rato (utilizar o teclado pareceu mais prático de implementar);
