# Case-Kognita
O arquivo "Case Kognita"contém o notebook com os códigos em python para os 10 exercícios. O Exercício 9 eu não fiz, fiquei em dúvida em como considerar a renda per capita de 100 mil habitantes e mesmo assim plotar os   muicípios.

A pasta mapas contém os mapas dos exercícios 2,3 e 4.

## Exercício 11 - Conclusões do Estudo
Retirei o município de São Paulo dos mapas com os POIs porque era um município com um número de pontos de interesse bem maior que os outros, e estava distorcendo a escala.
Os valores do coeficiente I de Moran global ficaram entre 0.19 e 0.31 (dependendo do método utilizado) na quantidade de POIs a nível de município, o que denota uma correlação positiva, mas não muito expressiva entre a quantidade de pois os municípios.
Os valores do coeficiente I de Moran global para o faturamento total em nível de município ficou entre 0.18 e 0.26 (dependendo do método) o que novamente indica uma correlação pouco expressiva, mas positiva, do faturamento total e a proximidade dos municípios.
Pensando nisso, resolvi encontrar quais seriam bons municípios no estado de São Paulo para se construir uma nova unidade dessa rede de varejo. Retirei os municípios onde a concorrência era muito alta, ou seja, com muitos POIs classificados como comércio, padaria ou supermercado. Pensando no coeficiente I de Moran global, retirei também municípios próximos desses de grande concorrência e também os municípios onde a tendência de faturamento prevista estava abaixo da mediana das unidades já estabelecidas, além de municípios com baixo faturamento.
Usei como parâmetro os municípios com unidades com o maior faturamento médio e com tendência de aumentar o faturamento, e busquei os municípios próximos. Mas não encontrei nenhum município que obedecesse todos esses requisitos, então ficaria como sugestão fazer uma nova unidade em municípios vizinhos de outros que tivessem unidades bem-sucedidas, com alto faturamento médio ou tendência de alta, como por exemplo Ubatuba, São Sebastião ou Bertioga.
