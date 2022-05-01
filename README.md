Deep learning for roof segmentation from satellite images.

In this project, a few images are given, around 25 images from satellites, with the corresponding labels, and 5 images without labels for validation. I used a custom model from Unet for this task, and I used "tanh" as an activation function.

# 1.0 - Upload the dataset to google drive.
To make sure this notebook will work correctly you have to upload the dataset to your google drive and then connect google drive with google colab. other than that you have to modify the direction of the dataset. Then unzip the dataset.

# 2.0 - Increase the size of the dataset.
As I mentioned that, the dataset is very small, so I used the Augmentor model in order to increase it.

# 3.0 - Import the important libraries for the trainig.
Building up the unet model and modifying the shape to match the same shape of the input data. Also, I used "tanh" as an activation function.

I used the parameters as follows:
The number of epoch = 100
The batch size = 32
The hyperparameter learning rate = 0.001
Also, I used "Mean square error" to evaluate the loss.

# 4.0 - Testing the model.

# 5.0 - Save the model for later uses.
