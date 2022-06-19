# Aprenderemos a nos comunicar com o usuario.

Conhecemos o comando document.white

Aprendi a fazer contas e a quebrar linha com a tag <br>

Primeiro contato com var em Javascript;

Math.round = arrendondar um número decimal.



## Desafio (Calculo Consumo)

Agora, vamos fazer um exercício completamente novo:
1) Crie um novo arquivo, o calcula_consumo.html, colocando um título de desta-
que na primeira linha: <h3>Álcool ou Gasolina?</h3>. Logo abaixo, insira as
já conhecidas tag de <script> e </script>. O arquivo está pronto para adicio-
narmos o código do nosso programa. Salve-o e abra-o no navegador.
2) Seu carro tem um tanque de 40 litros.
Com gasolina, e usando todo o
tanque, você fez um caminhoComGasolina de 480 quilômetros.
Qual é o
consumoDeGasolina? Para calculá-lo, divida a distância percorrida pela quan-
tidade de litros gasto. Imprima esse valor, organizando suas contas em variáveis.
É comum utilizar uma variável dessa forma, como consumoDeGasolina. A letra
D e G facilitam a leitura. Compare consumoDeGasolina com consumodegasolina.
E fique atento: se você errar o maiúscula/minúscula depois que criar a variável, o
código não funcionará como esperado.
3) Já com álcool, o mesmo tanque de 40 litros fez um caminhoComAlcool de 300
quilômetros. Qual é o consumoDeAlcool?
4) Os números são todos quebrados, cheios de dígitos. Utilize o Math.round para
arredondá-los. Funciona bem?
5) Arredondar um número pequeno, como 0.314178473, vai dar 0! Faz sentido,
mas não é o que queríamos. Gostaríamos de arredondar 0.314178473 para
ter apenas duas casas decimais, por exemplo. Pra fazer isso, você deve utilizar
24
E-book gerado especialmente para Jarbas Gomes Duarte Neto - elcid1466@gmail.com
Casa do Código
Capítulo 2. Comunique-se com o usuário
numero.toFixed(2), sendo que o 2 é um parâmetro indicando quantas casas de-
cimais queremos.
Repare que estamos chamando uma função de maneira bem diferente. Antes
fazíamos Math.round(numero) e agora fazemos numero.toFixed(2). Além do
nome da função ser diferente, dessa vez a variável numero aparece “na frente”
da chamada. Isso aparece bastante no JavaScript e tem sim uma diferença, que
entederemos em capítulos posteriores.
6) Agora um desafio. Hoje, o precoDaGasolina está R$2.90 e o precoDoAlcool
R$2.40. Qual é o precoPorKilometro, tanto do álcool quanto da gasolina? Dica:
dividindo o preço do litro pelo consumo, temos o preço por quilometro. Qual é
o menor deles?

# Parei na pagina 25!!!