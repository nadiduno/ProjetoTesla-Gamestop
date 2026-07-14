# ProjetoTesla-Gamestop
Extração e visualização de dados históricos de ações e receita da Tesla e GameStop usando Python, yfinance e web scraping (BeautifulSoup).

# Tesla & GameStop — Stock & Revenue Dashboard

Análise de dados históricos de preços de ações e receita trimestral da **Tesla (TSLA)** e **GameStop (GME)**, com visualização em gráficos comparativos.

## 🔧 Tecnologias
- Python
- yfinance — extração de dados de ações
- BeautifulSoup — web scraping de dados de receita
- Pandas — manipulação de dados
- Plotly — visualização gráfica
- Jupyter Notebook

## 📊 O que o projeto faz
- Extrai o histórico completo de preços das ações (TSLA e GME) via `yfinance`
- Faz web scraping da receita trimestral de cada empresa a partir de páginas HTML
- Limpa e trata os dados (remoção de `$`, `,` e valores nulos)
- Gera gráficos comparando preço da ação x receita ao longo do tempo

## 📁 Estrutura
- `Revenue_Data_and_Building_a_Dashboard.ipynb` — notebook principal com todo o código

## 🚀 Como rodar
```bash
pip install yfinance pandas requests beautifulsoup4 plotly
jupyter notebook
```

## 📈 Resultados
O projeto mostra, por exemplo, como o preço da ação da GameStop disparou em 2021 (short squeeze) sem relação direta com a receita da empresa, e como a Tesla teve crescimento acelerado de preço acompanhado de crescimento real de receita entre 2020-2021.
O projeto mostra, por exemplo, como o preço da ação da GameStop disparou em 2021 (short squeeze) sem relação direta com a receita da empresa, e como a Tesla teve crescimento acelerado de preço acompanhado de crescimento real de receita entre 2020-2021.
