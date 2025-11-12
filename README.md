# Dashboard de Vendas

Dashboard interativo desenvolvido com Streamlit para análise de dados de vendas.

## Funcionalidades

- **Visualização de dados**: Exibição completa do dataset de vendas
- **Métricas principais**: Receita total e quantidade de vendas
- **Gráficos interativos**: 
  - Mapa de vendas por estado
  - Receita mensal
  - Receita por estado e categoria
  - Performance de vendedores
- **Filtros**: Seleção de vendedores específicos

## Como executar

1. Instale as dependências:
```bash
pip install -r requirements.txt
```

2. Execute a aplicação:
```bash
streamlit run app.py
```

## Estrutura do projeto

- `app.py` - Aplicação principal
- `dataset.py` - Carregamento e processamento dos dados
- `graficos.py` - Geração dos gráficos
- `utils.py` - Funções auxiliares
- `dados/vendas.json` - Dataset de vendas
- `pages/dataframe.py` - Página adicional para visualização de dados

## Tecnologias

- Streamlit
- Plotly
- Pandas