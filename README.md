# Projeto de Análise de Sentenças com Language Studio

Neste projeto, exploraremos os recursos da Linguagem de IA do Azure usando o Language Studio para analisar avaliações de hotéis. A análise incluirá a identificação de sentimentos positivos e negativos nas avaliações.

## Processo

### 1. Criar um recurso de idioma no Azure
- Acesse o [portal do Azure](https://portal.azure.com/).
- Clique em "+Criar um recurso" e procure por "Serviço de Idioma".
- Selecione "Criar um plano de serviço de idioma" e siga as instruções para configurar o recurso.
  - As configurações incluem assinatura, grupo de recursos, região, nome e nível de preços.

### 2. Configurar o recurso no Language Studio de IA do Azure
- Acesse o [Language Studio](https://language.cognitive.azure.com/) e faça login.
- Escolha o recurso de idioma criado na etapa anterior.

### 3. Analisar avaliações no Language Studio
- Na guia "Classificar texto", selecione "Analisar sentimento e minerar opiniões".
- Escolha o idioma do texto (inglês) e selecione o recurso Azure criado.
- Cole a primeira revisão de exemplo e execute a análise.
- Observe o sentimento geral e as pontuações de positividade, neutralidade e negatividade.

### 4. Insights
Durante a análise, observamos que o Language Studio é capaz de avaliar sentimentos em textos de avaliações de hotéis. A pontuação de confiança fornece uma indicação da probabilidade associada a cada sentimento identificado.

### 5. Possibilidades Futuras
- Explorar técnicas avançadas de análise de sentimento.
- Integrar a análise de entidades, identificando locais ou pessoas mencionadas nas avaliações.
- Utilizar a API em aplicações para automatizar a análise de feedback do usuário.

## Exclusão de Recursos
Se não pretender continuar com outros exercícios, lembre-se de excluir os recursos no [portal do Azure](https://portal.azure.com/) para evitar custos desnecessários.

Este projeto fornece uma introdução prática ao uso do Language Studio para análise de texto, abrindo caminho para aplicações mais avançadas de processamento de linguagem natural.
