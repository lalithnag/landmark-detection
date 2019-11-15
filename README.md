
# Landmark detection in echocardiography

## CNN's

Convolutional Neural Networks can be used for segmentation of medical structures, when adequate expert data is provided. This project uses a U-Net architecture to segment the mitral valve.

## Model used

For this project, a U-Net model was used for the purpose of segmentation. You can find the U-Net paper [here](https://arxiv.org/pdf/1505.04597.pdf). The U-Net architecture uses an encoder-decoder type architecture with skip connections to ensure spatial information is incorporated in the upsampling layers.

## Pre-processing

For the purpose of this project, 4D ultrasound volumes were sliced using different slicing techniques such as start slicing, using the MITK Mitralyzer software. To batch process the data, python scripting functionality of ParaView was used. 

## Built With

* [Tensorflow](https://www.tensorflow.org/) - Tensorflow library for Machine Learning
* [Keras](https://keras.io/) - Built with tensorflow backend
* [Python](https://www.python.org/) - Implemented on PyCharm IDE

## Authors

* [Lalith Nag](https://github.com/lalithnag)
* **Kavya Raju** - M.Sc. in Medical Systems Engineering at Otto-von-Guericke University, Magdeburg

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* This project was undertaken as a team project in the *Computer Assisted Surgeries* group at the *Otto-von-Guericke University*, Magdeburg.
