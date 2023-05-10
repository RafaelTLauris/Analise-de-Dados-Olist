# Analise-de-Dados-Olist

# Análise Exploratória de Dados

Bem-vindos! Neste projeto, irei mostrar como realizei uma **análise exploratória de dados** da base de dados de e-commerce de uma grande empresa brasileira, a **Olist**.

A **análise exploratória de dados** é uma das principais técnicas utilizadas em **Data Science**, pois nos permite compreender melhor os dados e encontrar insights valiosos que podem ser usados em decisões de negócios. Neste notebook, irei explorar a base de dados da Olist e responder algumas perguntas importantes sobre o comportamento dos consumidores no mercado de e-commerce.

Para isso, usarei a linguagem **Python** e as bibliotecas **Pandas, Numpy** e **Matplotlib** para manipulação e visualização de dados. Além disso, utilizarei a biblioteca **Plotly** para criar gráficos interativos e mais complexos, permitindo uma análise mais detalhada dos dados.

(Esse notebook teve com base diversas análises de dados e EDAs)


# Quais dados vamos analisar?

Vamos analisar o conjunto de comércio eletrônico brasileiro de pedidos feitos na loja Olist.

Olist é uma plataforma de comércio eletrônico brasileira que conecta pequenas empresas a canais de vendas online, permitindo que vendam seus produtos em vários marketplaces do Brasil. A empresa também oferece serviços de logística e gerenciamento de pedidos para seus clientes.

O conjunto de dados possui informações de 100 mil pedidos de 2016 a 2018 realizados em vários marketplaces no Brasil. Suas características permitem visualizar um pedido em múltiplas dimensões: desde o status do pedido, preço, desempenho de pagamento e frete até a localização do cliente, atributos do produto e, finalmente, avaliações escritas pelos clientes. Também lançei um conjunto de dados de geolocalização que relaciona os códigos postais brasileiros às coordenadas (latitude/longitude).

**Obs:** Todo o texto que identifica lojas e parceiros foi substituído pelos nomes das grandes casas de Game of Thrones.


* Informações retiradas do dataset publicado no Kaggle e traduzido pelo autor
