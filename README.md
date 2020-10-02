<h1> Formulário animado com JS puro e CSS Animation </h1>

<h2> Desafios </h2>

- [x] Fazer o formulário aparecer, suavemente, quando a página abrir;
- [x] Fazer os campos aparecerem da esquerda para direita, suavizando a entrada e fazendo-os entrar em momentos distintos;
- [x] Quando clicar em Login, fazer o formulário sair da tela, indo para baixo;
- [x] Remover formulário do html e não mostrar rolagem enquanto o formulário está saindo da tela;
- [x] Adicionar um efeito diferente de timing para a saída do formulário;
- [x] Fazer o formulário dizer não-não (vibrar) caso haja campos vazios;
- [x] Criar alguns quadrados animados (que fiquem girando) e que saem de baixo da tela (fora do campo de visão) e vão para cima da tela (que saia do campo de visão também). Detalhes: Deve ter tamanhos diferentes, sairem em momentos diferentes, terem timing diferente, animação contínua.

<h3> Animation </h3>

8 propriedades:

- animation-name: animationname;
- animation-duration: 2s;
- animation-delay: 3s;
- animation-fill-mode: none;
- animation-play-state: running;
- animation-timing-function: ease;
- animation-direction: reverse;
- animation-iteration-count: infinite;

```css
@keyframes animationname {
    0% {

    }

    100% {

    }
}
```

Múltiplas animações em um mesmo elemento: 
```css
.animate {
    animation: slide-tpo 2s, bounce 1s, fade 0.2s;
}
``` 

<h2> Referencias </h2>

[CSS Animation Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Animations/Using_CSS_animations)

[Animation Timing Docs](https://developer.mozilla.org/en-US/docs/Web/CSS/animation-timing-function)

[Site para criar animações](http://animista.net/play/basic/scale-up)

[Site para criar cubic Bézier timming](https://matthewlein.com/tools/ceaser)