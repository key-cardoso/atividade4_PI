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
   ![image](https://github.com/user-attachments/assets/25532752-cc2f-4fe6-bb7e-ecd60bf4a25b)
- Em seguida, clique na opção "Image Project":
  ![image](https://github.com/user-attachments/assets/a10d9ace-df15-4690-8dfa-889de3d21477)
- Clique em "Image Project" e depois em "Standard Image Model":
  ![image](https://github.com/user-attachments/assets/17e38c0e-b504-4a6b-8fee-07cbb34277d6)
- Crie suas classes (ex: "Copo", "Caneta"):
  ![image](https://github.com/user-attachments/assets/0029b692-dbd0-4776-86b6-203cbac336f7)
- Grave amostras com sua webcam para cada classe. Clique na opção "Webcam" e capture as imagens do objeto que você quer treinar.
  ![image](https://github.com/user-attachments/assets/ab61e051-c5c1-4503-9589-2c4289f428ce)
Obs: nesse caso estamos usando a webcam, mas você pode tambem fazer uploads das imagens clicando na opção ao lado.
- Após capturar as imagens, clique em "Train Model":
 ![image](https://github.com/user-attachments/assets/f1c1e252-951a-48af-99cb-284e3e0a3eed)
- Após finalizar o treinamento, você pode apontar a webcam para o objeto e verificar se o seu modelo está classificando corretamente os objetos.
- Se estiver tudo certo, clique em "Export Model":
  ![image](https://github.com/user-attachments/assets/3d62508e-d444-4ef8-9066-de545327f9b9)
  
- Para esse projeto, você irá selecionar a opção "Tensorflow", em seguida "Keras", e clique "Download my model":
  ![image](https://github.com/user-attachments/assets/598ce8fb-830d-4f19-b1ad-80ca3ae5ae72)
  
- Isso irá baixar um .zip com os arquivos do modelo
- Extraia o arquivo .zip e use os seguintes arquivos no seu projeto:
    - keras_model.h5 → o modelo treinado
    - labels.txt → os nomes das classes
- Crie uma pasta, com o nome do seu projeto, e cole esses dois arquivos e mais o codigo do link abaixo na mesma pasta:
    - https://github.com/DafzData/Proc_Imag__Vis_Comp__BSI-2024/blob/main/aula6/classficacao_5_objetos-v4.ipynb
      ![image](https://github.com/user-attachments/assets/d98ea749-f4af-4485-9f72-38deaffcfc01)
      
- Baixe também esse arquivo do link abaixo e cole na mesma pasta do seu projeto:
    - https://drive.google.com/file/d/1C1iWpBoH7q0q4A7cupQpclA0bd8FIh7Z/view 
## 🚀 Executando seu projeto
- Abra o Anaconda, se necessario faça login, clique na opção "Environments" e em seguida na opção "import":
  ![image](https://github.com/user-attachments/assets/debed04d-11f2-4074-ab39-ee376a9d8a6b)
- Agora, selecione na pasta do seu projeto o arquivo "env_teste_PI_2024.yaml":
  ![image](https://github.com/user-attachments/assets/68c8e309-8890-4435-99de-72eaa4ff43f9)
- Após importar, garanta que seu ambiente esteja selecionado conforme a imagem a abaixo, se estiver selecionado, clique na opção "home" e abra o VS code:
  ![image](https://github.com/user-attachments/assets/4034d6b1-d3a6-4efc-818b-79caf88f98f4)
- Com o Vs code aberto, abra a pasta do seu projeto clicando em "Open Folder":
  ![image](https://github.com/user-attachments/assets/ed900226-31cc-40ef-bbed-0085a5d95828)
- Agora clique no arquivo "classficacao_5_objetos-v4"
  ![image](https://github.com/user-attachments/assets/5ad3b011-8aa7-42f8-95fd-314136c2d948)
- Agora clique na opção marcada de vermelho na imagem abaixo e selecione o arquivo "env_teste_PI_2024 (1)":
  ![image](https://github.com/user-attachments/assets/b51ba4ec-d0a4-4c5a-8cde-0ed93c57ad94)
- Execute o seu codigo (pode demorar alguns segundos, aguarde), abrirá uma janela com a imagem da Webcam, aponte para um dos objetos que você treinou, e veja se esta classificando corretamente:
 ![OCULOS](https://github.com/user-attachments/assets/1f2ad473-5cbe-4afd-a7e9-aac334068481)
- Caso dei falha na sua camera, abra seu codigo o trecho do codigo para "1":
  ![image](https://github.com/user-attachments/assets/c4f3fd13-ff9c-46a4-9437-35e932fe6252)







## Créditos



