# atividade4_PI
## 🔍Descrição do Projeto
Este projeto tem como objetivo treinar um modelo de machine learning para classificação de objetos visuais utilizando a ferramenta online Teachable Machine, com posterior aplicação prática em Python. A atividade consiste na coleta de imagens de cinco objetos diferentes (aproximadamente 200 imagens por classe), treinamento do modelo, testes com câmera em tempo real (via webcam ou aplicativo Iriun) e avaliação da acurácia da identificação dos objetos reconhecidos pelo algoritmo.

## 🔧Instruções de Instalação
Para rodar este projeto, você precisa ter o Anaconda instalado em sua máquina. Siga as instruções abaixo:
- Para baixar o Anaconda, acesse o site oficial e baixe o instalador para o seu sistema operacional (Windows, macOS ou Linux):
  - 🔗 https://www.anaconda.com/products/distribution
- Siga este tutorial passo a passo conforme seu sistema:
- 📘 Tutorial (Windows):
  - 👉 https://youtu.be/JrI9GuV_kZg?si=5ieVkILfzoDZSwLe 
- 📘 Tutorial (Linux e macOS):
  - 👉 https://youtu.be/PLQen8_NqK0?si=EVNBf5Uln0hNKKHc
## ✅ Passos para treinar o modelo:
- Acesse:
- - 🔗 https://teachablemachine.withgoogle.com/
Para melhor experiência, em vez de usar o navegador Chrome, utilize o navegador Firefox para abrir o link acima e treinar seu modelo.
- Após abrir o link clique na opção "Get Started":
- ![image](https://github.com/user-attachments/assets/25532752-cc2f-4fe6-bb7e-ecd60bf4a25b)


Clique em "Image Project" e depois em "Standard Image Model".

Crie suas classes (ex: "Copo", "Caneta", "Nada").

Grave amostras com sua webcam para cada classe.
👉 Quanto mais exemplos, melhor o modelo.

Após capturar as imagens, clique em "Train Model".

Quando o treinamento terminar, clique em "Export Model", depois:

Vá em TensorFlow → Download my model

Isso irá baixar um .zip com os arquivos do modelo

Extraia o arquivo .zip e use os seguintes arquivos no seu projeto:

keras_model.h5 → o modelo treinado

labels.txt → os nomes das classes

Coloque esses arquivos na mesma pasta do seu script Python.
## 🚀 Instruções de Uso



## Créditos



