# Analise-de-videos-YouTube-no-Tableau-Public
Objetivo dos negócios: analisar o histórico de vídeos de tendências no YouTube, o dashboard será usado: pelo menos uma vez por dia
Usuário do dashboard de destino: gerentes de planejamento de anúncios em vídeo
Conteúdo de dados do dashboard: Vídeos de tendências do passado, divididos por dia e categoria, divididos por países
Parâmetros segundo os quais os dados devem ser agrupados: Data e hora da tendência, categoria de vídeo, país
Histórico de tendências — valores absolutos com divisão por dia (dois gráficos: números absolutos e proporção percentual)
Eventos, discriminados por países — valores relativos (% de eventos)
A correspondência entre as categorias e os países — valores absolutos 

Fontes de dados para o dashboard: os engenheiros de dados prometeram criar uma tabela agregada chamada trending_by_time. 
Segue sua estrutura:
record_id — chave primária
region — país / região geográfica
trending_date — data e hora
category_title — a categoria de vídeo
videos_count — o número de vídeos na seção de tendências
A tabela fica armazenada no banco de dados do youtube , criado especialmente para suas necessidades
Intervalo de atualização de dados: uma vez a cada 24 horas, à meia-noite UT
O dashboard responde as perguntas
Quais categorias de vídeo estão em alta com mais frequência?
Como foram distribuídos entre as regiões?
Quais categorias foram especialmente populares nos Estados Unidos? Houve alguma diferença entre as categorias populares nos EUA e as populares em outros lugares?C


https://public.tableau.com/app/profile/debora.pivatto/viz/Sprint12project/Dashboard1?publish=yes
