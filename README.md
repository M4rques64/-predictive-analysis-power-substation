# -predictive-analysis-power-substation
AI analysis of a simulated dataset of power substations
# 📊 Subestação — Análise de Anomalias em Transformadores com Isolation Forest

Este projeto aplica técnicas de Machine Learning para **detecção de anomalias** em transformadores de uma rede elétrica, utilizando o algoritmo **Isolation Forest**. O objetivo é identificar comportamentos fora do padrão em tensões, temperaturas e consumo de energia, e **ranquear os transformadores mais críticos para manutenção preditiva**.

## 📂 Dataset

O projeto utiliza um arquivo CSV chamado:

dataset_transformadores_mes_expandido.csv

Colunas principais:
- Data_Hora: Data e hora da leitura
- Transformador: Identificador do transformador
- Tensao_RMS: Valor da tensão RMS
- Temp_Transformador_C: Temperatura do transformador em °C
- Consumo_kWh: Consumo de energia em kWh

## ⚙️ Tecnologias e Bibliotecas

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📌 Funcionalidades

✔️ Engenharia de features (hora, dia da semana, variação de tensão, razão tensão/consumo)  
✔️ Detecção de anomalias com **Isolation Forest**  
✔️ Definição de threshold ideal com **Precision-Recall Curve**  
✔️ Análise de importância das variáveis via **Permutation Importance**  
✔️ Geração de **ranking de transformadores mais críticos**  
✔️ Visualizações de:
- Distribuição de scores de anomalia
- Curva Precision-Recall
- Ranking Top 10 de transformadores mais críticos

## 📈 Como Executar

1️⃣ Clone este repositório:
git clone https://github.com/seuusuario/nome-do-repo.git
cd nome-do-repo

2️⃣ Instale as dependências:
pip install -r requirements.txt

3️⃣ Adicione o dataset no diretório sample_data/  
(ou altere o caminho no código)

4️⃣ Execute o script:
python analise_transformadores.py

## 📊 Resultados

- 📑 Relatório de métricas de classificação (precision, recall, f1-score)
- 📌 Importância das variáveis
- 📊 Ranking dos 10 transformadores com maior número de anomalias detectadas
- 📊 Gráficos de apoio para análise visual

## 📃 Licença

Este projeto está sob licença MIT.  
Sinta-se livre para usar, melhorar e compartilhar.


# 📊 Substation — Transformer Anomaly Detection with Isolation Forest

This project applies Machine Learning techniques for **anomaly detection** in electrical substation transformers using the **Isolation Forest** algorithm. The goal is to identify abnormal behaviors in voltage, temperature, and energy consumption and **rank the most critical transformers for predictive maintenance**.

## 📂 Dataset

The project uses a CSV file named:

dataset_transformadores_mes_expandido.csv

Main columns:
- Data_Hora: Date and time of the reading
- Transformador: Transformer identifier
- Tensao_RMS: RMS voltage value
- Temp_Transformador_C: Transformer temperature in °C
- Consumo_kWh: Energy consumption in kWh

## ⚙️ Technologies and Libraries

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## 📌 Features

✔️ Feature engineering (hour, day of week, voltage variation, voltage/consumption ratio)  
✔️ Anomaly detection using **Isolation Forest**  
✔️ Optimal threshold definition with **Precision-Recall Curve**  
✔️ Feature importance analysis via **Permutation Importance**  
✔️ **Ranking of the most critical transformers**  
✔️ Visualizations including:
- Anomaly score distribution
- Precision-Recall curve
- Top 10 most critical transformers ranking

## 📈 How to Run

1️⃣ Clone this repository:
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name

2️⃣ Install the dependencies:
pip install -r requirements.txt

3️⃣ Add your dataset to the sample_data/ folder  
(or adjust the file path in the script)

4️⃣ Run the script:
python analise_transformadores.py

## 📊 Results

- 📑 Classification report (precision, recall, f1-score)
- 📌 Feature importance table
- 📊 Ranking of the top 10 transformers with the highest number of detected anomalies
- 📊 Supportive visualizations for anomaly score distribution and ranking

## 📃 License

This project is licensed under the MIT License.  
Feel free to use, improve, and share it.
