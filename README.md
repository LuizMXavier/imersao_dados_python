# 📊 Dashboard de Salários na Área de Dados

Este é um projeto de análise de dados interativo desenvolvido em **Python** através da imersão da Alura. O objetivo é explorar e visualizar as tendências salariais globais na área de dados, permitindo filtros personalizados por senioridade, tipo de contrato e tamanho da empresa.

🔗 **Acesse o Dashboard online aqui:** [https://imersao-dados-python-aluna.streamlit.app/](https://imersao-dados-python-aluna.streamlit.app/)

## 🚀 Funcionalidades

O dashboard oferece diversas camadas de análise:

* **Filtros Dinâmicos:** Refine a análise por Ano, Nível de Senioridade, Tipo de Contrato e Tamanho da Empresa.
* **Métricas de Desempenho (KPIs):** Visualização rápida da média salarial, salário máximo registrado, total de registros na base e o cargo mais frequente.
* **Análises Gráficas Interativas:**
    * **Top 10 Cargos:** Gráfico de barras com as maiores médias salariais por cargo.
    * **Distribuição Salarial:** Histograma detalhando a frequência das faixas salariais (USD).
    * **Tipo de Trabalho:** Proporção de vagas remotas, presenciais ou híbridas.
    * **Mapa Global:** Média salarial de **Data Scientists** por país (ISO3).
* **Tabela de Dados:** Visualização detalhada dos dados brutos após a aplicação dos filtros.

## 🛠️ Tecnologias Utilizadas

* [Python](https://www.python.org/) - Linguagem de programação.
* [Streamlit](https://streamlit.io/) - Framework para criação do dashboard interativo.
* [Pandas](https://pandas.pydata.org/) - Manipulação e análise de dados.
* [Plotly](https://plotly.com/python/) - Biblioteca para gráficos interativos.

## 📦 Como rodar o projeto localmente

Para executar este dashboard na sua máquina, siga os passos abaixo:

1.  **Clone o repositório:**
    ```bash
    git clone [https://github.com/LuizMXavier/imersao_dados_python.git](https://github.com/LuizMXavier/imersao_dados_python.git)
    cd imersao_dados_python
    ```

2.  **Crie e ative um ambiente virtual (opcional):**
    ```bash
    python -m venv venv
    # No Windows:
    venv\Scripts\activate
    # No Linux/Mac:
    source venv/bin/activate
    ```

3.  **Instale as dependências:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Execute a aplicação:**
    ```bash
    streamlit run app.py
    ```

---

## ✒️ Autor

* **Luiz Xavier** - [GitHub](https://github.com/LuizMXavier)
