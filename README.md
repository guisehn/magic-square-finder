# Magic Square Finder (brute force)

[⬇️ Download da última versão](https://github.com/guisehn/magic-square-finder/releases/latest)

Trabalho Prático de Inteligência Artificial - UNISC 2016/1

Este aplicativo encontra [quadrados mágicos](https://pt.wikipedia.org/wiki/Quadrado_m%C3%A1gico) através de permutação (força bruta). Um quadrado mágico é uma tabela quadrada de números em progressão aritmética em que a soma de cada coluna, de cada linha e das duas diagonais são iguais.

Este aplicativo encontra quadrados mágicos através de força bruta. Quadrados mágicos são matrizes quadradas onde
a soma de todas as linhas e colunas, e das diagonais principais e secundárias, resultam no mesmo valor.

![Quadrado mágico](https://wikimedia.org/api/rest_v1/media/math/render/svg/3bc23e727d4029de3d46c2b70b8eafd4fa718b70)

Ele demora em média um segundo para encontrar todos os quadrados mágicos 3x3 (são oito), e de cinco a sete horas para encontrar os primeiros dez quadrados mágicos de tamanho 4 (testado em um [MacBook Pro 13" early 2015](https://support.apple.com/kb/sp715?locale=en_US)). Quadrados de tamanhos maiores não foram testados.

Este programa não utiliza nenhuma técnica de inteligência artificial, apenas força bruta. Foi desenvolvido para comparar a eficiência com uma versão desenvolvida utilizando algoritmo genético, que pode ser encontrada em: https://github.com/guisehn/genetic-magic-square-finder
