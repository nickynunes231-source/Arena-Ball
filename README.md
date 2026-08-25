# Arena Ball

Um jogo moderno de futebol de botão, responsivo e sem dependências.

## Jogar
Ative **Settings → Pages → Deploy from a branch → main / root** para disponibilizar o jogo no GitHub Pages.

## Controles
- Mouse/toque: arraste a partir do botão para definir direção e força; solte para chutar.
- Teclado: setas chutam na direção indicada; Tab troca o botão ativo.

## Funcionalidades
- Menu, perfil e configurações persistidas em localStorage
- Criação/entrada em sala com código e lobby local
- Seleção de quatro equipes, uniforme e bola
- Placar, cronômetro, turnos, colisões, gol e tela de resultado
- Sons procedurais e estatísticas da partida
- Separação de estado de perfil, sala e jogo, preparada para um adaptador de multiplayer/WebSocket, catálogo de times/skins, campeonatos e ranking.

Nesta versão as salas são locais: o código e o fluxo de lobby já são a base da futura sincronização online.
