# Imersão Dados IA - Alura

## Guia da Imersão

[Notion](https://grupoalura.notion.site/Imers-o-Dados-An-lises-com-Intelig-ncia-Artificial-2af96320056e4ab1adc3243c20e1093c)

## Aula 1 - ANÁLISE EXPLORATÓRIA DA BASE DE DADOS E CHATGPT

### Introdução

Trabalhar com dados no Excel e no Google Sheets se tornou uma habilidade essencial em diversas áreas, incluindo marketing, vendas e muitas outras. Essas ferramentas oferecem uma plataforma versátil para coletar, analisar e visualizar dados, permitindo que profissionais tomem decisões assertivas e estratégicas.

Nesta primeira aula, vamos te apresentar o Kaggle e fazer uma análise exploratória com uma base de dados de compras da Amazon, usando o ChatGPT como auxiliar na hora de gerar fórmulas básicas do Google Sheets.

[Planilha de dados](https://docs.google.com/spreadsheets/d/1pzFHqIAKdNOfbyecJ9hSYUXA3YSbXXF6pYEqLA_0b9k/edit#gid=105405843)

Informações representadas por cada coluna na planilha de dados:

- product_id: ID do produto
- product_name: Nome do produto
- category: Categoria do produto
- actual_price: Valor do produto com desconto
- product_price: Valor do produto com valor cheio
- rating: Valor de 0 a 5 avaliando o produto
- rating_count: Quantidade de pessoas que avaliaram o produto
- about_product: Descrição do produto
- product_link: Link do produto na loja da Amazon

[Planilha de dados com análise](https://docs.google.com/spreadsheets/d/1wIvW2bFuFtJSyKDZ6XFnZWOh0h7g_4pdNxQnVKY6nEA/edit#gid=1436504182)

### Desafios do dia:

1. Adicionar a formatação condicional de cores à coluna de porcentagens.

2. Faça uma análise exploratória e aplique as mesmas técnicas com o ChatGPT a uma nova base de dados do Kaggle: [Top 1000 IMDb Movies Dataset](https://www.kaggle.com/datasets/inductiveanks/top-1000-imdb-movies-dataset).

[Planilha Top 1000 IMDb Movies](https://docs.google.com/spreadsheets/d/1TeCE8_PZ9B2eKVTP8vEyB_1ty67XbOSGHm4-MUpx8cI/edit#gid=1590993529)

### Links

- [ChatGPT OpenAI](https://chat.openai.com/)
- [Base de dados completa da Amazon no Kaggle](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)

## Aula 2 - MANIPULE PLANILHAS E CRIE GRÁFICOS COM AJUDA DA IA

### Introdução

Usar a IA como assistente na manipulação de planilhas.

Vamos dar continuidade à utilização do ChatGPT para aprender a criar fórmulas no Google Sheets. Abordaremos algumas fórmulas mais avançadas, como o cálculo de média para faixas de valores e média ponderada, exploraremos a criação de gráficos e te apresentaremos a uma nova ferramenta de IA para dados.

[Planilha de dados](https://docs.google.com/spreadsheets/d/1vfgOR26f-ZH9SKN3JaTlUnSj5IpENS79sXvus6mV46E/edit#gid=105405843)

[Planilha de dados com análise](https://docs.google.com/spreadsheets/d/1wIvW2bFuFtJSyKDZ6XFnZWOh0h7g_4pdNxQnVKY6nEA/edit#gid=105405843)

### Desafio do dia:

1. Personalize o gráfico para adicionar as quantidades
2. Analise qual seria o melhor gráfico para o seu caso usando o guia citado pelo Marcell, que está nos links da aula
3. Faça uma análise exploratória e aplique as mesmas técnicas vistas na aula de hoje, incluindo a criação de gráficos, a uma nova base de dados do Kaggle: [base de dados de hotéis do Kaggle](https://www.kaggle.com/datasets/andrewgeorgeissac/hotels-in-munnar-kerala).

[Planilha hotéis indianos](https://docs.google.com/spreadsheets/d/1yso5XL371eWUOxPlbA3OLfuo1eFq8JMJBaehzUx5OaQ/edit#gid=1107662237)

### Links

- [ChatGPT OpenAI](https://chat.openai.com/)
- [Guia para escolher gráficos](arquivos/Guia%20rápido%20para%20escolher%20gráficos_PM3.pdf)
- [Sheet+ (IA específico para planilhas Excel e Goggle Sheets)](https://sheetplus.ai/)
- [Magical (Extensão browser para recriar textos ou gerar textos com IA)](https://www.getmagical.com/)
- [Rows (Webapp de planilhas com recursos de IA)](https://rows.com/)

## Aula 3 - CONECTE PLANILHAS E DOMINE CONCEITOS DE ENGENHARIA DE PROMPT

### Introdução

Uma nova base de dados, também da Amazon, que é relacionada à base antiga, e aprenderemos como conectá-las usando uma coluna comum a ambas. Apresentaremos também uma extensão que te permitirá ter o ChatGPT dentro do seu Google Sheets, e a empregaremos para realizar traduções, resumos e análises de sentimento de críticas. Por fim, focaremos uma parte da aula em te passar alguns dos principais conceitos de Engenharia de Prompt, como o uso de “few-shot” com o cadeia de pensamento, a fim de obter respostas mais precisas de IAs generativas como o ChatGPT.

[Nova planilha de dados](https://docs.google.com/spreadsheets/d/12THJZdg_FXW_P7Yh8s4ski0tEn3KzkwXWVcR7Pfkln8/edit#gid=1074485333)

[Planilha de dados com análise](https://docs.google.com/spreadsheets/d/1wIvW2bFuFtJSyKDZ6XFnZWOh0h7g_4pdNxQnVKY6nEA/edit#gid=1810944171)

Informações representadas por cada coluna na nova planilha de dados:

- product_id: ID do produto
- user_id: ID único do usuário
- user_name: Nome escolhido pelo usuário
- review_id: ID da crítica
- review_title: Título da crítica
- review_content: Conteúdo da crítica
- img_link: Link da imagem do produto

### Prompts da aula:

#### Pergunta principal

Pergunta: Tenho uma lista de valores. O meu resultado final será 30% da soma de valores. Porém, nem todos os valores serão somados, apenas aqueles acima de R$40.000,00. Para a lista abaixo, conte quantos valores existem e me diga qual é o meu resultado final?

R$10.000,00
R$20.000,00
R$50.000,00
R$60.000,00

Resposta: Nessa lista, existem 4 valores. Há 2 valores acima de R$40.000,00, que são R$50.000,00 e R$60.000,00. A soma desses valores é R$110.000,00. O resultado final é 30% da soma desses valores, portanto, 30% de R$110.000,00, que resulta em R$33.000,00.

Pergunta: Tenho uma lista de valores. O meu resultado final será 30% da soma de valores. Porém, nem todos os valores serão somados, apenas aqueles acima de R$40.000,00. Para a lista abaixo, conte quantos valores existem e me diga qual é o meu resultado final?

R$31.000,00
R$15.000,00
R$52.000,00
R$103.000,00
R$42.000,00
R$156.000,00
R$15.000,00
R$27.000,00
R$82.000,00
R$33.000,00

Resposta:

#### Resposta do Chat GPT

Nessa lista, existem 10 valores. Há 6 valores acima de R$40.000,00, que são R$52.000,00, R$103.000,00, R$42.000,00, R$156.000,00, R$82.000,00 e R$33.000,00. A soma desses valores é R$468.000,00.

O resultado final é 30% da soma desses valores, portanto, 30% de R$468.000,00, que resulta em R$140.400,00.

#### Resposta está errada então coloquei o novo prompt abaixo

R$33.000,00 é menor que R$40.000,00

#### Nova Resposta do Chat GPT

Peço desculpas pela resposta incorreta anterior. Você está absolutamente correto. R$33.000,00 está abaixo de R$40.000,00. Portanto, na lista fornecida:

Existem 10 valores.
Há 5 valores acima de R$40.000,00, que são R$52.000,00, R$103.000,00, R$42.000,00, R$156.000,00 e R$82.000,00.
A soma desses valores é R$435.000,00.

O resultado final é 30% da soma desses valores, portanto, 30% de R$435.000,00, que resulta em R$130.500,00.

### Desafio do dia:

1. Gere a tradução das críticas e faça uma análise de sentimentos das mesmas usando a extensão SheetGPT em uma nova base de dados do Kaggle: [base de críticas do aplicativo Threads](https://www.kaggle.com/datasets/saloni1712/threads-an-instagram-app-reviews).

[Planilha Threads Reviews](https://docs.google.com/spreadsheets/d/1ztv1T-iTXGVq5DZOOWElsZXFLo_noGQWeHkhfcOfTgQ/edit#gid=2024179416)

### Links

- [ChatGPT OpenAI](https://chat.openai.com/)
- [SheetGTP](https://workspace.google.com/marketplace/app/sheetgpt/1071108744264)
- [Guia básico de engenharia de prompt](https://github.com/openai/openai-cookbook/blob/main/techniques_to_improve_reliability.md)
- [Planilha para cálculo da arrecadação de impostos](https://docs.google.com/spreadsheets/d/1U0kYr00-lHRoCvqD4W-9u4rNmgF02WdqAfZDMP6C-9Q/edit#gid=0)

## Aula 4 - MANIPULE PLANILHAS COM PYTHON/PANDAS E O CHATGPT

### Introdução

Google Colab. Vamos mergulhar em Python e na biblioteca de manipulação de dados Pandas, demonstrando como importar tabelas e realizar análises iniciais com os comandos mais importantes. Não se preocupe se você não sabe programar! Nós utilizaremos o ChatGPT para nos auxiliar na criação de código em Python e Pandas, e também para plotar gráficos.

[Planilha avaliações Amazon](https://docs.google.com/spreadsheets/d/12THJZdg_FXW_P7Yh8s4ski0tEn3KzkwXWVcR7Pfkln8/edit#gid=1074485333)

[Código Google CoLab](https://colab.research.google.com/drive/1qSoP2TbOtahUC8YywBhZb_9Ru2FZaHkR)

### Desafios

1. Usando o Google Colab com Python e Pandas, criar uma nova coluna chamada “actual_price_real”, que será o valor da coluna “actual_price” convertido para reais (dica: você pode apenas multiplicar o valor em rúpias por 0.05, como fizemos na Aula 01, ou então buscar o valor de hoje da conversão entre rúpias indianas e reais brasileiros no Google).

2. Realizar as análises que foram executadas nas aulas anteriores usando o Google Sheets, mas agora utilizando Python e Pandas no Google Colab.

3. Conectar as duas planilhas usadas nas aulas anteriores, como fizemos com o VLOOKUP, mas usando Python e Pandas.

4. Colocar a base já corrigida na biblioteca Pandas Profiling citada no conteúdo extra.

[Código com desafios Google CoLab](https://colab.research.google.com/drive/1qSoP2TbOtahUC8YywBhZb_9Ru2FZaHkR#scrollTo=c1mOZRiAOdvK)

### Links

- [Google Colab](https://colab.research.google.com/?utm_source=scs-index)
- [Documentação da biblioteca Pandas](https://pandas.pydata.org/docs/user_guide/index.html)
- [Documentação da biblioteca Pandas Profiling](https://pandas.pydata.org/docs/user_guide/index.html)

## Aula 5 - CARREIRAS EM ANÁLISE DE DADOS E INTELIGÊNCIA ARTIFICIAL

### Introdução

Diferenças entre as principais carreiras nessa área de dados, tais como Analista de Dados, Cientista de Dados, Engenheiro de Dados, Engenheiro de Machine Learning, Engenheiro de IA e Engenheiro de Prompt.

### Engenheiro de dados

- Responsável pela coleta dos dados, preparação para análises e armazenamento dos dados, conforme lei vigente. Pode desenvolver plataformas para isso. Pode ou não fazer a limpeza de dados.

### Analistas (dados, business intelligence, negócios)

- Responsáveis pelo intendimento da geração dos dados, exploração de dados, hipóteses para testes, transformações dos dados, de um input extrair um output necessário ao negócio. Determinar o que é necessário em investimentos, colaboradores, o custo benefício ou não.

### Cientista de dados

- Responsável também pela limpeza e exploração de dados e também criar modelos de machine learning (aprendizado de máquina), métricas, modelos de regressão.

### Engenheiro de machine learning

- Responsável pelo monitoramento dos modelos prontos, entender como funcionam em produção, estruturar o workflow de transformação e análise dos dados. Coleta de novos dados em produção para retreinamento de machine learning.

### Governança de dados

- Responsável pela educação da equipe de gera os dados, política e diretrizes dos modelos a serem criados, o que é possível disponibilizar de dados, ajuda a catalogar e entender os dados disponíveis. Garantir a qualidade dos dados e metadados, conformidade em relação a legislação e normas, quem pode acessar os dados.

### Engenheiro de IA (inteligência artificial)

- Responsável por gerir e entender os modelos de IA. Pesquisa e desenvolvimento de IA. Modelos de linguagem e processamento de linguagem natural. Testar formas de criação e servir os modelos, eficiência dos modelos. Treinamento e Avaliação do modelos, buscar e criar novos datasets para avaliar o modelo. Planejar novos experimentos.

### Engenheiro de prompt

- Responsável pela analise das melhores formas de criar um prompt, para ser preciso e funcional na maioria das vezes. Testar novas formas de criação de prompt, chain of thought, tree of thoughts, entre muitos outros que estão sendo criados. Trazer artigos acadêmicos para as empresas.

### Links

- [Tech Guide](https://techguide.sh/)

## Certificado

- [PDF](/arquivos/imersao-dados-ia-certificado.pdf)
