---
title: "A crescente diminuição do poder de compra"
date: 2022-05-08T20:30:40-03:00
draft: false
---
Breve análise do poder de compra utilizando o preço médio da gasolina, índice oficial da inflação e a perceção real no bolso do consumidor brasileiro.

{{< chart 100 400 >}}
{
    type: 'bar',
    data: {
        labels: ['2020', '2022'],
        datasets: [{
            label: 'Preço médio da gasolina no Brasil',
            data: [4.14, 7.53],
            backgroundColor: [
                'rgba(255, 205, 86, 0.2)',
            ],
            borderColor: [
                'rgba(255, 205, 86, 1)',
            ],
            borderWidth: 2,
            order: 2,
        }, {
            order: 1,
            type: 'line',
            label: 'Poder de compra',
            data: [4.14, 1.53],
            fill: false,
            borderColor: 'rgb(54, 162, 235)',
            borderWidth: 5,
        }]
    },
    options: {
        maintainAspectRatio: false,
        scales: {
            y: {
                max: 9,
                ticks: {
                    callback: function(value, index, ticks) {
                        return 'R$' + Chart.Ticks.formatters.numeric.apply(this, [value, index, ticks]);
                    }
                }
            }
        },
        plugins: {
            title: {
                display: true,
                text: "Comparativo do preço médio da gasolina entre 04/2020 e 04/2022 junto a desvalorização do poder de compra",
            },
        },
        layout: {
        }
    }
}
{{< /chart >}}

| Período       | Salário mínimo | Preço médio da gasolina | Poder de compra | IPCA |
|---------------|----------------|-------------------------|-----------------| -- |
| 04/2020 | R$1.045,00     | R$4,14                  | 252L            | 6,76% |
| 04/2022 | R$1.212,00     | R$7,53                  | 160L            | 11,3% |

> **O poder de compra entre 04/2020 e 04/2022 teve uma redução de 63%, logo R$4,14 de 04/2020 vale R$1,53 em 04/2022.**

Nenhuma aplicação de investimento rende acima da inflação oficial. R$10.000,00 aplicados em 04/2020 teriam o seu poder de compra reduzido em 63% subtraído o rendimento da aplicação no período, para 04/2022.

> **De modo a manter o poder de compra de 04/2020 em 04/2022, o salário mínimo deveria ser R$1.703,00.**

O IPCA (índice oficial da inflação) não condiz com a realidade, visto que o cálculo é baseado num conjunto centralizado de bens de consumo. Desse modo, está caracterizada a ausência da taxa de crescimento de injeção monetária — impressão de dinheiro, a razão pela existência da inflação.

Assim como automóveis e imóveis, todas as coisas estão inflacionadas. Logo, tudo aquilo que temos ou possuímos não estão valorizados e sim, desvalorizados, porém, buscando correção monetária baseado em interesses de mercado manipulados. A crise financeira de 2008, também conhecida como crise imobiliária ou grande recessão, foi um marco recente numa história prestes a se repetir.

Utilizamos dinheiro estatal para adquirir bens e fazer trocas. Esse dinheiro tem dono e não somos proprietários dele, afinal, não temos poder e controle da impressão. Bens trocados por esse dinheiro estatal também não se tornam nossa propriedade, sendo assim, propriedade privada é posse governamental e não individual.

Fazemos parte de uma lógica de mundo onde possuir "coisas" está cada vez mais caro, e não possuir nada é a melhor condição de estado. Estabilidade não existe e patrimônio não é segurança. Com isso, bancos mundiais tornam bilhões de pessoas reféns de boletos porque o sistema inflacionário mantém a máquina de dívidas ativa dessa maneira, em razão do dinheiro controlado.

Buscar construir *portfólio* de ativos escassos é o único meio pelo qual um indivíduo se torna soberano e capaz de cumprir os fundamentos da propriedade privada, da privacidade e da liberdade.