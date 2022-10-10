# Repositorio do portfolio

##Tecnologias utilizadas
-HTML
-CSS
-JS

## Biblioteca

Utilizei a biblioteca typed.js para fazer o efeito de digitação.

## Como usar

Primeiro de tudo é necessário fazer o download da biblioteca através desse link: https://github.com/mattboldt/typed.js/

Após instalar, adicione a pasta do seu projeto e o insira na tag script

<script src="typed.js"></script>

<script>
    var typed = new Typed('.type', {
        strings: [
          "Desenvolvedor Front End",
          "Formado em Análise e desenvolvimento de sistemas",
          "Apaixonado por JavaScript"
        ],
        typeSpeed: 60,
        backSpeed: 100,
        loop: true
      });
</script>

Desta maneira. Insira dentro das strings o que deseja escrever e a velocidade da digitação e de quando apaga