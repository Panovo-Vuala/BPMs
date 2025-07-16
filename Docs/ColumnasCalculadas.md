| TableID | Column Name  | Expression                       | FormatString |
| ------- | ------------ | -------------------------------- | ------------ |
| 12      | DíasAbiertos | DATEDIFF([FECHA], TODAY(), DAY)  | 0            |
| 12      | Semana       | WEEKNUM('BPM Resultados'[FECHA]) | 0            |
