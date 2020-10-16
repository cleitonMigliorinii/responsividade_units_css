Responsividade
---

Criar um layout flexível, algo que se ajuste a qualquer dispositivo, seja ele
smartphone, tables, desktop, tv, geladeira...

Principal ponto da aula é : entender as estratédias de CSS Units para ajustar nossos conteudos para que fiquem fluidos.

FONT-SIZE PADRÃO = 16px;

https://www.w3schools.com/cssref/css_units.asp

Units fixas: 
---
O tamanho vai ser fixo e vai ser "renderizado" na tela o tamanho
proposto no atributo.

Layout fixo -

px - pixels
cm - centimeters
pt - points

Texto fixo -

px - pixels

1px = 0.75pt
1.5pt = 2px

conversor :
https://www.blitzresults.com/pt-br/pixel/


Units relativos ( flexível ) (Fluido)
---
Comprimento seja relativo a algum objeto.

100% -> 1920px;
100% -> 720px;

Layout Fluido -

% - Porcetagem
auto - Automatico
vh - Viewport Height
vw - Viewport Width

Texto fluido -

em - Relative to the font-size of the element
---

Exemplo em 1 - 
    div -> h1
    div - font-size : 16px;
    h1 - font-size: 1em;

    1em = 16px; 

    2em = (16px * 2em) = 32px;

Exemplo em 2 - 
    div -> h1
    div - font-size : 14px;
    h1 - font-size: 1em;

    1em = 14px; 

rem - Relative to font-size of the root element
---

r (r de root) -- em (Se nao tiver valor pega o valor padrao == 16px)

Exemplo em 3 - 
div -> h1
div - font-size : 14px;
h1 - font-size: 2em;

2em = (14px * 2em) = 28px; 

rem (r de root)

Quando usar o rem vai utilizar como base de multiplicação o
font-size do html ou *;


