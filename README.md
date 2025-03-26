<h1 align="center">Projeto Airbnb Rio - Previsão de Preço Médio de Aluguel de Imóvel  <img src="https://cdn-icons-png.freepik.com/256/258/258530.png?ga=GA1.1.763163565.1742925562&semt=ais_hybrid" width="25" heigth="25" > </h1>

<p align="center">Carina Maltauro</p>

## Objetivo

Criar um modelo de previsão de preço de aluguel que permita estimar o valor das diárias de um imóvel comum, excluindo imóveis de alto padrão. Dessa forma, um locador, sem o conhecimento prévio dos preços de imóveis semelhantes ao seu, poderá estimar o preço médio do aluguel do seu imóvel no Airbnb. Da mesma forma, um locatário poderá verificar se o imóvel que está buscando no Airbnb está dentro da média de preços, considerando a localidade e as características do imóvel. A consulta ao preço estimado de aluguel deverá ser feita por meio de um link disponibilizado pelo Streamlit, que conterá um formulário a ser preenchido pelo usuário.



## Instruções

Para mais informações sobre dados, instalações e procedimentos de deploy, vide requirements.txt.


## Resultados
A princípio, mês e ano foram considerados como possíveis fatores de interferência no preço das diárias do imóvel; no entanto, esses fatores não influenciaram tanto o preço. Por outro lado, quartos, latitude, longitude e o número de comodidades apresentaram uma importância expressiva. A quantidade de quartos sugeriu que "locatários priorizam a privacidade". A influência da latitude e longitude está de acordo com o esperado, refletindo a importância da localização. Já o fator número de comodidades não se relaciona de forma diretamente proporcional ao preço, o que pode estar relacionado à qualidade das comodidades, pois uma churrasqueira pode ser mais atraente do que um ventilador, cozinha equipada ou cortinas.


