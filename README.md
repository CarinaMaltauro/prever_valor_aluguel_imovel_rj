<h1 align="center">Projeto Airbnb Rio - Previsão de Preço Médio de Aluguel de Imóvel  <img src="https://cdn-icons-png.freepik.com/256/258/258530.png?ga=GA1.1.763163565.1742925562&semt=ais_hybrid" width="25" heigth="25" > </h1>

<p align="center">Carina R. P. M. Dias</p>

## Objetivo

Criar modelo de previsão de preço de aluguel que permita estimar o valor de diárias de um imóvel comum. Não são considerados os
imóveis de alto padrão. Sendo assim, um locador, sem o conhecimento de preços de imóveis equiparados ao seu, terá a possibilidade
de estimar o preço médio do aluguel de seu imóvel no Airbnb. Já um locatário terá a possibilidade de estimar se o imóvel
procurado no Airbnb está dentro da média de valores segundo a localidade e as características do imóvel.


## Instruções

Para mais informações sobre dados, instalações e procedimentos de deploy, vide requirements.txt.


## Conclusão

A princípio, a sazonalidade foi considerada como um possível fator de interferência no preço das diárias do imóvel, no entanto,
as variáveis month e year não interferiram tanto no preço. Já bedrooms, latitude, longitude e n_amenities (número de comodidades)
possuem expressiva importância. Bedrooms sugere que "locatários priorizam a privacidade". A importância de latitude e longitude
estão de acordo com o esperado em relação a localidade. E o fator n_amenities não interfere de forma diretamente proporcional
no preço, isso pode estar relacionado a qualidade das amenities, pois uma churrasqueira pode ser mais interessante que ventilador,
panelas e cortinas.

