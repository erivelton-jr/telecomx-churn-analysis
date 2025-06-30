# Análise de Evasão de Clientes (Churn) 📃

### 1. Introdução
Este relatório tem como objetivo analisar os dados de clientes da empresa Telecom X, com foco no problema de evasão de clientes (churn). A alta taxa de cancelamento de contratos tem impactado negativamente a receita da empresa, e entender os principais fatores que levam à saída dos clientes é essencial para traçar estratégias de retenção.

### 2. Limpeza e Tratamento de Dados
- Os seguintes passos foram realizados na preparação dos dados:
- Importação dos dados usando pandas e requests.
- Conversão de variáveis para valores binários (Sim = 1, Não = 0).
- Verificação e tratamento de valores ausentes ou inconsistentes.
- Conversão de colunas numéricas, como cobranca_total e cobranca_mensal, para o tipo adequado.
- Criação de colunas derivadas como cobranca_diaria para aprofundar a análise.

### 3. Análise Exploratória de Dados (EDA)
- A análise exploratória buscou identificar padrões e fatores associados à evasão:
    - Proporção de evasão por tipo e tempo de contrato.
    - Proporção de evasão por gênero, idade e por tipos de serviços contratados.
    - Visualizações em gráficos para facilitar a interpretação.
    - Utilização da correlação (.corr()) para encontrar relações entre - variáveis numéricas e o cancelamento.
#### Principais descobertas visuais e estatísticas:

- Maior taxa de cancelamento entre clientes com:
    - Contrato mensal (month-to-month)
    - Curto tempo de permanência (tenure baixo)
    - Serviço de internet (Fibra Óptica)
    - Clientes idoso
### 4. Conclusões e Insights
- A evasão é mais frequente entre clientes novos, especialmente nos primeiros 6 meses.
- O tipo de contrato é o fator mais influente: contratos mensais apresentam alta taxa de churn.
- Clientes que contratam serviços de segurança e suporte técnico tendem a cancelar com mais frequência — indicando possível insatisfação ou custo percebido alto.
- A fidelização aumenta com o tempo: clientes com mais de 2 anos de serviço tendem a permanecer.
### 5. Recomendações
- Incentivar contratos anuais com benefícios exclusivos (descontos, bônus).
Melhorar a qualidade e percepção dos serviços técnicos (segurança, suporte, backup).
- Programas de fidelidade para novos clientes que completem 6 meses.
- Contato proativo com clientes em risco de cancelamento, especialmente nos primeiros meses de serviço.
