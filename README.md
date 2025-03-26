# 💨 Análise de Campo de Velocidade com OpenPIV

Este projeto realiza a análise de um **campo de velocidades** a partir de um vídeo experimental usando **Particle Image Velocimetry (PIV)** com a biblioteca OpenPIV. O código foi desenvolvido e testado no **Google Colab**.

## 📽️ Sobre

O vídeo analisado contém partículas em movimento (por exemplo, em um escoamento fluido), e o código aplica algoritmos PIV para estimar a velocidade das partículas quadro a quadro.

---

## 📦 Bibliotecas Utilizadas

- `openpiv` – biblioteca para processamento PIV
- `opencv-python` – para leitura do vídeo
- `numpy` – operações numéricas
- `matplotlib` – visualização

---

## ▶️ Como Rodar

### 1. Suba o vídeo no ambiente Colab (ou ajuste o caminho do vídeo)

### 2. Instale o OpenPIV:

```python
!pip install openpiv

## 👨‍💻 Autor
Projeto desenvolvido por [Gabriel Medeiros].
