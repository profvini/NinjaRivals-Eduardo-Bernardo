# NinjaRivals
Repositório destinado às entregas e requerimentos propostos na disciplina de Multiplayer

## Autores: Bernardo Pereira e Eduardo Rodrigues

## CheckPoint 1 - 09/11
* O projeto consiste em um jogo multiplayer pixel art 2D, em visão top-down. 
* O projeto vem sendo desenvolvido desde o começo do semestre (2/2021) para a disciplina de Laboratório de Software e Projetos como um jogo Singleplayer estilo The Legend Of Zelda. Porém, ao ser incluído no projeto final de Jogos Multiplayer foram feitas alterações (descritas abaixo) para se encaixar nos critérios desta disciplina.
* O jogo será focado na interação entre os players utilizando o estilo party onde dois ninjas dividem o mesmo mapa, cada um de um lado.  
* Devido ao fato de o projeto já ter sido iniciado previamente, alguns aspectos já haviam sido implementados:
	- Player com movimentação
	- Arma do player
	- Animações do player e de ataque.
	- Assets de arte
	

## CheckPoint 2 - 16/11

* Foram revistas as determinações do projeto.
* Para se encaixar na proposta multiplayer foi alterado o estilo de gameplay para party, buscando tanto uma interação divertida entre os players (como em muitos jogos da Nintendo) quanto um distanciamento dos comuns jogos de PvP em que os players simplesmente batalham entre si.
* Para alcançar essa proposta foi definida uma gameplay baseada em hordas onde um ninja consegue interferir na gameplay do outro ao mesmo tempo em que acumula pontos para si. Tudo isso contribui para que seja incentivada uma competição divertida entre ambos.
* No decorrer da partida, surgirão hordas de monstros simultaneamente, uma para cada ninja e o os player deverão derrotá-las para sobreviver.
* Ao matá-los, haverá uma chance de dropar um item que, ao ser coletado, causará um efeito negativo (debuff) ao outro ninja, dificultando a luta contra a sua horda. Além disso, os monstros darão uma pontuação aos players que ao final da partida poderá ser convertida na criptomoeda do jogo.
* Com a alteração da proposta, foi removido o mapa antigo (de exploração).
* Foi criado o novo mapa e iniciado o processo de criação de inimigos. 
* Implementou-se um inimigo - cactus - com movimentação, path finding e animações para testagem inicial das mecânicas, sem as funções de dano.


## CheckPoint 3 - 23/11

* Iniciado o sistema de waves.
* Cooldown do ataque do player <br/>
* Sincronização completa:
	* Players
	* Ataques
	* Animações



## CheckPoint 4 - 30/11
* Waves completamente implementadas e com características programáveis:
	* Quantidade de inimigos.
	* Tipos dos inimigos
	* Tempo de duração da wave
* Novos inimigos, com animações movimentação e path finding:
	* Skeleton 	
	* Gold Knight
	* Dark Ninja
