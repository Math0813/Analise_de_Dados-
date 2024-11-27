# Análise de Cancelamento de Cartões de Crédito

## Descrição do Projeto

Este projeto analisa os principais fatores que levam clientes a cancelar seus cartões de crédito. A análise ajuda a empresa a criar estratégias para retenção e minimizar prejuízos.

---

## Base de Dados

- **Fonte:** [Credit Card Customers - Kaggle](https://www.kaggle.com/sakshigoyal7/credit-card-customers)  
- **Arquivo Utilizado:** `ClientesBanco.csv`

---

## Etapas do Projeto

1. **Importação dos Dados**  
   - Utilizamos a biblioteca `pandas` para carregar e manipular a base de dados.  
   
2. **Tratamento dos Dados**  
   - Removemos colunas irrelevantes e linhas com valores vazios.  

3. **Exploração e Visualização dos Dados**  
   - Analisamos a distribuição e as estatísticas descritivas das variáveis.  
   - Criamos gráficos interativos com `plotly` para identificar padrões.

4. **Análise de Categorias**  
   - Identificamos a proporção de clientes por categoria (`Ativo` e `Cancelado`).  
   - Criamos gráficos para entender os fatores associados ao cancelamento.

---

## Tecnologias Utilizadas

- **Python 3.7+**
- **Bibliotecas:**
  - `pandas`: Manipulação de dados.
  - `plotly.express`: Criação de gráficos interativos.

---

## Configuração do Ambiente

### Em Ambientes Locais (VS Code, PyCharm)

1. **Instale o Python:**  
   - Baixe em [https://www.python.org/](https://www.python.org/).  
   - Certifique-se de marcar "Add Python to PATH" durante a instalação.  

2. **Instale as bibliotecas necessárias:**  
   ```bash
   pip install pandas plotly

3. **Execute o código:**
Salve o script como um arquivo .py e rode no terminal:
python nome_do_script.py

### Em Ambientes Online (Google Colab, Kaggle)

**Google Colab**

O pandas e o plotly já estão instalados. Basta importar as bibliotecas e carregar o arquivo.

**Kaggle Notebooks**

Utilize o caminho correto para carregar o arquivo:

tabela = pd.read_csv("../input/credit-card-customers/ClientesBanco.csv", encoding="latin1")

**Como Executar**
1. Faça o download do arquivo ClientesBanco.csv [aqui](https://www.kaggle.com/sakshigoyal7/credit-card-customers)
2. Configure o ambiente conforme descrito acima.
3. Execute o script principal no terminal ou no notebook.

## Instruções de Uso

1. Faça o download da base de dados do Kaggle .  
2. Clone este repositório:  
   ```bash
   git clone <URL_DO_REPOSITORIO>
   cd <NOME_DO_REPOSITORIO>
