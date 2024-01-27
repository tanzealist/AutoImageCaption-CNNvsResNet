# Caption It! - Harnessing the Power of CNN/ResNet Models for Image Description

## Introduction
"Caption It!" is a deep learning project focusing on the automation of image captioning. Utilizing the Flickr 8k Dataset and pre-trained CNN/ResNet models, this project compares two approaches: CNN+LSTM and ResNet+GRU, evaluating their performance using BLEU scores.

## Agenda
1. Problem Statement
2. Technical Approach
3. Dataset Analysis
4. Exploratory Data Analysis
5. Deep Learning Approaches: VGG16+LSTM and RESNET50+GRU
6. Performance Evaluation
7. Conclusion

## Problem Statement
Our goal was to develop a model that automatically generates captions for images using advanced deep learning techniques.

## Technical Approach
- Import libraries and modules
- Load and preprocess dataset
- Perform feature extraction and caption tokenization
- Model building, training, and evaluation

## Dataset Analysis
The Flickr 8k Dataset, comprising 8000 images each with 5 captions, was used. This dataset offers a diverse range of images and high-quality captions, ideal for training image captioning models. Below are some visuals from the dataset!

## Caption Length Distribution

<p align="center">
  <img width="431" alt="Caption Length Distribution" src="https://github.com/tanzealist/-ImageNarratorPro-Comparative-Analysis-of-CNN-LSTM-and-ResNet-GRU-in-Image-Captioning-/assets/114698958/8be3c39f-9a7c-41ea-8ce7-ccb28c61c6d2">
</p>

## Top 50 Words in the Dataset

<p align="center">
  <img width="431" alt="Top 50 Words" src="https://github.com/tanzealist/-ImageNarratorPro-Comparative-Analysis-of-CNN-LSTM-and-ResNet-GRU-in-Image-Captioning-/assets/114698958/2e072630-ec98-4783-bd81-c8bbafdb0ccb">
</p>

## Model Training Visualization: Sample Image Captions

<p align="center">
  <img width="544" alt="Model Training Visualization" src="https://github.com/tanzealist/-ImageNarratorPro-Comparative-Analysis-of-CNN-LSTM-and-ResNet-GRU-in-Image-Captioning-/assets/114698958/921a568a-4cad-4127-bbb5-591afdd57bda">
</p>

## Deep Learning Approaches
### VGG16 & LSTM
- VGG16: A pre-trained CNN for image classification.
- LSTM: A recurrent neural network excellent for capturing temporal dependencies.

Output of trained VGG16 & LSTM model

<p align="center">
  <img width="570" alt="image" src="https://github.com/tanzealist/-ImageNarratorPro-Comparative-Analysis-of-CNN-LSTM-and-ResNet-GRU-in-Image-Captioning-/assets/114698958/fb4d1f43-c180-4b8c-a6b4-db3517ca218b">



### ResNet50 & GRU
- ResNet50: A deep residual network for image recognition.
- GRU: Efficient at capturing temporal relationships in sequence modeling.

Output of trained ResNet50 & GRU model

<p align="center">
  <img width="570" alt="image" src="https://github.com/tanzealist/-ImageNarratorPro-Comparative-Analysis-of-CNN-LSTM-and-ResNet-GRU-in-Image-Captioning-/assets/114698958/a86c0ee6-7c3e-4990-a14f-551f4e67cdca">



## Performance Evaluation
- Model performance was evaluated using BLEU scores.

BLUE Scores comparision
<p align="center">
  <img width="741" alt="Screenshot 2024-01-27 at 11 10 09 AM" src="https://github.com/tanzealist/-ImageNarratorPro-Comparative-Analysis-of-CNN-LSTM-and-ResNet-GRU-in-Image-Captioning-/assets/114698958/9825ee8b-6430-46fa-8343-2707965a7a87">


- The VGG16+LSTM model exhibited higher BLEU scores, indicating its effectiveness in generating more accurate captions.

## Conclusion
The project reveals the impact of different pre-trained image feature extraction models and sequence models on the quality of generated captions. It opens pathways for further improvements in the field of automated image captioning.

## Dependencies
This project requires the following libraries:
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- PIL
- NLTK

Install these using `pip` or `conda` as shown in the provided Python notebooks.

## Instructions to Run the Project
To run this project, follow these steps:
1. Clone the repository to your local machine.
2. Ensure you have Jupyter Notebook installed.
3. Open and run the `eda.ipynb` notebook for exploratory data analysis.
4. Proceed with `vgg16_lstm.ipynb` for the VGG16+LSTM model training and evaluation.
5. Finally, execute `resnet_gru.ipynb` for the ResNet50+GRU model training and evaluation.
6. Compare the BLEU scores as outputted by the notebooks to evaluate the models.
7. Refer PPT for flow of the project

Please refer to each notebook for detailed instructions on the steps involved in the respective processes.
