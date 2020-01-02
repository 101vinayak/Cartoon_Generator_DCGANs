# Image Generator

Python notebook containing TensorFlow DCGAN implementation. It was trained on a [Simpsons Faces](https://www.kaggle.com/kostastokis/simpsons-faces) dataset.

<br>

Check out corresponding Kaggle kernel: [Image Generator](https://www.kaggle.com/greg115/image-generator-dcgan-the-simpsons-dataset).

Check out corresponding Medium article:

[Image Generator - Drawing Cartoons with Generative Adversarial Networks](https://towardsdatascience.com/image-generator-drawing-cartoons-with-generative-adversarial-networks-45e814ca9b6b)

<h3 align="center">
  <img src="homer.gif">
</h3>

## DCGAN
Network architecture by [Radford et al., 2015](https://arxiv.org/abs/1511.06434).
<img src="model.png">

## Training
Visualization of training with the following hyperparameteres.

	IMAGE_SIZE = 128
	NOISE_SIZE = 100
	BATCH_SIZE = 64
	HALF_BATCH = 32
	EPOCHS = 300
	EPSILON = 0.00005
	NO_OF_BATCHES = math.ceil(input_imgs.shape[0]/float(BATCH_SIZE))
	adam = Adam(lr=2e-4, beta_1=0.5)


## Results

These were the generated samples.

<img src="final_grid.png">

