# SAD_Trabalho_Final
Rotterdam

obs: avaliação pode ser obtida do nome


Sasonalidade

Calender:
listing_id
date
available
price
adjusted_price
minimum_nightsm
maximum_nights


Pegar quantos dias esta livre

listings:
id
name
host_id
host_name
neighbourhood_group
neighbourhood latitude
longitude
room_type
price
minimum_nights
number_of_reviews
last_review
eviews_per_month
calculated_host_listings_count
availability_365
number_of_reviews_ltm
license

listings zipado ( listings.csv.gz ):
id
listing_url
scrape_id
last_scraped
source
name
description
neighborhood_overview
picture_url
host_id
host_url
host_name
host_since
host_location
host_about
host_response_time
host_response_rate
host_acceptance_rate
host_is_superhost
host_thumbnail_url
host_picture_url
host_neighbourhood
host_listings_count
host_total_listings_count
host_verifications
host_has_profile_pic
host_identity_verified
neighbourhood
neighbourhood_cleansed
neighbourhood_group_cleansed
latitude,longitude
property_type
room_type
accommodates
bathrooms
bathrooms_text
bedrooms
beds
amenities
price
minimum_nights
maximum_nights
minimum_minimum_nights
maximum_minimum_nights
minimum_maximum_nights
maximum_maximum_nights
minimum_nights_avg_ntm
maximum_nights_avg_ntm
calendar_updated
has_availability,
availability_30
availability_60
availability_90
availability_365
calendar_last_scraped
number_of_reviews
number_of_reviews_ltm
number_of_reviews_l30d
first_review
last_review
review_scores_rating
review_scores_accuracy
review_scores_cleanliness
review_scores_checkin
review_scores_communication
review_scores_location
review_scores_value
license
instant_bookable
calculated_host_listings_count
calculated_host_listings_count_entire_homes
calculated_host_listings_count_private_rooms
calculated_host_listings_count_shared_rooms
reviews_per_month

neighbourhoods:
neighbourhood_group
neighbourhood

reviews - comentarios:
listing_id
id
date
reviewer_id
reviewer_name
comments

Quantos comentarios tem cada divisão

reviews:
listing_id
date


KPI's:
Taxa de Ocupação: Percentual de tempo em que um anúncio está reservado em comparação com o tempo total disponível.
Avaliações e Classificações: A média das avaliações deixadas pelos hóspedes, bem como a classificação global de uma propriedade.
Preço Médio por Noite: O preço médio que os anfitriões estão cobrando por noite.
Receita Total: A receita total gerada pela plataforma, incluindo taxas e comissões.
Taxa de Satisfação do Hóspede: Mede a satisfação dos hóspedes com base em suas experiências.

Perguntas:
Qual é a média de preços dos aluguéis no Airbnb na cidade?
Quais são os bairros mais caros e mais baratos para alugar no Airbnb?
Quais são os tipos de propriedades mais comuns (apartamentos, casas, quartos compartilhados)?

Existe uma sazonalidade nos preços ou na ocupação ao longo do ano?
Há uma **** entre a localização do imóvel e sua popularidade?(clusters - encontrar concorrente )
quarto, numero de reviws, preço,

Como as avaliações dos hóspedes variam em relação de preço?(correlação linear)
Qual é a distribuição geográfica dos imóveis mais bem avaliados?(há um grafico para isso!)
Quais são os meses de maior e menor movimento no mercado de aluguéis?
Há uma diferença notável nas taxas de ocupação nos fins de semana versus dias úteis?
Qual é a média de dias reservados por hóspede?

regreção logistica ou classificação
teste de hipoteses


*****Conversa com o chat *****

Para definir cruzamentos de dados e extrair conclusões, é importante entender quais são as questões específicas que você deseja abordar ou os insights que procura obter. No entanto, com base nas informações fornecidas, aqui estão algumas análises potenciais que você pode realizar usando os diferentes conjuntos de dados e técnicas estatísticas mencionadas:

Estatística Descritiva:

Analisar estatísticas descritivas básicas (média, mediana, desvio padrão, etc.) para variáveis como preço, número mínimo de noites, número de avaliações, etc., em diferentes bairros ou grupos de bairros.
Examinar a distribuição da disponibilidade ao longo do tempo usando o conjunto de dados do calendário.
Verificar a variação nos preços ajustados ao longo do tempo.
Estatística Inferencial:

Realizar testes de hipóteses para comparar médias ou proporções entre diferentes grupos, como comparar preços médios entre diferentes tipos de quartos ou bairros.
Utilizar intervalos de confiança para estimar a faixa em que os preços médios ou outras variáveis estão provavelmente localizados.
Clusters:

Agrupar bairros com base em características semelhantes, como preços médios, número mínimo de noites, ou tipos de quartos disponíveis.
Explorar clusters de listagens com base em diferentes critérios, como comodidades, número de avaliações, etc.
Regressão Linear:

Avaliar a relação entre variáveis, como preço e número de avaliações, preço e número mínimo de noites, etc.
Modelar a influência de variáveis independentes (por exemplo, localização, tipo de quarto) no preço das listagens.
Classificação Supervisionada:

Prever a disponibilidade de uma listagem com base em características como preço, localização e número mínimo de noites.
Classificar listagens como "superhost" ou não com base em várias características do host.
Ao realizar essas análises, é crucial levar em consideração a natureza dos dados, verificar a qualidade e consistência dos mesmos, e ajustar os modelos conforme necessário. Além disso, é recomendável utilizar visualizações gráficas para comunicar efetivamente os resultados. Essas são apenas sugestões iniciais, e as análises específicas dependerão das perguntas de pesquisa e objetivos específicos que você tem em mente.