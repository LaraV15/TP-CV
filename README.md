# TP-CV
**Informe:** https://docs.google.com/document/d/1vRiIrs9_e6EUaTHSAjPWnsiwX1P1OCzj81KQIeraHI0/edit?usp=sharing

**Código en Google Colab:** https://drive.google.com/file/d/1cyHaDJ5uT5ppWx-WHSZKrPEycIkaQ5Bw/view?usp=sharing

**Archivos y carpetas de este repositorio:**
1) Carpetas
- dataset: se encuentra el dataset utilizado para el entrenamiento. Dentro de ella se cuentran las carpetas correspondientes a losd atos de test, train y validación.
  - run: es la carpeta obtenida al entrenar el primer modelo, corresponde a YOLOv8l
  - run-2: es la carpeta obtenida al entrenar el segundo modelo, corresponde a YOLOv8m
  - run-3: es la carpeta obtenida al entrenar el tercer modelo, corresponde a YOLOv8s
2) Archivos:
  - Sign_Language_MNIST_dataset.ipynb
  - Sign_Language_MNIST_models.ipynb
Son los archivos correspondientes al dataset y modelo que se probó en primer lugar. El cual luego se descartó.
  - **TP_FINAL.ipynb** es el archivo que contiene todo el código del trabajo. Al principio del readme se adjunta el link al Google Colab correspondiente.
  - abecedario_señas.jpg es una iamgen con las señas del abecedario en el lenguaje de señas.
  - best_1.pt: contiene los pesos del modelo que han mostrado el mejor rendimiento durante el proceso de entrenamiento para el modelo 1.
  - best_2.pt: contiene los pesos del modelo que han mostrado el mejor rendimiento durante el proceso de entrenamiento para el modelo 2.
    - best_3.pt: contiene los pesos del modelo que han mostrado el mejor rendimiento durante el proceso de entrenamiento para el modelo 3.
    - camera.ipynb: contiene el código que se corrió para evaluar el modelo con la cámara de la PC, es decir, en un video en tiempo real. Este código debe ejecutarse en Visual Studio Code, ya que Google Colab no permite encender la cámara.
    - video.mp4.mp4: es el video que se utilizó para testear los modelos.
