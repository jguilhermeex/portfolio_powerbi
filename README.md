# Projeto de Análise de Dados - Case Netflix
<div style="display: flex; justify-content: space-between;"> <br>
<img width="1000" alt="netflix" src="https://user-images.githubusercontent.com/120759992/235283693-2ca603e9-0d99-4032-a7d7-1ea06f451847.PNG">

# Sobre o Projeto:
- Este projeto analisou o catálogo da Netflix para identificar tendências e padrões no conteúdo disponível. Com base nos dados examinados, foram sugeridas ações para aprimorar o catálogo e conquistar novos públicos. O projeto apresenta insights valiosos que podem ajudar a Netflix a tomar decisões estratégicas em relação ao conteúdo disponibilizado.
<br />

# Etapas do Projeto (DataOps)
- Definição do Problema de Negócio
- Mapeamento dos Dados
- Escolha das Ferramentas - Softwares Utilizados
- ETL (Extração, Transformação e Carregamento)
- Desenvolvimento do Dashboard
- Insights e Recomendações
<br />

# Problema de Negócio
Como a Netflix pode otimizar a composição do seu catálogo para atender às preferências do público, considerando o número e a evolução das produções, as classificações etárias e a presença de diferentes países, a fim de oferecer uma experiência personalizada aos seus usuários?

Para isso, podemos quebrar o problema em perguntas específicas:
 
 - Qual é o número de produções no catálogo da Netflix?
 - Qual é a porcentagem de filmes e programas de TV no catálogo da Netflix e como tem sido a evolução ao longo dos anos?
 - Existe alguma correlação entre o aumento da porcentagem de filmes e programas de TV no catálogo da Netflix?
 - Quais são as classificações indicativas mais presentes no catálogo da Netflix?
 - Quais são os países com mais produções no catálogo da Netflix?
<br />

# Mapeamento dos Dados
- Os dados se encontram em um arquivo de formato CSV (Separado por vírgulas) conforme amostra abaixo:
<img width="1000" alt="Imagem dados" src="https://user-images.githubusercontent.com/120759992/234710323-ebea7c42-f5b3-445e-8142-de7e041ecc76.PNG">
 
<br />
 
# Softwares Utilizados
- Microsoft Excel
- Microsoft Power BI
 
<br />
 

# ETL (Extração, Transformação e Carregamento)
### Preparação dos dados
- Limpeza, transformação, modelagem, checagem da qualidade dos dados, etc.
### Análise exploratória
- Extração de estatísticas descritivas relevantes.

 <img width="1000" alt="ETL" src="https://user-images.githubusercontent.com/120759992/234715009-41cd4875-6830-4f42-b3d2-2a84dda0405c.PNG">
 
<br />
  
<br />
 
 
  
# Dashboard Interativo
- [Clique aqui para visualizar o dashboard de maneira interativa](https://app.powerbi.com/view?r=eyJrIjoiZWUwNDNhYTgtZjI0Yi00YTRiLWE5MzItOWYwZWZiM2YyOTg1IiwidCI6ImQ2ZjhiMGIwLTRiNzEtNDE1Yy1iODczLTk4ZDY3Mzc3MzhiZCJ9)

<br />

<img width="1000" alt="Dashboard Final" src="https://user-images.githubusercontent.com/120759992/235281875-717c99ae-996e-4478-8f2e-533674e9dc70.PNG">


<br />
<br />


# Insights
 
## Evolução do cátalogo ao longo do tempo
 
- Observa-se oscilações na proporção de filmes para programas de TV ao longo dos anos analisados, com um aumento mais significativo dos filmes em relação aos programas de TV entre 2017 e 2018, e uma queda mais acentuada em 2020. No geral, os filmes apresentaram um crescimento maior em relação aos programas de TV.

Abaixo a proporção do catálogo desde 2015:

- 2015: 58 filmes / 30 programas de TV = 1.93 filmes por programa de TV. 
- 2016: 258 filmes / 185 programas de TV = 1.39 filmes por programa de TV. 
- 2017: 864 filmes / 361 programas de TV = 2.39 filmes por programa de TV. 
- 2018: 1255 filmes / 430 programas de TV = 2.92 filmes por programa de TV.
- 2019: 1497 filmes / 656 programas de TV = 2.28 filmes por programa de TV.
- 2020: 1312 filmes / 697 programas de TV = 1.88 filmes por programa de TV.
 
 <br />
 
 ## Classificação Indicativa
 
- As classificações indicativas TV-MA, TV-14 e TV-PG são as líderes no dashboard da Netflix desde 2015 com TV-MA sempre na liderança.

- A classificação TV-MA, que significa "apenas para adultos", é a que tem a maior popularidade e pode indicar que um público mais adulto consome as produções da plataforma. A classificação TV-14, que significa "adequado para maiores de 14 anos", também é popular entre os usuários da Netflix, enquanto a classificação TV-PG, que significa "orientação parental sugerida", é mais adequada para crianças.

- Embora as classificações indicativas sejam importantes para orientar o público sobre o conteúdo, também é interessante observar que todas as três classificações têm mais filmes do que programas de TV no catálogo da Netflix.
 
 <br />
 
 ## Países
 
- Os Estados Unidos têm sido o país com maior número de produções no catálogo da Netflix ao longo dos anos, enquanto a Índia ocupa o segundo lugar, porém com uma diferença significativa em relação ao número de títulos.
 
- Do TOP 10, apenas Reino Unido, Japão e Coreia do Sul possuem mais programas de TV do que filmes.
 
 <br />
 
 # Recomendações ao tomador de decisão
 
 - Analisar a demanda por filmes e programas de TV entre os usuários da Netflix e ajustar o catálogo de acordo com essas tendências.
 - Considerar a inclusão de mais programas de TV em relação aos filmes no catálogo, caso haja uma tendência de crescimento na demanda por esse tipo de conteúdo.
 - Explorar a possibilidade de produzir mais conteúdo com classificações indicativas TV-MA e TV-14, já que essas classificações são as mais populares entre os usuários da Netflix.
 - Investir em produções oriundas de países que apresentam um potencial de crescimento no número de títulos no catálogo da Netflix, como é o caso da Índia.
 - Analisar o desempenho de produções de países como Reino Unido, Japão e Coreia do Sul, que possuem mais programas de TV do que filmes, e considerar a inclusão de mais produções desses países no catálogo da Netflix.
<br />

# BÔNUS - Dica de Ferramenta - Tooltip
- As dicas de ferramentas no Power BI permitem análises dentro de outras análises, conforme mostrado no vídeo abaixo.
- OBS: Algumas atualizações foram feitas nos campos do dashboard. Durante a gravação, o dashboard ainda estava sendo modificado até chegar à versão final que está armazenada neste repositório.

https://user-images.githubusercontent.com/120759992/234713590-4d1ed1e8-6b7b-40c2-a129-902d8461adc4.mp4





