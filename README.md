# Frontend Mentor - NFT preview card component solution

Essa é a solução do [NFT preview card component challenge do site Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U).  

## Tabela de conteúdo

- [Visão geral](#overview)
  - [O desafio](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Minha trajetória](#my-process)
  - [Construído com...](#built-with)
  - [O que eu aprendi](#what-i-learned)
  - [Desenvolvimento contínuo](#continued-development)
  - [Recursos úteis](#useful-resources)
- [Autor](#author)
- [Reconhecimentos](#acknowledgments)

## Visão geral

### O desafio

Usuários devem estar habilitados a:

- Ver o layout de forma otimizada independente do tamanho de tela do dispositivo que esteja sendo utilizado.
- Ver "hover" e "states" para elementos interativos na página.

### Screenshot

![Sem screenshots no momento, pois a página pode ser acessada online](./screenshot.jpg)

### Links

- Site URL: [Clique aqui e veja o projeto funcionando](https://vercel.com/philipeex/nf-tpreview-card-component)

## Minha trajetória

### Construído com...

- HTML5
- CSS3
- Flexbox
- Mobile-first

### O que eu aprendi

Entre os diversos detalhes envolvidos no projeto, o que mais me chamou a atenção - e que talvez tenha passado despercebido quando eu deveria ter aprendido antes - foi a dificuldade que encontrei ao tentar colocar o ícone de "olho" no centro da imagem da NFT quando o cursor do mouse passava por cima com o efeito hover. Isso ocorreu porque não sabia que seria possível alterar as características de um elemento específico ao definir o seletor "hover" para outro elemento.

```css
.conteudo-imagem:hover .icone-olho-nft{
    display: inline;
    opacity: .5;
}
```

### Desenvolvimento contínuo

-Propositalmente vazio

### Recursos úteis

- Não utilizei

## Author

- LinkedIn - [Philipe Rodrigues](https://www.your-site.com)