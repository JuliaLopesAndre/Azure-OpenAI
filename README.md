# Azure-OpenAI
# Resumo: Conceitos do Azure OpenAI  

## Deploy  
O **deploy** é o processo de configuração e ativação de um recurso do **OpenAI no Azure**, tornando-o disponível para uso no **Playground** e em aplicações.  

## Playground  
O **Playground** é um ambiente interativo que permite criar e testar **prompts** para modelos de IA, ajustando parâmetros para otimizar respostas.  
## Parâmetros do Modelo  
- **Temperatura**: Controla a **aleatoriedade** das respostas. Valores baixos resultam em respostas previsíveis, enquanto valores altos geram respostas mais criativas.  
- **Top-P**: Define o **conjunto de palavras prováveis** que o modelo pode escolher ao gerar um texto, influenciando a diversidade das respostas.  
- **Penalidades**: Ajustam a **repetição e diversidade** do texto gerado:  
  - **Frequency Penalty**: Reduz a repetição de tokens já utilizados.  
  - **Presence Penalty**: Regula a introdução de novos tokens com base no tema abordado.  

## Tokenização  
A **tokenização** divide um texto em unidades menores (**tokens**). No português, o processo pode ser mais complexo do que no inglês, pois as palavras são frequentemente separadas, aumentando o custo computacional.  

## System Message  
Define o **contexto inicial e o comportamento** do modelo. Para criar um bom **System Message**, é necessário usar estratégias como:  
- **Zero-shot**: O modelo responde apenas com base no prompt, sem exemplos anteriores.  
- **Few-shot**: Inclui exemplos no prompt para guiar a resposta da IA.  

## Multimodalidade  
Os modelos de IA podem gerar **mais do que apenas texto**, como imagens com o **DALL·E**. Para obter bons resultados, é essencial fornecer um prompt **claro, específico e bem estruturado**.  


