# Análise de Sentimentos com Azure AI - Language Studio

## Objetivo
Neste projeto, foi realizado um processo de análise de sentimentos de várias sentenças utilizando o **Language Studio** da **Microsoft Azure AI**. O objetivo era entender os conflitos das frases fornecidas, e identificar como positivas, negativas ou neutras.

## Passo a Passo

## 1. Criação de um Repositório no GitHub
Para começar, criei um repositório para armazenar o código e os resultados do projeto. No repositório, temos a pasta `inputs` que contém um arquivo de texto com sentença.

## 2. Utilizando o Language Studio do Azure AI
O **Language Studio** do Azure permite analisar texto para obter insights como análise de sentimentos, detecção de entidades e muito mais.

1. Acesse o [Azure AI Language Studio](https://studio.azure.ai/).
2. Crie um novo projeto de análise de sentimentos.
3. Importe ou cole as sentenças no painel de análise de texto.
4. O modelo de análise de sentimentos irá retornar uma pontuação para cada sentença indicando o seu sentimento.

### 3. Analisando as Sentenças
Após submeter as sentenças ao modelo, obtemos os seguintes resultados:

- **"A empresa é maravilhosa, todos os funcionários são super amigáveis!"** - Sentimento: Positivo
- **"O atendimento ao cliente deixou muito a desejar, estou insatisfeito."** - Sentimento: Negativo
- **"Estou muito feliz com a compra, valeu a pena!"** - Sentimento: Positivo
- **"A qualidade do produto é excelente, mas o preço é muito alto."** - Sentimento: Neutro
- **"O serviço foi péssimo, não voltarei a usar."** - Sentimento: Negativo

### 4. Insights e Possibilidades
Ao realizar a análise de sentimentos com o Azure AI, percebi que o modelo consegue entender bem o contexto emocional das frases, sendo capaz de classificar as sentenças com boa precisão.

Possibilidades que explorei:
- Detecção de sentimentos em críticas de clientes para empresas.
- Análise de sentimentos em redes sociais para medir a recepção de campanhas de marketing.
- Uso de IA para melhorar o atendimento ao cliente, direcionando respostas automáticas baseadas no sentimento.

### 5. Prints do Processo
(Insira prints aqui do processo no Azure Language Studio, como a interface de análise de sentimentos, os resultados, etc.)

## Conclusão
A análise de sentimentos com Azure AI é uma ferramenta poderosa para entender a percepção dos usuários sobre produtos, serviços ou qualquer conteúdo textual. Este projeto demonstra como a análise de sentimentos pode ser aplicada de forma simples e eficaz para obter insights valiosos em várias áreas.
