# Paper
R.M. Cichy, K. Dwivedi, B. Lahner, A. Lascelles, P. Iamshchinina, M. Graumann, A. Andonian, N.A.R. Murty, K. Kay, G. Roig, A. Oliva (2021) The Algonauts Project 2021 Challenge: How the Human Brain Makes Sense of a World in Motion, [arXiv:2104.13714](https://arxiv.org/abs/2104.13714)


# Code
## 1. Extract Alexnet features for the videos
* `generate_features_alexnet.py`: to extract pretrained AlexNet features from the videos for all layers of AlexNet.
* Video stimuli in `./AlgonautsVideos268_All_30fpsmax/`
* AlexNet features will be saved `./alexnet`

## 2. Predict fMRI responses
* `perform_encoding.py`: to create predicted fMRI responses for test videos based on AlexNet features or custom Neural Network Layers.
* Real fMRI data in `./participants_data_v2021`
* AlexNet features in `./alexnet`

## 3. [tutorial](./tutorial.ipynb)
