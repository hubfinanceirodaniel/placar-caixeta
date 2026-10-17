# Placar de caixeta

Marcador de pontos do jogo de caixeta, feito para o navegador do celular.

**Jogue aqui: https://hubfinanceirodaniel.github.io/placar-caixeta/**

Não precisa instalar nada. Abra o link e, se quiser um ícone na tela do celular,
use "Adicionar à Tela de Início" (iPhone) ou "Adicionar à tela inicial" (Android).

## Como funciona

- Cada jogador começa com os **pontos de entrada** (padrão 10) e vai perdendo.
- Por rodada, cada um é marcado como **não foi** (−1), **ganhou** (0) ou
  **foi e perdeu** (−2). Os três valores e os pontos de entrada são
  configuráveis, antes ou durante o jogo.
- Quem chega a zero fica **fora**; o último com pontos ganha o jogo.
- O placar fica salvo no próprio aparelho, então dá para fechar e voltar depois.
  Cada celular guarda o seu — o placar não é compartilhado entre aparelhos.
- Menu `⋯`: incluir jogador no meio do jogo, ajustar pontos à mão, mudar as
  regras, zerar o placar ou começar um jogo novo. O botão `↶` desfaz a última
  rodada.

## Sobre o código

É um arquivo só, `index.html`, com tudo dentro: nada de dependência, build ou
servidor. Para mexer, edite o arquivo e abra no navegador.
