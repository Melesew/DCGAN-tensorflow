# DCGAN in Tensorflow

Tensorflow implementation of [Deep Convolutional Generative Adversarial Networks](http://arxiv.org/abs/1511.06434) which is a stabilize Generative Adversarial Networks. The referenced torch code can be found [here](https://github.com/soumith/dcgan.torch).


## Prerequisites

- Python 2.7 or Python 3.3+
- [Tensorflow](https://github.com/tensorflow/tensorflow/tree/r0.12)
- [SciPy](http://www.scipy.org/install.html)
- [pillow](https://github.com/python-pillow/Pillow)

## Resources

- [Data set](https://github.com/spMohanty/PlantVillage-Dataset)

## Usage

To train a model with downloaded dataset:

    $python main.py --dataset "folder_name" --input_height=100 --output_height=100 --input_fname_pattern='*.JPG' --train

To test with an existing model:

    $ python main.py --dataset "folder_name" --input_height=100 --output_height=100

## Results

- Generated data is found [here](https://gitlab.com/Melesew/plant_disease_detection/blob/master/generated_plant_leafs/.gitkeep)

## Related works

- [BEGAN-tensorflow](https://github.com/carpedm20/BEGAN-tensorflow)
- [DiscoGAN-pytorch](https://github.com/carpedm20/DiscoGAN-pytorch)
- [simulated-unsupervised-tensorflow](https://github.com/carpedm20/simulated-unsupervised-tensorflow)

