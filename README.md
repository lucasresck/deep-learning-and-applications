# deep-learning-and-applications

[Deep Learning and Applications](https://emap.fgv.br/sites/emap.fgv.br/files/ementa_deep_learning_and_applications.pdf)
summer course (2021, FGV). Professor: Cristian Jose Lopez Del Alamo (Universidad la Salle - Peru).

In this couse, we studied various neural networks architectures, focusing on the implementation, such as CNNs, RNNs, Autoencoders, Variational Autoencoders and GANs.
In this repository, you will find implementations of
- CNN for MNIST ([notebook](https://github.com/lucasresck/deep-learning-and-applications/blob/main/cnn/cnn_mnist.ipynb))
- CNN architecture comparison for COVID-19 detection ([notebook](https://github.com/lucasresck/deep-learning-and-applications/blob/main/cnn/cnn_comparison.ipynb), [YouTube](https://youtu.be/NGKW85Pwxjw))
- social distancing detection with YOLOv5 ([notebook](https://github.com/lucasresck/deep-learning-and-applications/blob/main/cnn/social_distancing_detection.ipynb), [YouTube](https://youtu.be/0q7XxRK1fb8))

## Social distancing detection

[![](https://github.com/lucasresck/deep-learning-and-applications/blob/main/images/social_distance_detection.gif)](https://youtu.be/0q7XxRK1fb8)

I used the model YOLOv5 for the people detection task and I implemented two ways of calculating distances among people:
- The first (naive) way is to calculate the distance among people using the distance among the centers of the detection boxes returned by the model.
- The second way, cooler, is to apply perspective in order to calculate the real distance among people.

More details can be found in the [notebook](https://github.com/lucasresck/deep-learning-and-applications/blob/main/cnn/social_distancing_detection.ipynb) and on [YouTube video](https://youtu.be/0q7XxRK1fb8).
Example of perspective transformation:

[![](https://raw.githubusercontent.com/lucasresck/deep-learning-and-applications/main/images/perspective_transformation.png)](https://github.com/lucasresck/deep-learning-and-applications/blob/main/cnn/social_distancing_detection.ipynb)
