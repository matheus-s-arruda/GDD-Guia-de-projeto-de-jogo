# Guia de Documento de Game Design
[![Generic badge](https://img.shields.io/badge/versão-1.1.1-red.svg)](https://shields.io/)
</br></br>
Modelo de GDD para elaboração de um projeto de jogo.</br>
Veja também [mini gdd](mini-gdd.md), uma versão reduzida e direta (focada em gameJans).

## Como utilizar:
A ideia de elaborar essa documentação pra teu jogo não segue uma orientação em serie, o propósito não é terminar todos os tópicos para começar o projeto, mas utilizar esse planejamento para organizar a elaboração do projeto final, utilizando de mudanças, remoções e readaptações de definições "propostas" aqui.
Seguindo essa lógica, não é esperado que todos os tópicos sejam utilizados, variando de escopo e de usuário. Porém, elaborar as [Definições gerais](#definições-gerais) e as [Regras do jogo](#regras-do-jogo) é crucial para qualquer jogo, seja fisico ou virtual.

Qualquer duvida abre uma _Issue_, Tmj fml 🤙.

---
### Sumário
- [Definições gerais](#definições-gerais)
- [Regras do jogo](#regras-do-jogo)
- [Elementos](#elementos)
- [Historia](#historia)
- [Mecânicas](#mecânicas)
- [Arte](#arte)
- [Conclusão do projeto](#conclusão-do-projeto)
---

## Nome do jogo
##### Slogan: _"Frase de impacto que anunciará esse jogo"_

## Definições gerais
##### Tags:
Etiquetas sobre o jogo, ex: `2D` `3D` `pixel art` `fps`

##### Ambição:
Qual sua ambição para a experiência do jogador? qual o objetivo que deseja alcançar com esse jogo? 
</br>(O proprosito geral desse topico é servir de pré-requisito e servir de orientação na idealização, de forma que busque sempre atender esse objetivo)

##### Resumo:
Uma frase ou paragrafo curto que explique o momento atual do inicio do jogo, a situação que estará no final do jogo e o meio ou contexto de como alcançar.
<br>(Requisito ou foco geral do projeto, a progressão do jogo não deve sair deste contexto)

##### Referencias:
Base de inspiração, explique também o porque dessa inspiração.

##### Semelhantes/concorrencia:
Jogos que tem o mesmo principio ou jogabilidade.

##### Proposta para o mercado de jogos:
Qual o diferencial que esse jogo tem que o torma especial.

##### Proposta de valor:
- Custo do deselvolvimento
- modelo de monetização

##### Como se joga:
- Como é a gameplay
- Qual o nivel de dificuldade do jogo

##### Requisitos:
- Publico alvo: idade minima estipulada
- Hardware: requisitos minimos pra rodar o jogo
- Condição fisica: risco a saude, como epilepsia, ou caso o jogo precise de utilizar membros, como os braços ou andar

##### Plataformas:
Console, mobile, Pc ou fisico

## Regras do jogo
##### desafios:
Qual o principal desafio do jogo, e quais os outros possiveis desafios que o jogador poderá encontrar.

##### evolução:
Qual o estado inicial do jogador e qual seu estado no final do jogo.</br>
Como é o deselvolvimento do jogador durante o jogo.

##### conclusão:
Como é o final do jogo, como se comporta os elementos no final do jogo.
Se o jogo não tem fim, qual a conclusão para o deselvolvimento do jogador e dos elementos.

## Elementos
##### Entidades:
Quem são os atores, ex: _os npcs, os inimigos, o mundo, o tabuleiro, as peças, os itens_

##### O jogador:
Oque é, ou quem é o jogador dentro do jogo.

##### encontros/relacionamentos:
Como o jogador interage com as entidades, como as entidades interagem entre si(isso é sobre o contexto, não sobre i.a ou comportamento)

##### Pontuações:
Há pontuações? Há coletáveis ou conquistas? 

## Historia
#### Lore: (Se tiver historia, claro.)
Toda a trama do teu jogo em detalhes.

##### Historia de fundo:
qual a historia que se passa antes do inicio do jogo

##### Momento atual no jogo:
Qual o ponto de partida que o jogador se encontra na historia.</br>
Qual o objetivo do jogador de acordo com a historia.

##### Situação no(s) final(is) do jogo:
Como é os finais do jogo, e como afeta a historia como um todo.

#### Encontros:
Eventos durante o jogo que contribuem pra avançar na trama.

| Nome do acontecimento | Condição para acontecer | Resultado do acontecimento |
| --------------------- | ----------------------- | -------------------------- |
| _Dialogo com NPC Fulano_ | _O jogador entra no vilarejo pela primeira vez_ | _O Jogador ganha a missao "salvar a princesa"_ |

## Mecânicas
##### Controles
Quais são os controles, qual hardware utiliza, se possivel adicione uma imagem para melhor entendimento.</br>
Exemplo:
| ação | tecla |
| ---- | ----- |
| mover para cima | A |
| mover para baixo | S |

##### Inteligencia artificial:
Como o jogo se comporta sem a interação do jogador, ou interação indiretamente (ex: campo de visão do inimigo)

##### Interações do jogador:
- Quais elementos que o jogador pode interagir.
- Oque e como acontece nessas interações.

##### eventos automatizados estaticos
Comportamento do jogo que pode afetar outros comportamentos e que o jogador não possui interação direta.</br>
ex: 
- ciclo dia e noite
- clima

## Arte
##### Temática:
Qual o teor artistico do jogo, qual o tema ou os temas que o jogo terá

##### Estilos:
Descreva qual e o porque desse estilo, ex:
- minimalista: _"Combina com a ideia geral do jogo"_
- pixel art: _"Escolhido por meio da capacidade do grupo"_
- instrumental: _"Retrata bem o ambiente buscado"_

## Conclusão do projeto
##### Créditos:
Material e ferramentas usadas, membros da equipe, menções a auxilios.

##### Desvio da idealização inicial:
Oque foi mudado durante o desenvolvimento em relação ao design e o porque.

##### Defeitos e mudanças posteriores:
Complicações e próximos passos depois da finalização, tal como:
- dlcs
- versões exclusivas
- reajuste de publico alvo
- feedback negativo de elementos




