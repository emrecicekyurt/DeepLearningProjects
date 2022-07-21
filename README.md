# DeepLearningProjects
A workspace where I share Deep Learning projects.

## FoodVisionBig Project
A deep learning project that uses the dataset (https://data.vision.ee.ethz.ch/cvl/datasets_extra/food-101/) to classify food image objects. Feature extraction and fine-tuning are used to build a robust model. Also, some helper function are taken from https://github.com/mrdbourke/tensorflow-deep-learning. TensorFlow Datasets Module has been used to import data. TensorFlow input pipeline is used for preprocessing the data with better perfomance. Also, mixed precision is used to increase the performance of GPU (NVIDIA T4 provided by Colab) up to 3x.  
