# BreakNeon Rogue

BreakNeon Rogue é um jogo de navegador que combina a jogabilidade clássica de Breakout com progressão roguelite, chefes, relíquias permanentes, melhorias temporárias e diferentes tipos de blocos. O projeto foi desenvolvido como um exercício de vibe coding, explorando a criação e a evolução iterativa de um jogo completo com auxílio de inteligência artificial.

## Como jogar

Abra o arquivo `BreakNeon_Rogue.html` em um navegador moderno. O jogo não exige instalação, servidor local ou processo de compilação. É necessária conexão com a internet para carregar Tailwind CSS, Lucide Icons e as fontes do Google. Na versão com trilha sonora, mantenha o HTML e os arquivos MP3 na mesma pasta. A versão `BreakNeon_Rogue_Sem_Trilha.html` dispensa os arquivos de música e preserva os efeitos sonoros gerados pelo próprio jogo.

Use o mouse, o toque, as setas direcionais ou as teclas A e D para mover a raquete. Pressione Espaço, clique ou toque no campo para lançar a bola. O laser, quando adquirido, dispara automaticamente enquanto houver uma bola em movimento. A tecla P ou Esc pausa a partida.

## Modos de jogo

No modo Campanha, o jogador percorre cinco andares com níveis progressivamente mais difíceis, fases bônus entre os andares e um chefe ao final de cada setor. Os três primeiros andares possuem três níveis, o quarto possui quatro e o quinto possui cinco. A campanha termina após a vitória sobre o quinto chefe.

No modo Infinito, os campos são gerados continuamente com dificuldade crescente. A loja é aberta após cada limpeza, e o melhor resultado fica registrado no navegador.

## Principais recursos

O jogo inclui blocos regenerativos, invisíveis, teleportadores, congelantes, fortificados, elétricos e inquebráveis. Também oferece sistema de combos, loja de melhorias, multibolas, bola de fogo, bola perfurante, impacto crítico, laser automático, Holo Escudo, aumento de vida máxima e expansão da raquete.

Os cinco chefes possuem padrões de ataque telegrafados, períodos de invulnerabilidade e mecânicas próprias. O quarto chefe possui duas fases, o quinto possui três, e todos são imunes ao laser.

As fases bônus aparecem entre os andares e possuem uma quantidade de fileiras calculada pelo número do andar concluído multiplicado por dois, mais um. Uma das fileiras é formada apenas por blocos especiais. Ao concluir a fase, o jogador escolhe gratuitamente uma melhoria; ao perder, segue para o próximo andar sem a recompensa.

## Progressão e salvamento

As relíquias conquistadas ao derrotar chefes são permanentes. As compras realizadas na loja valem apenas durante a partida atual. Conquistas, relíquias, recordes e a partida em andamento são armazenados automaticamente no `localStorage` do navegador.

A opção “Iniciar um novo jogo” reinicia as relíquias da campanha. A opção “Continuar” recupera o progresso salvo. Limpar os dados do site no navegador também remove o salvamento.

## Estrutura para publicação

O arquivo principal com música é `outputs/BreakNeon_Rogue.html`. Os arquivos `Andar 2.mp3`, `Andar 5.mp3`, `Musica Chefes.mp3` e `Musica Menu.mp3` devem permanecer no mesmo diretório do HTML. O pacote `outputs/BreakNeon_Rogue_Com_Musicas_v3.zip` reúne essa versão e suas faixas.

A edição sem músicas está disponível em `outputs/BreakNeon_Rogue_Sem_Trilha.html` e pode ser distribuída como um único arquivo.

## Tecnologias

BreakNeon Rogue utiliza HTML, CSS e JavaScript em um único documento, com Canvas para renderização, Tailwind CSS para a interface e Lucide Icons para os ícones. Não há dependências de instalação nem etapa de build.

## Observação sobre o desenvolvimento

Este projeto é um exercício de vibe coding. As ideias, regras e decisões de design foram refinadas de forma incremental, enquanto a implementação foi produzida e revisada com assistência de IA. O objetivo é experimentar um fluxo criativo rápido sem deixar de validar sintaxe, funcionamento e consistência das mecânicas.

## Licença

Nenhuma licença foi definida até o momento. Antes de reutilizar, modificar ou redistribuir o projeto e suas faixas de áudio, confirme as permissões aplicáveis a cada arquivo.
