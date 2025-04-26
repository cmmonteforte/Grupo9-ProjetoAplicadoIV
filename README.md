# COVID-19 no Brasil: Uma Abordagem Preditiva para Apoio à Gestão e Alocação de Recursos

### Documentação completa: 
https://github.com/cmmonteforte/Grupo9-ProjetoAplicadoIV/blob/main/analysis_and_documentation/Grupo9_projeto_aplicado_IV_entrega_3.ipynb

# Introdução
Nas primeiras 3 semanas de 2025, o Brasil registrou mais de 57 mil casos confirmados de COVID-19, o maior número em 10 meses, representando um aumento de 151% em comparação com as últimas 3 semanas de 2024 (ESTADÃO CONTEÚDO, 2025).<br>
Em 2025, a COVID-19 é a maior causadora de síndromes respiratórias agudas graves (SRAGs), representando 48% das notificações da doença e 87% das mortes, segundo o informe de 15/02/2025 da Secretaria de Vigilância em Saúde e Ambiente do Ministério da Saúde.

Apesar do cenário de baixa mortalidade, a circulação de novas variantes da doença pode afetar a população brasileira de maneiras bastante distintas de acordo com a sua condição socioeconômica. Um estudo conduzido na favela da Maré, no Rio de Janeiro, mostrou que linhagens do coronavírus evoluíram na comunidade e infectaram pessoas mundialmente. Fatores como piores condições sanitárias e moradias precárias colaboram para maior dispersão do vírus em comunidades, podendo catalizar novas infecções não apenas em contexto regional. Além disso, o difícil acesso ao serviço de saúde nessa região levou-a a apresentar uma taxa de mortalidade de quase o dobro do registrado na cidade do Rio de Janeiro entre 2020-2021 (AGÊNCIA BRASIL, 2025).<br>

Nesse projeto, analisaremos séries temporais do número de casos e óbitos de COVID-19 no Brasil, desde 2020, com o objetivo de prever a quantidade de novos casos e sua sazonalidade, a fim de apoiar a tomada de decisão das autoridades e serviços de saúde na alocação de recursos hospitalares, planejamento de políticas públicas e adoção e propagação de medidas preventivas.<br>

# Motivações e justificativa
A previsão de novos casos e a vigilância da evolução da COVID-19 em território brasileiro é essencial para a boa gestão dos recursos de saúde pelas autoridades. A doença não se espalha homogeneamente entre as camadas socieconômicas e o surgimento de novas variantes e a baixa adesão à vacinação pode criar picos de transmissão da doença de maneira súbita, como já foi observado durante a pandemia.<br>

A análise preditiva desses dados pode fornecer insights para os gestores planejarem ações de contenção de casos. Hospitais podem se antecipar à demanda por leitos, insumos médicos e equipes de atendimento. A identificação de crescimento regionais dão a possibilidade de criar-se estratégias de mitigação localizadas, como restrições sanitárias e campanhas. Além disso, o estudo pode revelar tendências sazonais, efeitos de medidas governamentais e o impacto de novas variantes do vírus.<br>

# Objetivo
Neste projeto, buscamos desenvolver um modelo preditivo que analise dados históricos de casos e de óbitos causados pela COVID-19 no território brasileiro, com o intuito de prever a quantidade de novos casos para que assim seja possível apoiar a tomada de decisão das autoridades na gestão de saúde pública.<br>

Esperamos atingir esse objetivo através das seguintes metas:

* Coletar e processar dados oficiais de casos e óbitos relacionados à COVID-19 no Brasil;
* Aplicar e comparar técnicas de modelagem de séries temporais;
* Validar o desempenho dos modelos preditivos através de métricas de erros e testes estatísticos;
* Gerar um modelo com bom desempenho, capaz de prever a quantidade de casos ou óbitos nos próximos dias, semanas ou meses.

# Contribuição
Membros do grupo:
- Carolina Molinari Monteforte
- Leandro da Cruz Cirqueira
- Levy Salles Bispo de Oliveira
- William Silva Veçoso
