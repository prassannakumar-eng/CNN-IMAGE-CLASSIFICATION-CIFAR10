# CNN-IMAGE-CLASSIFICATION-CIFAR10

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: PRASSANNA KUMAR

*INTERN ID*: CT04DY1376

*DOMAIN*: MACHINE LEARNING

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

This task involves building an image classification model using Convolutional Neural Networks (CNN), a deep learning technique widely used for analyzing visual data. The objective of this task is to classify images into different categories by extracting important features using convolutional layers. CNNs are particularly effective in image-related tasks because they can automatically detect patterns such as edges, textures, and shapes.

In this task, a dataset such as CIFAR-10 is used, which contains images belonging to different categories like animals and vehicles. The images are first loaded and preprocessed by normalizing pixel values to improve model performance. The dataset is then split into training and testing sets to evaluate the model’s accuracy.

A CNN model is built using multiple layers, including convolutional layers, pooling layers, and fully connected layers. Convolutional layers are responsible for feature extraction, while pooling layers reduce the dimensionality of the data and improve computational efficiency. Fully connected layers are used for classification. The model is compiled using an optimizer and loss function, and then trained over several epochs to learn patterns from the dataset.

After training, the model is evaluated using test data to measure its accuracy. Graphs are plotted to visualize training and validation accuracy over time, which helps in understanding the learning behavior of the model. Predictions can also be made on new images to demonstrate the model’s effectiveness.

The tools used in this task include Python, TensorFlow, and Keras for deep learning implementation, along with Matplotlib for visualization. The editor platform used is typically Google Colab or Jupyter Notebook, as they provide GPU support and an interactive environment for training deep learning models.

This task has wide applications in real-world scenarios such as facial recognition, medical image analysis, object detection, and autonomous driving systems. CNNs are used in healthcare for detecting diseases from medical images, in security systems for face detection, and in e-commerce for product recognition.

Overall, this task provides a strong understanding of deep learning concepts and demonstrates how neural networks can be used for image classification. It also highlights the importance of data preprocessing, model architecture, and evaluation in building accurate models.

OUTPUT:
Downloading data from https://www.cs.toronto.edu/~kriz/cifar-10-python.tar.gz
170498071/170498071 ━━━━━━━━━━━━━━━━━━━━ 4s 0us/step

/usr/local/lib/python3.12/dist-packages/keras/src/layers/convolutional/base_conv.py:113: UserWarning: Do not pass an `input_shape`/`input_dim` argument to a layer. When using Sequential models, prefer using an `Input(shape)` object as the first layer in the model instead.

  super().__init__(activity_regularizer=activity_regularizer, **kwargs)
  
Epoch 1/10

1563/1563 ━━━━━━━━━━━━━━━━━━━━ 98s 61ms/step - accuracy: 0.4305 - loss: 1.5617 - val_accuracy: 0.5502 - val_loss: 1.2737

Epoch 2/10

1563/1563 ━━━━━━━━━━━━━━━━━━━━ 124s 50ms/step - accuracy: 0.5782 - loss: 1.1977 - val_accuracy: 0.5980 - val_loss: 1.1251

Epoch 3/10

1563/1563 ━━━━━━━━━━━━━━━━━━━━ 78s 47ms/step - accuracy: 0.6306 - loss: 1.0497 - val_accuracy: 0.6367 - val_loss: 1.0368

Epoch 4/10

1563/1563 ━━━━━━━━━━━━━━━━━━━━ 73s 47ms/step - accuracy: 0.6642 - loss: 0.9588 - val_accuracy: 0.6560 - val_loss: 0.9802

Epoch 5/10

1563/1563 ━━━━━━━━━━━━━━━━━━━━ 74s 48ms/step - accuracy: 0.6884 - loss: 0.8880 - val_accuracy: 0.6678 - val_loss: 0.9597

Epoch 6/10

1563/1563 ━━━━━━━━━━━━━━━━━━━━ 74s 48ms/step - accuracy: 0.7081 - loss: 0.8306 - val_accuracy: 0.6874 - val_loss: 0.9166

Epoch 7/10

1563/1563 ━━━━━━━━━━━━━━━━━━━━ 75s 48ms/step - accuracy: 0.7250 - loss: 0.7832 - val_accuracy: 0.6963 - val_loss: 0.8787

Epoch 8/10

1563/1563 ━━━━━━━━━━━━━━━━━━━━ 76s 49ms/step - accuracy: 0.7395 - loss: 0.7416 - val_accuracy: 0.6971 - val_loss: 0.8816

Epoch 9/10

1563/1563 ━━━━━━━━━━━━━━━━━━━━ 74s 47ms/step - accuracy: 0.7503 - loss: 0.7073 - val_accuracy: 0.6907 - val_loss: 0.8922

Epoch 10/10

1563/1563 ━━━━━━━━━━━━━━━━━━━━ 74s 47ms/step - accuracy: 0.7648 - loss: 0.6642 - val_accuracy: 0.7043 - val_loss: 0.8787

313/313 ━━━━━━━━━━━━━━━━━━━━ 4s 14ms/step - accuracy: 0.7043 - loss: 0.8787

Test Accuracy: 0.7042999863624573
