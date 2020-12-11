# Alzheimer-s-Classification-using-DenseNet169
A CNN model to classify Alzeimer's disease in a patient using DenseNet-169 pretrained keras weights 

The dataset can be found here: 
https://www.kaggle.com/tourist55/alzheimers-dataset-4-class-of-images <br />

DenseNet architecture explicitly differentiates between information that
is added to the network and information that is preserved.
DenseNet layers are very narrow (e.g., 12 filters per layer),
adding only a small set of feature-maps to the “collective
knowledge” of the network and keep the remaining featuremaps unchanged—and the final classifier makes a decision
based on all feature-maps in the network.
Besides better parameter efficiency, one big advantage of
DenseNets is their improved flow of information and gradients throughout the network, which makes them easy to
train. Each layer has direct access to the gradients from the
loss function and the original input signal, leading to an implicit deep supervision . This helps training of deeper
network architectures. Further, we also observe that dense
connections have a regularizing effect, which reduces overfitting on tasks with smaller training set sizes. <br />

Instead of drawing representational power from extremely deep or wide architectures, DenseNets exploit the
potential of the network through feature reuse, yielding condensed models that are easy to train and highly parameterefficient. Concatenating feature-maps learned by different
layers increases variation in the input of subsequent layers
and improves efficiency. This constitutes a major difference
between DenseNets and ResNets. Compared to Inception
networks, which also concatenate features from different layers, DenseNets are simpler and more efficient. <br />


The outout looks like :
![Screenshot](al1.png)
![Screenshot](al2.png)
![Screenshot](al3.png)
![Screenshot](al4.png)
