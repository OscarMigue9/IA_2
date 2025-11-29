# Deep Learning For Motion Deblurring

<img width="800" height="300" alt="Deep Learning For Motion Deblurring" src="https://github.com/user-attachments/assets/83db6299-ee74-4b6d-bf3a-d2b86b3d21ab" />

## **Autores**
Juan David Toloza _ 2221067,  Oscar Miguel Ortega _ 2220528, Cristian Alberto Solano _ 2211906.

## **Objetivo**

"Analizar comparativamente estrategias de Deep Learning en la tarea de motion deblurring, contrastando modelos desde cero y transferencia de aprendizaje frente a arquitecturas basadas en Transformers, para lograr una recuperación efectiva de la nitidez y los detalles en las imágenes."

## **Dataset**

- Link del Dataset: https://drive.google.com/file/d/1y4wvPdOG3mojpFCHTqLgriexhbjoWVkK/view?usp=sharing
- Descripción: El GoPro Large Dataset es un referente en tareas de motion deblurring, compuesto por pares de imágenes borrosas y nítidas extraídas de videos de alta velocidad. Este conjunto captura desenfoque realista derivado del movimiento relativo entre la cámara y los objetos. Aunque la resolución nativa es de 1280×720 píxeles, se llevó a cabo un preprocesamiento de redimensionamiento espacial a 224×224 píxeles, gestionado en un notebook independiente llamado Dataset.ipynb. Para la fase experimental, se seleccionó un subconjunto de datos distribuido en 2,814 imágenes para entrenamiento y 400 imágenes para la validación/prueba (test).

## **Modelos**

- Fine Tunning EfficientNetB4
  - Transfer Learning 
  - EfficientNetB4 Backbone 
  - Encoder-Decoder
  - Skip Connections 
  - Conv2DTranspose

- Fine Tunning VGG19
  - Transfer Learning 
  - VGG19 Backbone 
  - Feature Extraction
  - Concatenation (Concat)
  - Batch Normalization (BN)

- Residual Unet
  - Global Residual Connection 
  - Input Identity 
  - Double Conv 
  - Dropout Regularization 
  - MAE + SSIM Loss

- NafNET
  - NAFBlock (Nonlinear Activation Free)
  - SimpleGate
  - Simplified Channel Attention (SCA)
  - LayerNorm 
  - Multi-stage Decoder

- Uptimus
  - LeWinBlock (Locally-enhanced Window)
  - Transformer-based 
  - Window Attention 
  - Conv Transpose2D 
  - Multi-scale Architecture 

## **Enlaces**

- Código: https://github.com/OscarMigue9/IA_2/blob/main/Deblur.ipynb
- Video:
- Repositorio (Github): https://github.com/OscarMigue9/IA_2
