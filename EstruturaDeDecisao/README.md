# Lista de exercícios [link aqui](https://wiki.python.org.br/EstruturaDeDecisao)

***Uma adaptação dos exercícios de python para JavaScript.***
***Cada arquivo será uma Html com JavaScript fazendo o que o exercício deseja.***

1. Faça um Programa que peça dois números e imprima o maior deles
2. Faça um Programa que peça um valor e mostre na tela se o valor é positivo ou negativo
3. Faça um Programa que verifique se uma letra digitada é "F" ou "M". Conforme a letra escrever: F - Feminino, M - Masculino, Sexo Inválido
4. Faça um Programa que verifique se uma letra digitada é vogal ou consoante
5. Faça um programa para a leitura de duas notas parciais de um aluno.
    O programa deve calcular a média alcançada por aluno e apresentar
        A mensagem "Aprovado", se a média alcançada for maior ou igual a sete
        A mensagem "Reprovado", se a média for menor do que sete
        A mensagem "Aprovado com Distinção", se a média for igual a dez

6. Faça um Programa que leia três números e mostre o maior deles
7. Faça um Programa que leia três números e mostre o maior e o menor deles
8. Faça um programa que pergunte o preço de três produtos e informe qual produto você deve comprar, sabendo que a decisão é sempre pelo mais barato
9. Faça um Programa que leia três números e mostre-os em ordem decrescente
10. Faça um Programa que pergunte em que turno você estuda. Peça para digitar M-matutino ou V-Vespertino ou N- Noturno. Imprima a mensagem "Bom Dia!", "Boa Tarde!" ou "Boa Noite!" ou "Valor Inválido!", conforme o caso
11. As Organizações Tabajara resolveram dar um aumento de salário aos seus colaboradores e lhe contrataram para desenvolver o programa que calculará os reajustes
    Faça um programa que recebe o salário de um colaborador e o reajuste segundo o seguinte critério, baseado no salário atual
        salários até R$ 280, 00 (incluindo) : aumento de 20%
        salários entre R$ 280, 00 e R$ 700, 00 : aumento de 15%
        salários entre R$ 700, 00 e R$ 1500, 00 : aumento de 10%
        salários de R$ 1500, 00 em diante : aumento de 5%
    o salário antes do reajuste
    o percentual de aumento aplicado
    o valor do aumento
    o novo salário, após o aumento

12. Faça um programa para o cálculo de uma folha de pagamento, sabendo que os descontos são do Imposto de Renda, que depende do salário bruto (conforme tabela abaixo) e 3% para o Sindicato e que o FGTS corresponde a 11% do Salário Bruto, mas não é descontado (é a empresa que deposita). O Salário Líquido corresponde ao Salário Bruto menos os descontos. O programa deverá pedir ao usuário o valor da sua hora e a quantidade de horas trabalhadas no mês
    Desconto do IR
    Salário Bruto até 900 (inclusive) - isento
    Salário Bruto até 1500 (inclusive) - desconto de 5%
    Salário Bruto até 2500 (inclusive) - desconto de 10%
    Salário Bruto acima de 2500 - desconto de 20%

    Salário Bruto: (5 * 220): R$ 1100, 00(-) IR(5 % ): R$ 55, 00(-) INSS(10 % ): R$ 110, 00
    FGTS(11 % ): R$ 121, 00
    Total de descontos: R$ 165, 00
    Salário Liquido: R$ 935, 00

13. Faça um Programa que leia um número e exiba o dia correspondente da semana. (1-Domingo, 2- Segunda, etc.), se digitar outro valor deve aparecer valor inválido

14. Faça um programa que lê as duas notas parciais obtidas por um aluno numa disciplina ao longo de um semestre, e calcule a sua média. A atribuição de conceitos obedece à tabela abaixo

    Média de Aproveitamento Conceito
    Entre 9.0 e 10.0 A
    Entre 7.5 e 9.0 B
    Entre 6.0 e 7.5 C
    Entre 4.0 e 6.0 D
    Entre 4.0 e zero E

15. Faça um Programa que peça os 3 lados de um triângulo. O programa deverá informar se os valores podem ser um triângulo. Indique, caso os lados formem um triângulo, se o mesmo é: equilátero, isósceles ou escaleno
    Dicas
        Três lados formam um triângulo quando a soma de quaisquer dois lados for maior que o terceiro
        Triângulo Equilátero: três lados iguais
        Triângulo Isósceles: quaisquer dois lados iguais
        Triângulo Escaleno: três lados diferentes

16. Faça um programa que calcule as raízes de uma equação do segundo grau, na forma ax2 + bx + c. O programa deverá pedir os valores de a, b e c e fazer as consistências, informando ao usuário nas seguintes situações
    1. Se o usuário informar o valor de A igual a zero, a equação não é do segundo grau e o programa não deve fazer pedir os demais valores, sendo encerrado
    2. Se o delta calculado for negativo, a equação não possui raízes reais. Informe ao usuário e encerre o programa
    3. Se o delta calculado for igual a zero a equação possui apenas uma raiz real; informe-a ao usuário
    4. Se o delta for positivo, a equação possui duas raiz reais; informe-as ao usuário

17. Faça um Programa que peça um número correspondente a um determinado ano e em seguida informe se este ano é ou não bissexto.

18. Faça um Programa que peça uma data no formato dd/mm/aaaa e determine se a mesma é uma data válida.

19. Faça um Programa que leia um número inteiro menor que 1000 e imprima a quantidade de centenas, dezenas e unidades do mesmo
    Observando os termos no plural a colocação do "e", da vírgula entre outros
    326 = 3 centenas, 2 dezenas e 6 unidades
    12 = 1 dezena e 2 unidades

20. Faça um Programa para leitura de três notas parciais de um aluno. O programa deve calcular a média alcançada por aluno e presentar
    1. A mensagem "Aprovado", se a média for maior ou igual a 7, com a respectiva média alcançada
    2. A mensagem "Reprovado", se a média for menor do que 7, com a respectiva média alcançada
    3. A mensagem "Aprovado com Distinção", se a média for igual a 10

21. Faça um Programa para um caixa eletrônico. O programa deverá perguntar ao usuário a valor do saque e depois informar quantas notas de cada valor serão fornecidas. As notas disponíveis serão as de 1, 5, 10, 50 e 100 reais. O valor mínimo é de 10 reais e o máximo de 600 reais. O programa não deve se preocupar com a quantidade de notas existentes na máquina
    1. Exemplo 1: Para sacar a quantia de 256 reais, o programa fornece duas notas de 100, uma nota de 50, uma nota de 5 e uma nota de 1
    2. Exemplo 2: Para sacar a quantia de 399 reais, o programa fornece três notas de 100, uma nota de 50, quatro notas de 10, uma nota de 5 e quatro notas de 1

22. Faça um Programa que peça um número inteiro e determine se ele é par ou impar. Dica: utilize o operador módulo (resto da divisão).

23. Faça um Programa que peça um número e informe se o número é inteiro ou decimal. Dica: utilize uma função de arredondamento.

24. Faça um Programa que leia 2 números e em seguida pergunte ao usuário qual operação ele deseja realizar. O resultado da operação deve ser acompanhado de uma frase que diga se o número é
    1. par ou ímpar
    2. positivo ou negativo
    3. inteiro ou decimal

25. Faça um programa que faça 5 perguntas para uma pessoa sobre um crime.As perguntas são
    1. "Telefonou para a vítima?"
    2. "Esteve no local do crime?"
    3. "Mora perto da vítima?"
    4. "Devia para a vítima?"
    5. "Já trabalhou com a vítima?"

26. Um posto está vendendo combustíveis com a seguinte tabela de descontos.
    1. Álcool
    2. até 20 litros, desconto de 3% por litro
    3. acima de 20 litros, desconto de 5% por litro
    4. Gasolina
    5. até 20 litros, desconto de 4% por litro
    6. acima de 20 litros, desconto de 6% por litro

27. Uma fruteira está vendendo frutas com a seguinte tabela de preços
    Até 5 Kg Acima de 5 Kg
    Morango R$ 2, 50 por Kg R$ 2, 20 por Kg
    Maçã R$ 1, 80 por Kg R$ 1, 50 por Kg

28. O Hipermercado Tabajara está com uma promoção de carnes que é imperdível.Confira
    Até 5 Kg Acima de 5 Kg
    File Duplo R$ 4, 90 por Kg R$ 5, 80 por Kg
    Alcatra R$ 5, 90 por Kg R$ 6, 80 por Kg
    Picanha R$ 6, 90 por Kg R$ 7, 80 por Kg
