# COVID-19 Detection with Active Learning

## Project Overview:
This repository serves as a hub for resources, code, and explanations related to COVID-19 detection leveraging active learning. Active learning, a powerful machine learning paradigm, plays a pivotal role in optimizing the labeling process, enhancing model performance, and making the most of limited labeled data.

## Key Features:
Showcases an active learning framework designed to significantly reduce the annotation burden in training COVID-19 detection models.
Explores the synergy between machine learning and human expertise, where the model intelligently selects the most informative samples for labeling.
Utilizes state-of-the-art deep learning architectures and image processing techniques for robust detection of COVID-19 cases from medical images.
Offers a curated dataset containing diverse medical images for COVID-19, facilitating model training, validation, and experimentation.
Encourages collaborative research and experimentation by providing a well-documented codebase and resources.

![The-active-learning-loop-In-active-machine-learning-data-from-experiments-informs-a](https://user-images.githubusercontent.com/69680607/182359622-76a4c70e-c834-478f-8449-74121c705c01.png)


# Covid-19-detection

Virus
![virus_1](https://user-images.githubusercontent.com/69680607/182359720-dfdf021d-6d36-4b3c-8d9d-8846ab3dd8e6.jpeg)


Normal
![normal_1](https://user-images.githubusercontent.com/69680607/182359731-92966de8-6cc4-4e9b-b04f-6a1ca4be3a0f.jpeg)

## Tensorflow version
in Tensorflow-keras directory run this code:
``` python train.py ```

<br/>

## Pytorch version
in Pytorch directory run this code:
``` python train_torch.py ```

<br/>

## Pytorch Active Learning version
in Active Learning (Pytorch) directory run this code:
``` python train_queries.py ```

<br/>

### Note about the parameters in main running file:<br/>
You can change the hyperparameters in the main running file.<br/>
You can also add more models in the models directory using our importing format<br/>
You can use any datasets and using datasets directory files you can split and preprocess the datasets.<br/>

<br/>

## Results
We achieved 98% validation accuracy using InceptionResnetV2 model and could reach around 0.0002 total validation loss in Active learning and normal classifiers in Pytorch and Tensorflow.
