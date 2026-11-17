<sub>**Datas:** pasta 17/01/2024 · código 17/01/2024 (`dados.xlsx`)</sub>

# Enem — proporção de nota máxima por região

Testes de proporção (`prop.test`) comparando fração de nota máxima entre **regiões** do Brasil.

## O que o código faz

`enem.Rmd`:

- Lê contagens por região em `dados.xlsx`.
- Combina com vetor fixo `notas_regioes` (contagens de nota máxima por região).
- Intervalos de confiança e gráfico comparativo.

## Dados

`dados.xlsx` — colunas usadas: `Regiao` e a 2ª coluna (população ou base de referência para o teste).

Ajuste o path no Rmd se não for `C:/R/Enem Notas/dados.xlsx`.

## Como rodar

Knit `enem.Rmd` (`readxl`).