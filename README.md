# Autoencoder-based anomaly detection

Building of a simple autoencoder to detect anomalies (and quantify the degree of abnormality) using the TensorFlow framework.
The model presented here is a simple autoencoder with one hidden layer. The number of neurons in the hidden layer is equal to the input-output layers.
The sigmoid activation function is used for all layers and the reconstruction error is assessed using the mean squared error estimator.
The model is used to predict sector configuration transitions, as described in the [ICRAT 2018](http://www.icrat.org/icrat/) paper: "Predicting sector configuration transitions with autoencoder-based anomaly detection" 


## Built With

* [TensorFlow](https://www.tensorflow.org/) - Open source machine learning framework


## Authors

* **Thomas Dubot** 


## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


## Acknowledgments

* How to build autoencoders with TensorFlow: Aurelien Géron "Hands-On Machine Learning with Scikit-Learn and TensorFlow"


