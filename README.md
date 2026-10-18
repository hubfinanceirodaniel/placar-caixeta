# Placar de caixeta

Marcador de pontos do jogo de caixeta, feito para o navegador do celular.

**Jogue aqui: https://hubfinanceirodaniel.github.io/placar-caixeta/**

Não precisa instalar nada. Abra o link e, se quiser um ícone na tela do celular,
use "Adicionar à Tela de Início" (iPhone) ou "Adicionar à tela inicial" (Android).

## Como funciona

- Cada jogador começa com os **pontos de entrada** (padrão 10) e vai perdendo.
- Por rodada você marca **só quem vai**. O resto o sistema deduz: quem não foi
  perde 1, quem foi e não ganhou perde 2, quem ganhou não perde nada. Os três
  valores e os pontos de entrada são configuráveis, antes ou durante o jogo.
- Rodada em que alguém foi **não fecha sem ganhador**: o botão vira "Quem
  ganhou?" e lista só quem foi. Rodada em que ninguém foi salva direto.
- Quem chega a zero fica **fora**; o último com pontos ganha o jogo.
- O placar fica salvo no próprio aparelho, então dá para fechar e voltar depois.
  Cada celular guarda o seu — o placar não é compartilhado entre aparelhos.
- Menu `⋯`: incluir jogador no meio do jogo, tirar quem desistiu, ajustar
  pontos à mão, mudar as regras, zerar o placar ou começar um jogo novo. O
  botão `↶` desfaz a última rodada.
- Quem desiste sai das rodadas seguintes e não disputa o campeonato, mas
  continua no histórico das rodadas que jogou.

## Sobre o código

É um arquivo só, `index.html`, com tudo dentro: nada de dependência, build ou
servidor. Para mexer, edite o arquivo e abra no navegador.
