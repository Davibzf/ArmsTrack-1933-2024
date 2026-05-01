⚔️ Global Arsenal Intelligence

> Análise de 10.000 sistemas de armas militares | 128 países | 1933–2024

![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-2.x-lightblue?logo=pandas)
![Plotly](https://img.shields.io/badge/Plotly-Interactive-purple?logo=plotly)
![Status](https://img.shields.io/badge/Status-Em%20Desenvolvimento-yellow)

---

## 📌 Sobre o Projeto

Este projeto aplica técnicas de **Data Analytics** para explorar o maior dataset público
de sistemas de armas militares disponível no Kaggle. São mais de 10.000 registros cobrindo
11 categorias de armamento — de rifles de assalto a mísseis balísticos — com 36 atributos
por sistema, incluindo especificações técnicas, custo, histórico de combate e status de exportação.

O objetivo é extrair padrões estratégicos, tecnológicos e geopolíticos que respondam
perguntas reais sobre o poder militar global.

---

## 🎯 Perguntas que o projeto responde

- Quais países dominam a produção e exportação de armamentos?
- Como velocidade, alcance e custo evoluíram entre 1933 e 2024?
- Sistemas com combate comprovado são mais adotados internacionalmente?
- Como a compatibilidade NATO influencia os padrões de exportação global?
- Quais categorias de armas têm o maior custo unitário médio?

---

## 📦 Dataset

| Atributo            | Detalhe                                                                                                                               |
|---------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| Linhas              | 10.000                                                                                                                                |
| Colunas utilizadas  | 29 (7 removidas por baixa relevância)                                                                                                 |
| Países de origem    | 128                                                                                                                                   |
| Período coberto     | 1933 – 2024                                                                                                                           |
| Categorias de armas | 11                                                                                                                                    |
| Fonte principal     | [Kaggle — abbas829](https://www.kaggle.com/datasets/abbas829/global-military-arsenal-dataset-weapons-systems)                        |
| Fonte complementar  | [Kaggle — maulikgajera](https://www.kaggle.com/datasets/maulikgajera/global-military-arsenal-dataset-weapons-systems)                |

---

## 🛠️ Tecnologias

| Biblioteca    | Status        | Uso                                      |
|---------------|---------------|------------------------------------------|
| Pandas        | ✅ Utilizado  | Manipulação e limpeza dos dados          |
| Plotly        | ✅ Utilizado  | Visualizações interativas                |
| NumPy         | 🔄 Planejado  | Operações numéricas                      |
| Matplotlib    | 🔄 Planejado  | Visualizações estáticas                  |
| Seaborn       | 🔄 Planejado  | Gráficos estatísticos                    |
| Scikit-learn  | 🔄 Planejado  | Clustering e classificação               |
| NLTK / spaCy  | 🔄 Planejado  | Análise de texto da coluna Notes         |

---

## 📁 Estrutura do Projeto
ArmsTrack-1933-2024/
│

├── ArmsTrack.ipynb       # Notebook principal com toda a análise

├── ArmsTrack.csv         # Dataset principal

├── requirements.txt      # Dependências do projeto

└── README.md             # Documentação

---

## 🚀 Como Executar

```bash
# Clone o repositório
git clone https://github.com/Davibzf/ArmsTrack-1933-2024.git

# Entre na pasta
cd ArmsTrack-1933-2024

# Instale as dependências
pip install pandas plotly nbformat

# Abra o notebook
jupyter notebook ArmsTrack.ipynb
```

---

## ⚠️ Aviso

> Este projeto utiliza dados públicos e destina-se exclusivamente a fins acadêmicos e educacionais.
> Nenhuma informação classificada ou restrita está contida no dataset analisado.
