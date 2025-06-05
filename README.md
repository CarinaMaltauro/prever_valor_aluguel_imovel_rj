## Licença
Este projeto está licenciado sob a Licença Apache 2.0.

## Atribuição obrigatória
De acordo com os termos da licença Apache 2.0, qualquer pessoa que reutilizar este código (total ou parcialmente) deve incluir atribuição ao autor original:

Código criado por @CarinaMaltauro

A atribuição pode ser feita:

Nos arquivos de código (comentários)

Na documentação do projeto derivado

Ou em qualquer local visível e apropriado


<h1 align="center">Projeto Airbnb Rio - Previsão de Preço Médio de Aluguel de Imóvel  <img src="https://cdn-icons-png.freepik.com/256/258/258530.png?ga=GA1.1.763163565.1742925562&semt=ais_hybrid" width="25" heigth="25" > </h1>

<p align="center">Carina R P M Dias</p>

## Objetivo

Criar um modelo de previsão de preço de aluguel que permita estimar o valor das diárias de um imóvel comum, excluindo imóveis de alto padrão. Dessa forma, um locador, sem o conhecimento prévio dos preços de imóveis semelhantes ao seu, poderá estimar o preço médio do aluguel do seu imóvel no Airbnb. Da mesma forma, um locatário poderá verificar se o imóvel que está buscando no Airbnb está dentro da média de preços, considerando a localidade e as características do imóvel. A consulta ao preço estimado de aluguel deverá ser feita por meio de um link disponibilizado pelo Streamlit, que conterá um formulário a ser preenchido pelo usuário.



## Instruções

DADOS: https://www.kaggle.com/code/allanbruno/helping-regular-people-price-listings-on-airbnb/input?select=total_data.csv

IDE: Projeto construído no Anaconda Jupyter Notebook.

INSTALAÇÕES: joblib e streamlit foram realizadas no Anaconda Prompt no diretório base do usuário.

TESTE DE DEPLOY: Passe o arquivo deploy.ipynb para deploy.py. No terminal Anaconda Prompt entre na pasta do projeto e rode "streamlit run deploy.py" sem as aspas.



## Resultados

A princípio, mês e ano foram considerados como possíveis fatores de interferência no preço das diárias do imóvel; no entanto, esses fatores não influenciaram tanto o preço. Por outro lado, quartos, latitude, longitude e o número de comodidades apresentaram uma importância expressiva. A quantidade de quartos pode sugerir que "locatários priorizam a privacidade, a divisão de custos e realizar viagem com família ou amigos". A influência da latitude e longitude está de acordo com o esperado, refletindo a importância da localização. Já o fator número de comodidades não se relaciona de forma diretamente proporcional ao preço, o que pode estar relacionado à qualidade das comodidades, pois uma churrasqueira pode ser mais atraente do que um ventilador, cozinha equipada ou cortinas.


