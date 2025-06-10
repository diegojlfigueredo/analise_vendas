
Análise Exploratória de Vendas — Projeto Superstore

Visão Geral

Este projeto apresenta uma análise exploratória detalhada da base de dados Superstore, que contém informações sobre vendas, lucros, descontos e categorias de produtos distribuídos em diferentes regiões. O objetivo é identificar padrões, tendências e oportunidades de negócio para otimizar estratégias comerciais.

Estrutura do Projeto

analise_vendas/
│
├── dados/                 # Arquivos de dados brutos (.csv)
├── imagens/               # Gráficos e visualizações salvos (.png)
├── notebooks/             # Notebooks Jupyter com análises detalhadas (.ipynb)
└── README.md              # Documentação do projeto

Base de Dados

O dataset utilizado é proveniente da empresa fictícia Superstore e está disponível no arquivo Superstore.csv dentro da pasta dados/. Ele contém registros transacionais com informações como data da venda, região, categoria do produto, valor da venda, lucro, desconto aplicado, entre outros.

Tecnologias e Ferramentas Utilizadas

- Python 3.9+
- Jupyter Notebook
- Pandas para manipulação e limpeza de dados
- Seaborn e Matplotlib para visualização gráfica
- Git para controle de versão e versionamento do código

Metodologia

A análise foi conduzida em etapas, que incluem:

1. Importação e limpeza dos dados:
   - Verificação de valores faltantes e inconsistências
   - Ajustes nos tipos de dados

2. Análise Exploratória de Dados (EDA):
   - Estatísticas descritivas
   - Visualização das distribuições de vendas, lucro e descontos
   - Análise por região, categoria e produtos

3. Insights e resultados:
   - Identificação das regiões com maior volume de vendas
   - Categorias mais lucrativas
   - Impacto do desconto aplicado sobre o lucro
   - Ranking dos produtos com maiores vendas

Principais Resultados

- A região Sul apresentou o maior volume de vendas, seguida pela região Norte.
- A categoria Tecnologia gerou o maior lucro total, enquanto a categoria Móveis teve maior volume de vendas.
- Foi observada uma correlação negativa entre o desconto aplicado e o lucro obtido, indicando que maiores descontos impactam negativamente a rentabilidade.
- Os 10 produtos mais vendidos representam aproximadamente 60% do faturamento total.

Como Executar o Projeto

Para reproduzir esta análise, siga os passos abaixo:

1. Clone este repositório:
   git clone https://github.com/seuusuario/analise_vendas.git

2. Navegue até o diretório do projeto:
   cd analise_vendas

3. (Opcional) Crie e ative um ambiente virtual:
   python -m venv venv
   source venv/bin/activate    # Linux/Mac
   venv\Scripts\activate     # Windows

4. Instale as dependências:
   pip install -r requirements.txt

5. Abra o Jupyter Notebook:
   jupyter notebook notebooks/01_analise_vendas_superstore.ipynb

6. Execute as células do notebook para reproduzir a análise e gerar os gráficos salvos na pasta imagens/.

Contato

Para dúvidas, sugestões ou colaborações, fique à vontade para me contatar:

- Diego
- LinkedIn: https://www.linkedin.com/in/diego-juliano-lima-figueredo-7112816a/
- GitHub: https://github.com/diegojlfigueredo

---

Este projeto faz parte do portfólio de análises de dados de Diego, com foco em desenvolvimento de habilidades práticas e apresentação profissional.
