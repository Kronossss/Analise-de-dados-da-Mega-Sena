# Analise-de-dados-da-Mega-Sena
# 🎰🎲 Mega-Sena AI — Previsão de Números com Deep Learning

Este repositório reúne diferentes abordagens de **Machine Learning e Deep Learning**
para análise e previsão de sequências numéricas da Mega-Sena, utilizando dados históricos
dos sorteios.

⚠️ **Aviso importante**  
Este projeto tem **finalidade exclusivamente educacional e experimental**.  
Não há garantia estatística de acerto em jogos de loteria.

---

## 📊 Técnicas Utilizadas

O projeto explora múltiplos modelos e arquiteturas para aprendizado de padrões numéricos:

- 🔹 Redes Neurais Artificiais (ANN)
- 🔹 Redes Neurais Convolucionais 1D (CNN)
- 🔹 Redes Neurais Recorrentes (RNN)
- 🔹 Transformers
- 🔹 Autoencoders
- 🔹 Análise estatística e correlação
- 🔹 Normalização e escalonamento de dados

---

## 📁 Estrutura do Projeto

```text
mega-sena-ai/
│
├── data/
│   └── Mega-Sena.csv
│
├── notebooks/
│   ├── ann.ipynb
│   ├── cnn.ipynb
│   ├── rnn.ipynb
│   ├── transformer.ipynb
│   ├── autoencoder.ipynb
│   └── analysis.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── models.py
│   └── prediction.py
│
├── results/
│   └── plots/
│
├── README.md
└── requirements.txt

🧠 Modelos Desenvolvidos
✔ ANN (Artificial Neural Network)
- Rede neural densa tradicional
- Utilizada como baseline
- Previsão direta dos números sorteados

✔ CNN
- Tratamento da sequência como sinal temporal
- Uso de convoluções 1D
- Extração de padrões locais

✔ RNN
- Modelagem temporal dos concursos
- Uso de janelas deslizantes (ex: 3, 10, 20 concursos)
- Previsão baseada em histórico sequencial

✔ Transformer
- Atenção multi-head para captura de padrões complexos
- Arquitetura baseada em **Self-Attention**
- Capaz de capturar relações globais entre concursos
- Previsão direta dos 6 números
- Geração estendida para 7 números

✔ Autoencoder
- Redução de dimensionalidade
- Análise de correlação entre números sorteados
- Extração de padrões latentes

🔢 Previsões
O projeto permite gerar:

🎯 Previsão de 6 números
🎯 Previsão estendida de 7 números

O 7º número é gerado de forma controlada e válida (1 a 60)
Evita números duplicados

Exemplo de saída:

[7, 16, 25, 28, 34, 44, 50]

📈 Visualizações
Evolução da soma dos números ao longo do tempo

Comparação entre valores reais e previstos

Análise de correlação entre bolas sorteadas

⚙️ Tecnologias Utilizadas
Python 3.x

Pandas

NumPy

Scikit-learn

TensorFlow / Keras

Matplotlib

🚀 Como Executar
Clone o repositório:

git clone https://github.com/seu-usuario/mega-sena-ai.git

Instale as dependências:

pip install -r requirements.txt
Execute os notebooks no Google Colab ou localmente.

📌 Observações Importantes
Loterias são processos aleatórios

Modelos aprendem padrões históricos, não garantem previsões futuras

👨‍💻 Autor
Projeto desenvolvido para fins educacionais e experimentais
por Igor Alex Farias
