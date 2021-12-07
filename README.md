# NinjaRivals
Repositório destinado às entregas e requerimentos propostos na disciplina de Multiplayer.<br/>
Para acessar e testar o jogo, acessar a página do Ninja Rivals no Itch.io: https://erodrigues.itch.io/ninja-rivals.

## Autores: Bernardo Pereira e Eduardo Rodrigues

## CheckPoint 1 - 09/11
* O projeto consiste em um jogo multiplayer pixel art 2D, em visão top-down. 
* O projeto vem sendo desenvolvido desde o começo do semestre (2/2021) para a disciplina de Laboratório de Software e Projetos como um jogo Singleplayer estilo The Legend Of Zelda. Porém, ao ser incluído no projeto final de Jogos Multiplayer foram feitas alterações (descritas abaixo) para se encaixar nos critérios desta disciplina.
* O jogo será focado na interação entre os players utilizando o estilo party onde dois ninjas dividem o mesmo mapa, cada um de um lado.  
* Devido ao fato de o projeto já ter sido iniciado previamente, alguns aspectos já haviam sido implementados:
	- Player com movimentação.
	- Arma do player.
	- Animações do player e de ataque.
	- Assets de arte.
	
## CheckPoint 2 - 16/11

* Foram revistas as determinações do projeto:
	* Para se encaixar na proposta multiplayer foi alterado o estilo de gameplay para party, buscando tanto uma interação divertida entre os players (como em muitos jogos da Nintendo) quanto um distanciamento dos comuns jogos de PvP em que os players simplesmente batalham entre si.
	* Para alcançar essa proposta foi definida uma gameplay baseada em hordas onde um ninja consegue interferir na gameplay do outro ao mesmo tempo em que acumula pontos para si. Tudo isso contribui para que seja incentivada uma competição divertida entre ambos.
	* No decorrer da partida, surgirão hordas de monstros simultaneamente, uma para cada ninja e o os player deverão derrotá-las para sobreviver.
	* Ao matá-los, haverá uma chance de dropar um item que, ao ser coletado, causará um efeito negativo (debuff) ao outro ninja, dificultando a luta contra a sua horda. Além disso, os monstros darão uma pontuação aos players que ao final da partida poderá ser convertida na criptomoeda do jogo.
* Com a alteração da proposta, foi removido o mapa antigo (de exploração).
* Foi criado o novo mapa e iniciado o processo de criação de inimigos. 
* Implementou-se um inimigo - Cactus - com movimentação, path finding e animações para testagem inicial das mecânicas, sem as funções de dano.

## CheckPoint 3 - 23/11

* Iniciado o sistema de waves.
* Cooldown do ataque do player (1s).
* Sincronização completa e funcional:
	* Players.
	* Ataques.
	* Animações.
	* Inimigos.

## CheckPoint 4 - 30/11
* Waves completamente implementadas e com características programáveis:
	* Quantidade de inimigos.
	* Tipos dos inimigos.
	* Tempo de duração da wave (Quanto tempo levará para spawnar a próxima). 
* Novos inimigos, com animações, movimentação e path finding:
	* Skeleton.
	* Gold Knight.
	* Dark Ninja.
* Implementação do dano do player (10 por hit). 
* Morte dos inimigos.<br/> 
Cada inimigo terá uma quantidade diferente de vida: 
	* Cactus - 20HP.
	* Skeleton - 50HP.
	* Dark Ninja - 100HP.
	* Golden Knight - 200HP.
* Sistema de Score.
* Iniciado o sistema de countdown das waves (Sinal visual para mostrar aos players que a próxima wave está vindo!).

##CheckPoint 5 - 07/12
* Vida dos Players - 100HP (Agora os Ninjas podem ser mortos pelos inimigos).
* Ataque dos inimigos:
	* Cactus - 10 dmg.
	* Skeleton - 10 dmg.
	* Dark Ninja - 20 dmg.
	* Golden Knight - 30 dmg.
* Tela inicial. Com botões Play e Host.
* Tela de fim de partida. Quando o HP de um dos Ninjas chegar a zero aparecerá a tela de WIn/Lose dando a vitória para o Ninja que sobreviver até o final.
* Sistema de Score aprimorado, após encontrarmos problemas no sistema antigo.
