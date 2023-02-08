# Object detection by Fine Tuning
Проект представляет собой решение задачи детекции объектов на собранном мной датасете
## Реализация
1) С помощью imageio собирал и обработал датасет для детекции;
2) Загрузил и применил Fine Tuning на модель resnet50 с помощью tensorflow 2;
3) Построил pipeline сбора данных обучения и предсказания с помощью tensorflow_detection_api;
## Resources
- https://www.tensorflow.org/api_docs/python/tf/keras/applications/resnet50/ResNet50
- https://imageio.readthedocs.io/en/stable/
- https://github.com/tensorflow/models/tree/master/research/object_detection