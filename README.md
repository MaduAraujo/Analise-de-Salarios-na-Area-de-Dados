## 📊 Dashboard de Salários na Área de Dados

Este projeto apresenta um dashboard interativo construído com **Streamlit** para analisar dados salariais na área de Dados. Ele permite que os usuários explorem tendências, 
comparem salários por cargo, senioridade e outros fatores, e visualizem a distribuição salarial de forma clara e intuitiva.

## Projeto no ar

https://github.com/user-attachments/assets/f2c6afd1-02b8-4706-9cee-fef3b1851ee4

Link para visualização: https://salarios-dados.streamlit.app/

### ✨ Funcionalidades

O dashboard oferece as seguintes funcionalidades principais:

  * **Filtros Interativos:** A barra lateral permite filtrar os dados por **Ano**, **Senioridade**, **Tipo de Contrato** e **Tamanho da Empresa**, possibilitando uma análise personalizada.
  * **Métricas Chave (KPIs):** Na seção principal, são exibidas métricas como o **salário médio**, **salário máximo**, o **número total de registros** e o **cargo mais frequente**, fornecendo um resumo rápido e objetivo dos dados.
  * **Visualizações Gráficas:** Diversos gráficos foram implementados para facilitar a interpretação dos dados:
      * **Top 10 cargos por salário médio:** Um gráfico de barras que destaca os cargos com os maiores salários.
      * **Distribuição de salários:** Um histograma que mostra a frequência dos salários em diferentes faixas.
      * **Proporção dos tipos de trabalho:** Um gráfico de pizza que exibe a porcentagem de trabalhos presenciais, híbridos e remotos.
      * **Salário médio de Cientista de Dados por país:** Um mapa coroplético que visualiza a média salarial para o cargo de `Data Scientist` em diferentes países.
  * **Tabela de Dados:** Uma tabela detalhada mostra os dados brutos filtrados, permitindo uma inspeção mais aprofundada dos registros.

### 💻 Como Executar o Projeto Localmente

Para rodar este dashboard em sua máquina, siga os passos abaixo:

1.  **Clone o repositório:**

    ```bash
    git clone https://github.com/MaduAraujo/Analise-de-Salarios-na-Area-de-Dados.git
    cd Analise-de-Salarios-na-Area-de-Dados
    ```

2.  **Instale as dependências:**
    Certifique-se de ter o Python instalado. As bibliotecas necessárias são **Streamlit**, **Pandas** e **Plotly Express**. Você pode instalá-las usando o `pip`:

    ```bash
    pip install streamlit pandas plotly-express
    ```

3.  **Execute o aplicativo:**
    Na pasta do projeto, execute o seguinte comando no terminal:

    ```bash
    streamlit run app.py
    ```

    Isso abrirá automaticamente o dashboard no seu navegador padrão.

### 🛠️ Tecnologias Utilizadas

  * **Python:** Linguagem de programação principal.
  * **Streamlit:** Framework para a criação do dashboard interativo.
  * **Pandas:** Biblioteca para manipulação e análise dos dados.
  * **Plotly Express:** Biblioteca para a criação de gráficos interativos e visualizações.

### 🔗 Fonte dos Dados

Os dados utilizados neste projeto são extraídos do seguinte repositório:
`https://raw.githubusercontent.com/MaduAraujo/Analise-de-Salarios-na-Area-de-Dados/main/dados-imersao-final.csv`
