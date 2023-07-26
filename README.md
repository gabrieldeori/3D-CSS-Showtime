# 3D-CSS-Showtime
## Introdução
Esse repositório foi usado como estudo de caso de como aplicar técnicas CSS que trazem como resultado efeitos 3D, não só na intenção de criar ilusão de posicionamento em 3 dimensões, mas também emular shaders (iluminação, sombras, e cores) e pra finalizar criar um tipo arcaico de simulação de física.

## Quer ver o projeto rodando?
O projeto pode ser acessado em sua última build através deste [link](https://vercel.com/gabrieldeori/3d-css-showtime)
Escolhi o Vercel pela facilidade de colocar o projeto no ar, com poucos cliques um resultado satisfatório para o estudo é alcançado.

## O que foi aprendido
  - Técnicas de perspectiva com o uso de:
    - perspective
    - perspective-origin
    - transform-style: preserve-3d;
  - Técnicas de sombreamento usando:
    - box-shadow:
      - inset para uma espécie de efeito HBAO
      - outset no bottom para sombras
    - radial-gradient
      - aplicando circle at top para fazer a bola.
      - efeito de iluminação no chão. No caso desenhando sombra no chão.
  - Técnicas de construção de padrões utilizando:
    - repeating-conic-gradient
  - Técnicas para suavização de animação
    - Usar animation-timing-function dentro de keyframes para criar novas suavizações.
  - Como é feita a rotação 3D dos elementos, pequenos detalhes:
    - A rotação é feita na raiz do elemento e não em seu centro. Ou seja caso deslocado,
      a rotação ocorrerá no ponto inicial antes do deslocamento.
