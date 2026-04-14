# olist-sql-transformation

E-commerce Data Engineering & Analytics: Olist Project

**Descrição**
Construção de um ambiente de Data Warehouse utilizando SQL para estruturação de dados de E-commerce. O projeto foca em Modelagem de Dados, Joins complexos e integridade de pipelines de dados para transformar dados brutos em inteligência de negócio.
**
Objetivo**
Este projeto simula o fluxo de um Engenheiro de Dados ao transpor bases transacionais brutas (CSV) para um banco de dados relacional estruturado (SQLite), permitindo a extração de KPIs estratégicos para a performance de vendas e satisfação do cliente.

**Tech Stack**
Linguagem Principal: Python.
Manipulação de Dados: Pandas.
Banco de Dados: SQL (SQLite).
Visualização de Dados: Seaborn e Matplotlib, com foco em layouts limpos e escaneáveis.

**Estrutura do Projeto**
1. ETL & Modelagem de Dados
O processo de carga (ETL) automatiza a extração de arquivos compactados e a criação de um esquema relacional no SQLite. Foram estabelecidas conexões entre as tabelas de pedidos, pagamentos, itens e produtos para garantir a integridade referencial.

**2. Análise de Performance de Receita**
Utilização de consultas SQL avançadas, incluindo CTEs (Common Table Expressions) e Window Functions, para calcular métricas fundamentais:

****Ticket Médio Mensal:** **Evolução do valor médio por pedido ao longo do tempo.

**Curva ABC (Pareto):** Classificação das categorias de produtos que representam 80% do faturamento da companhia.
<img width="1018" height="502" alt="image" src="https://github.com/user-attachments/assets/a6094cdd-1223-4091-9850-9460897b4bbd" />


**Volume por Estado:** Identificação de polos logísticos e concentração de demanda.

**3. Business Intelligence & Visualização**
Desenvolvimento de gráficos otimizados para tomada de decisão, evitando poluição visual e priorizando a legibilidade:

**Distribuição de Pagamentos:** Comparação de magnitude entre métodos de pagamento (Cartão, Boleto, Voucher).
**
Heatmap de Comportamento:** Concentração de pedidos por dia da semana e horário.

**Análise de Sentimento:** Distribuição de review scores para monitoramento da satisfação do cliente.

**Como Executar**
Certifique-se de ter o Python instalado.
Faça o upload do dataset archive.zip para o diretório raiz.
Execute o notebook para realizar o unzip automático e a carga do banco de dados olist_database.db.
As consultas SQL podem ser testadas diretamente via pd.read_sql.


