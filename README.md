
# 📊 Análise de Churn - Telecom X

Este projeto realiza **extração, transformação, análise e visualização de dados** relacionados ao churn (evasão) de clientes de uma operadora fictícia, **Telecom X**.  
O objetivo é identificar padrões e insights que ajudem a prever e reduzir o cancelamento de serviços.

---

## 🚀 Funcionalidades
- **Coleta de dados** via API (JSON).
- **Pré-processamento**: limpeza, renomeação de colunas e padronização de valores.
- **Análise de churn** por tipo de serviço de internet e tempo de contrato.
- **Visualização gráfica** com `Matplotlib` e `Seaborn`.
- **Relatório estratégico** com métricas-chave.

---

## 📂 Estrutura do Projeto
```
📁 projeto-churn-telecomx
│-- 📄 script.py              # Código principal
│-- 📄 requirements.txt       # Dependências do projeto
│-- 📄 README.md               # Documentação
```
---

## 🛠️ Tecnologias Utilizadas
- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Requests](https://docs.python-requests.org/)
- [Matplotlib](https://matplotlib.org/)
- [Seaborn](https://seaborn.pydata.org/)

---

## 📥 Como Executar o Projeto

### 1️⃣ Clonar o repositório
```bash
git clone (https://github.com/lilian-retori/Analise_evasao_clientes_ML.git))
cd projeto-churn-telecomx
```

### 2️⃣ Criar e ativar um ambiente virtual (opcional, mas recomendado)
```bash
python -m venv venv
# Windows
venv\Scripts\activate
# Linux/Mac
source venv/bin/activate
```

### 3️⃣ Instalar as dependências
```bash
pip install -r requirements.txt
```

### 4️⃣ Executar o script
```bash
python script.py
```

---

## 📊 Exemplo de Saída
O script gera no console um **relatório estatístico** contendo:
- Total de clientes
- Total de churn
- Taxa de churn geral
- Taxa de churn por tipo de internet
- Taxa de churn por faixa de tempo de contrato

E também exibe um **gráfico de barras** mostrando a taxa de churn por tipo de internet.

---

## 📌 Próximos Passos
- Criar modelo preditivo para prever clientes com alta probabilidade de churn.
- Adicionar mais visualizações interativas (ex.: `Plotly` ou `Dash`).
- Criar dashboard para acompanhamento contínuo.

---

## 📝 Licença
Este projeto é de uso livre para fins educacionais e pode ser adaptado conforme necessário.

---

💡 **Dica:** Caso queira aprofundar, integre este código com um pipeline de Machine Learning para prever o churn antes que ele aconteça!
