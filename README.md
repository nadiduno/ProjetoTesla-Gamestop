# Análise de Dados Financeiros: Tesla & GameStop 📊

Este projeto foi desenvolvido como parte do desafio final do curso de Ciência de Dados da IBM. 

O objetivo é realizar a extração, tratamento e visualização de dados financeiros históricos para identificar correlações entre o preço das ações e a receita trimestral das empresas Tesla (TSLA) e GameStop (GME).

## 🛠️ Tecnologias Utilizadas
*   **Linguagem:** Python
*   **Extração de Dados:** `yfinance` e `requests` (Web Scraping)
*   **Manipulação de Dados:** `Pandas`
*   **Visualização:** `Matplotlib`
*   **Ambiente:** Jupyter Notebook

## 📋 Funcionalidades
*   **Coleta:** Extração de dados históricos de mercado via API `yfinance`.
*   **Web Scraping:** Extração de dados de receita trimestral de páginas HTML usando `BeautifulSoup`.
*   **Limpeza:** Tratamento de dados brutos, incluindo remoção de caracteres especiais (`$`, `,`) e limpeza de valores nulos.
*   **Visualização:** Criação de gráficos comparativos para análise temporal.

## 🚀 Como Executar
1. Clone este repositório:
   ```bash
   git clone https://github.com/nadiduno/ProjetoTesla-Gamestop.git

2. Instale as dependências:

```bash
pip install yfinance pandas requests beautifulsoup4 matplotlib
```

3. Abra o Jupyter Notebook:

```bash
jupyter notebook Revenue_Data_and_Building_a_Dashboard.ipynb
```

## 📈 Insights Gerados
O projeto permite visualizar comportamentos distintos de mercado:

GameStop (GME): Identificação clara do fenômeno do short squeeze em 2021, onde houve uma valorização extrema das ações sem uma correspondência direta na receita operacional.

Tesla (TSLA): Observação de um crescimento no preço das ações entre 2020 e 2021 que reflete, em grande parte, o crescimento real e estrutural da receita da companhia.

Projeto desenvolvido para fins educacionais como parte do [IBM]([URL](https://www.coursera.org/account/accomplishments/verify/TY6RJI3SC1AK) Data Science Professional Certificate no site de Coursera.

[Certificado oficial de conclusão da IBM](https://www.coursera.org/account/accomplishments/verify/TY6RJI3SC1AK))
