# GlobalAIHub_DeepLearning_Bootcamp
Global AI Hub Deep Learning Bootcamp Final Project

Dataset: UrbanSound8K

Dataset Description: This dataset contains 8732 labeled sound excerpts (<=4s) of urban sounds from 10 classes: air_conditioner, car_horn, children_playing, dog_bark, drilling, enginge_idling, gun_shot, jackhammer, siren, and street_music. The classes are drawn from the urban sound taxonomy.

CreateSpectrogram: Selects audio files in .wav format. It then converts these audio files into "spectrogram" graphics. It saves these graphics in folders according to their class in .png format.

Preprocessing: We read the spectrogram charts we created. We resize, normalize and grayscale on these files and add them to a list. We shuffle the data so that it is not ordered. We split our dataset to prepare the data for processing. We save the data to a file.

Model: We are creating a CNN model. We measure the training performance of our model. For hyperparameter optimization, we use different activation functions and compare model performances.
