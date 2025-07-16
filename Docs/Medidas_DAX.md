| NAME           | Expression                                                                                                                                    |
| -------------- | --------------------------------------------------------------------------------------------------------------------------------------------- |
| % Cumplimiento | DIVIDE(<br>    COUNTROWS(FILTER('BPM Resultados', 'BPM Resultados'[Resultado] = "Cumple")),<br>    COUNTROWS('BPM Resultados'),<br>    0<br>) |
