# 3D-CSS-Showtime
## Introdução
Esse repositório foi usado como estudo de caso de como aplicar técnicas CSS que trazem como resultado efeitos 3D, não só na intenção de criar ilusão de posicionamento em 3 dimensões, mas também emular shaders (iluminação, sombras, e cores) e pra finalizar criar um tipo arcaico de simulação.

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
      - radial-gradient aplicando circle at top para fazer a bola.
      - radial-gradient para aplicar efeito de iluminação no chão.
        No caso desenhando sombra no chão 
  - Técnicas de construção de padrões utilizando:
    - repeating-conic-gradient
  - Técnicas para suavização de animação
    - Usar animation-timing-function dentro de keyframes para criar novas suavizações.
  - Como é feita a rotação 3D dos elementos, pequenos detalhes:
    - A rotação é feita na raiz do elemento e não em seu centro. Ou seja caso deslocado,
      a rotação ocorrerá no ponto inicial antes do deslocamento.

## Honestidade Intelectual
Esse foi um projeto guiado, o código em sua maioria foi concepção de Amit Sheen, veja as referências abaixo), esse foi um laboratório para testar diferentes configurações e o que dava certo e errado no 3D também o que me tirou algumas dúvidas.

Foram feitos testes com diferentes configurações de animação, cores e sombras.

## Referências
Eu usei como base um vídeo do canal [Kevin Powell](https://www.youtube.com/kepowob), o vídeo em questão é o desse [link para youtube](https://youtu.be/NdftnCDwKaU) e esse vídeo conta com a participação de [twitter @amit_sheen](https://twitter.com/amit_sheen) que é um especialista em animações CSS e é famoso por GIFS de animações CSS fora do comum.
