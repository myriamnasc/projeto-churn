# projeto-churn

# Análise Exploratória de Churn - ABC Multistate Bank

Este projeto tem como objetivo realizar uma análise exploratória de dados (EDA) para entender os fatores que influenciam o churn de clientes (ou seja, a saída de clientes) em um banco fictício chamado **ABC Multistate Bank**.  
A análise foi conduzida utilizando Python e bibliotecas de ciência de dados, em ambiente Jupyter no VS Code.

---

## Sobre o Dataset

O dataset utilizado refere-se ao banco ABC Multistate e contém informações de clientes com o objetivo de analisar o churn, ou seja, a saída de clientes ao longo do tempo.

- 📂 Fonte do Dataset: [Kaggle - Bank Customer Churn Dataset](https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset)


### Colunas 

| Coluna            | Descrição |
|-------------------|-----------|
| `customer_id`     | Identificador único do cliente. (Variável não utilizada na análise) |
| `credit_score`    | Pontuação de crédito do cliente. Usada como input |
| `country`         | País de origem do cliente. Usada como input |
| `gender`          | Gênero do cliente. Usada como input |
| `age`             | Idade do cliente. Usada como input |
| `tenure`          | Tempo de relacionamento com o banco (em anos). Usada como input |
| `balance`         | Saldo na conta do cliente. Usado como input |
| `products_number` | Número de produtos contratados. Usado como input |
| `credit_card`     | Indica se o cliente possui cartão de crédito. Usado como input |
| `active_member`   | Indica se o cliente é um membro ativo. Usado como input |
| `estimated_salary`| Salário estimado do cliente. Usado como input |
| `churn`           | Variável alvo: 1 se o cliente saiu do banco, 0 caso contrário |

---

## Objetivo

O objetivo principal é entender o perfil dos clientes que tendem a deixar o banco, identificando padrões, correlações e comportamentos por meio de uma análise visual e estatística.

---

## Etapas da Análise

1. **Entendimento Inicial dos Dados**
   - Verificação de tipos de dados
   - Estatísticas descritivas

2. **Análise das Variáveis**
   - Distribuição individual de cada variável
   - Comparações por categorias

3. **Análise de Churn**
   - Relação entre a variável churn e os demais atributos
   - Gráficos comparativos e segmentações (por faixa etária, saldo, atividade, etc.)

---

## Ferramentas Utilizadas

- Python 
- Jupyter Notebook (via VS Code)
- Pandas
- NumPy
- Matplotlib
- Seaborn
