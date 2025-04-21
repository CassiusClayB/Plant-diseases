# 🌿 Plant Disease Classifier

Este é um projeto de **classificação de doenças em plantas** baseado em imagens. Ele utiliza um modelo de Deep Learning treinado com Keras e uma aplicação web feita com Flask. A interface permite ao usuário enviar uma imagem da planta e receber como resposta a **classe da doença**, **confiança da previsão** e o **tempo de inferência**.

## 📸 Exemplo da Interface

<p align="center">
  <img src="https://drive.google.com/uc?export=view&id=1h8-Lx2Lmmd5WPmnOSELoyytoTaQz-y0Y" alt="Plant Classifier UI" width="600"/>
</p>


---

## 🚀 Funcionalidades

- Upload de imagem via navegador
- Processamento da imagem e classificação automática
- Interface web responsiva e amigável
- Resultado com confiança e tempo de resposta
- Integração com Docker e Render para deploy contínuo
- Suporte a carregamento do modelo via Google Drive

---

## 🧠 Modelo de Machine Learning

O modelo foi previamente treinado e está hospedado no Google Drive. Durante o primeiro build, ele é baixado automaticamente e salvo no diretório `app/model`.

> **Nota:** o link do modelo é definido via variável de ambiente `MODEL_URL`.

---

## 🧪 Requisitos

- Python 3.8+
- Docker (opcional para produção)
- Conta no [Render.com](https://render.com)

---

## 📦 Instalação e Execução Local

```bash
git clone https://github.com/CassiusClayB/Plant-diseases.git
cd Plant-diseases
python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows
pip install -r requirements.txt
