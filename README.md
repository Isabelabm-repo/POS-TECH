# POS-TECH
# Tech Challenge – NPS Preditivo

## Objetivo
Analisar fatores que impactam a satisfação do cliente e propor ações para melhoria da experiência.

## Principais Resultados
- Atraso na entrega é o principal driver de insatisfação
- Reclamações e atendimento impactam fortemente o NPS
- Recompra está diretamente ligada à satisfação
-  Análise Exploratória de Dados (EDA)

#################################

Objetivo

A análise exploratória de dados (EDA) teve como objetivo identificar os principais fatores que influenciam a satisfação do cliente, representada pelo NPS (nps_score), além de compreender padrões de comportamento e possíveis pontos críticos na jornada de compra.

📁 Base de Dados

A base utilizada contém aproximadamente 2.500 registros com informações relacionadas a:

Perfil do cliente (idade, região)
Dados do pedido (valor, quantidade de itens)
Dados logísticos (tempo de entrega, atrasos)
Dados de atendimento (contatos, tempo de resolução)
Indicadores de satisfação (CSAT e NPS)


Etapas da Análise
1. Entendimento dos Dados

Foi realizada a leitura e exploração inicial da base para compreender a estrutura, tipos de variáveis e significado dos campos disponíveis.

2. Tratamento dos Dados

Foram realizadas verificações básicas para garantir a qualidade da análise:

Identificação de valores nulos
Validação de tipos de dados
Consistência das variáveis

Não foram identificados problemas críticos que inviabilizassem a análise.

3. Análise Univariada

Foram analisadas as distribuições individuais das principais variáveis, como:

NPS (nps_score)
Atrasos na entrega (delivery_delay_days)
Número de reclamações (complaints_count)
Contatos com atendimento (customer_service_contacts)

Essa etapa permitiu entender o comportamento geral dos dados.

4. Análise de relações

Foi avaliada a relação entre variáveis operacionais e o NPS, com foco em identificar fatores de impacto na satisfação.

Principais relações analisadas:

Atraso na entrega vs NPS
Reclamações vs NPS
Contatos com atendimento vs NPS
Tempo de resolução vs NPS
Recompra vs NPS


5. Análise de Correlação

Foi utilizada a correlação para medir a força e a direção da relação entre variáveis numéricas.

Principais resultados:

delivery_delay_days: forte correlação negativa com o NPS
complaints_count: impacto negativo relevante
customer_service_contacts: relação negativa moderada
repeat_purchase_30d: forte correlação positiva
csat_internal_score: forte correlação positiva

Porém, correlação não implica causalidade.

Principais Insights
Atrasos na entrega são o principal fator de insatisfação
Reclamações e contato com suporte indicam falhas na jornada
Clientes que recompram tendem a ser mais satisfeitos
O problema não está no prazo de entrega, mas no atraso


