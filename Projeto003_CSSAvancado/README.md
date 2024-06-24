# CSS animation

- a animação é definida peolo `@keyframes` nomeDaAnimacao  
- toda animação tem o inicio e o fim:

  • 0% ou from
  • 100% ou to

- para usar é necessário pelo menos 2 atributos do css:
  
  • 1. animation-name
  • 2. animation-duration

- caso queira puxar as informações de estado da animação exemplo mover um objeto e querer que permanecça no lugar é necessário usar o atributo:

  • 3. animation-fill-mode

- podemos alterar a propriedade da linha do tempo por exemplo colocar 50%: faz com que a animação vai e volte para o estado original

- é posivel também fazer com que animação ocorra várias vezes de ida e volta com os atributos:
  
  • 4. animation-direction
  • 5. animation-iteration-count

- podemos fazer com que a animação começe depois de um tempo com o atributo:

  • 6. animation-delay

- também podemos fazer com que a velocidade da animação se comporte diferente na sua decorrência com:

  • 7. animation-timing-function
    - podemos usar o: cubic-bazier(x1, y1, x2, y2)

- podemos também pausar uma animação exemplo em um hover com:

  • 8. animation-play-state: paused;

- temos o shorthand pra tudo isso:

  • 9. animation

