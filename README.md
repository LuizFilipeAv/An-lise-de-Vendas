Sistema de Análise de Vendas (Python)
Este projeto foi desenvolvido como uma solução prática para o processamento e análise de dados de vendas a partir de arquivos CSV. O sistema realiza desde a limpeza e carga dos dados até a geração de indicadores de desempenho (KPIs) e visualizações gráficas.

O projeto une conceitos de Engenharia de Software (como qualidade e validação de dados) com técnicas modernas de Data Analysis.

Objetivos do Projeto:
- Implementar um fluxo completo de processamento de dados (ETL simplificado).
-Extrair métricas relevantes como faturamento por região e produtos mais vendidos.
-Proporcionar inteligência de negócio através de gráficos de tendências e categorias.

Tecnologias e Ferramentas
- Linguagem: Python 3.10+
- Manipulação de Dados: Pandas
- Visualização: Matplotlib

Ambiente: Google Colab / Jupyter Notebook

Funcionalidades
- Carga e Inspeção: Leitura automatizada de arquivos .csv com verificação de tipos e integridade.
- Cálculos Automáticos: Geração de coluna de Receita Total (Quantidade × Preço Unitário).
- Filtragem Dinâmica: Isolamento de dados por categorias específicas e regiões.
- Análise de Desempenho:
  - Identificação do produto campeão de vendas.
  - Ranking de faturamento por região geográfica.
- Visualizações Gráficas:
  - Gráfico de Barras: Comparação de faturamento entre categorias.
  - Gráfico de Linhas: Evolução temporal das vendas para identificação de sazonalidade.

Como Executar
Clone este repositório:
git clone https://github.com/seu-usuario/nome-do-repositorio.git

Certifique-se de ter as bibliotecas instaladas:
pip install pandas matplotlib
Certifique-se de que o arquivo vendas.csv está no mesmo diretório do script.

Execute o arquivo principal ou abra o notebook no Google Colab.

 Conceitos Aplicados (Engenharia de Software)
Durante o desenvolvimento, foram aplicados princípios de:

Verificação e Validação (V&V): Garantia de que os tipos de dados (como datas) foram convertidos corretamente antes da análise dinâmica.

Manutenibilidade: Código modularizado e utilização de operações vetorizadas do Pandas para evitar loops desnecessários e reduzir bugs.
