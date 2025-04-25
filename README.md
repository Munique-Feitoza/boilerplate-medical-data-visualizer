# Medical Data Visualizer

Este projeto analisa dados médicos coletados durante exames clínicos, utilizando as bibliotecas **Pandas**, **Seaborn** e **Matplotlib** em Python. Ele faz parte do curso de **Análise de Dados com Python** da [freeCodeCamp](https://www.freecodecamp.org/learn/data-analysis-with-python/data-analysis-with-python-projects/medical-data-visualizer).

## 📊 Objetivo

Visualizar e calcular dados relacionados à saúde de pacientes, explorando a relação entre fatores como:

- Níveis de colesterol e glicose
- Hábito de fumar e consumo de álcool
- Atividade física e obesidade
- Pressão arterial e presença de doenças cardiovasculares

A visualização é feita por meio de dois gráficos principais:

- **Gráfico categórico (catplot)** para comparar dados de estilo de vida e saúde entre pessoas com e sem doenças cardíacas.
- **Mapa de calor (heatmap)** para exibir correlações entre os diversos atributos médicos dos pacientes.

## 📁 Estrutura do Projeto

```
📦 medical-data-visualizer/
├── medical_data_visualizer.py   # Arquivo principal com as funções de visualização
├── main.py                      # Script de teste
├── test_module.py               # Testes unitários
├── medical_examination.csv      # Conjunto de dados médicos
└── README.md                    # Este arquivo
```

## 🚀 Como Executar

1. Clone o repositório:
   ```bash
   git clone <url-do-seu-repositório>
   cd medical-data-visualizer
   ```

2. Instale as dependências (se necessário):
   ```bash
   pip install pandas seaborn matplotlib
   ```

3. Execute o script de teste:
   ```bash
   python main.py
   ```

## ✅ Requisitos

- Python 3.x
- pandas
- seaborn
- matplotlib

## 🧪 Testes

Os testes são executados automaticamente ao rodar o `main.py`, que importa as funções de `test_module.py`.

## 📚 Fonte dos Dados

Os dados foram fornecidos pelo curso da freeCodeCamp e representam medidas médicas e escolhas de estilo de vida coletadas durante exames clínicos.

---

Projeto baseado no curso gratuito da [freeCodeCamp](https://www.freecodecamp.org/).
