🧠 ## Reconhecimento-Facial-com-MTCNN-e-FaceNet-KNN

Este projeto realiza reconhecimento facial utilizando a rede pré-treinada FaceNet para gerar embeddings (vetores de características) de rostos, e um classificador KNN (K-Nearest Neighbors) para identificar pessoas com base nesses embeddings.

🔧 Tecnologias utilizadas

Python

FaceNet (keras-facenet)

MTCNN (para detecção de faces)

KNN (scikit-learn)

Google Colab

📁 Estrutura do projeto

dataset.zip: Imagens organizadas em pastas por pessoa (ex: John_Lennon/, Paul_McCartney/).


beatles_group.PNG: Imagem com várias pessoas para teste.


knn_face_classifier.joblib: Modelo KNN treinado salvo.


🚀 Etapas do projeto

Upload do dataset zipado contendo rostos rotulados.

Extração de faces com MTCNN.

Geração de embeddings com FaceNet.

Treinamento do modelo KNN com os embeddings.

Reconhecimento facial em uma imagem de grupo.

Visualização com PCA / t-SNE .

Avaliação com métricas (precisão, recall, f1-score).

✅ Resultados

Precisão de 100% na avaliação de teste.

Visualização com t-SNE mostrou separação clara entre os indivíduos.

## Resultado do Reconhecimento

Imagem gerada com as faces detectadas e reconhecidas:

![Resultado do Reconhecimento](grupo_reconhecido.png)




MTSNN

https://mtcnn.readthedocs.io/en/latest/usage/

https://medium.com/data-science/face-detection-using-mtcnn-a-guide-for-face-extraction-with-a-focus-on-speed-c6d59f82d49


https://medium.com/hackernoon/building-a-facial-recognition-pipeline-with-deep-learning-in-tensorflow-66e7645015b8

https://machinelearningmastery.com/how-to-perform-face-detection-with-classical-and-deep-learning-methods-in-python-with-keras/


FaceNet em Keras

https://machinelearningmastery.com/how-to-develop-a-face-recognition-system-using-facenet-in-keras-and-an-svm-classifier/

https://pyimagesearch.com/2023/01/09/face-recognition-with-siamese-networks-keras-and-tensorflow/
