# 📊 Linguagens Utilizadas por Grandes Empresas no GitHub

Este projeto utiliza a **API pública do GitHub** para coletar dados dos repositórios de grandes empresas de tecnologia como **Amazon, Netflix, Spotify, Uber e Microsoft**, com o objetivo de identificar as **linguagens de programação mais utilizadas por cada uma**.

---

## 🚀 O que este projeto faz

- Conecta-se à API do GitHub
- Coleta os nomes e linguagens dos repositórios das empresas
- Gera arquivos `.csv` com os dados de cada empresa
- Cria visualizações em gráfico de barras mostrando as linguagens mais utilizadas
- Faz upload dos dados para um repositório do GitHub via API

---

## 🛠️ Tecnologias Utilizadas

- Python 3
- Requests (para integração com a API)
- Pandas (manipulação dos dados)
- Seaborn & Matplotlib (visualização dos dados)
- GitHub API (v3)

---

## 📁 Estrutura do Projeto

```bash
linguagens-repositorios-empresas/
│
├── dados/
│   ├── linguagens_amzn.csv
│   ├── linguagens_netflix.csv
│   ├── linguagens_spotify.csv
│   ├── linguagens_uber.csv
│   └── linguagens_microsoft.csv
│
├── script_coleta_dados.py     # Classe para buscar e salvar os dados
├── script_envio_arquivo.py    # Classe para criar repositório e enviar arquivos via API
├── script_visualizacao.py     # Gráficos por empresa
├── README.md
