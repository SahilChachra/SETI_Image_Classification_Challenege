<h1 align="center">SETI Signal Classification - Help find Extra Terrestrial!</h1>

<div align='center'>
<img src='https://github.com/SahilChachra/SETI_Image_Classification/blob/main/sampleImages/ufo.gif' width="480" height="360"><br>
Above GIF has been downloaded from Pintrest
</div>

<div align= "center">
  <h4>The classification model has been trained in Python using Tensorflow and Keras in Google Colab</h4>
</div>

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
&nbsp;&nbsp;

## :star: Brief about the dataset and the solution.
The dataset has a total of 7000 Images(1000 for each class). In this 5600 images are Train Images(800 per class) and remaining 1400 images are validation images(200 per class). The input images were resized to 192x192 and was passed through ImageDataGenerator to get images which are titlted, zoomed in, etc. The architecture used was ResNet50. All the layers of the architecture were trained which took total 4 hours in Google Colab(GPU allocated was Tesla K80) for 100 epochs with batch size of 64 and 88 iteration per epoch (Iteration = number_of_training_images/Batch_Size).
Training Accuracy achieved was 79.12% and Validation Accuracy achieved was 77.7%. Also Precision, Recall and F1 score achieved were quite good owing to number of epochs used.

## Output
<img src=''></img>

## Accuracy Metrices
### Confusion Matrix
<img src=''></img>

### Classification Report
<img src=''></img>

## :file_folder: Dataset
The dataset used can be downloaded here (Kaggle) - [Click to Download](https://www.kaggle.com/tentotheminus9/seti-data/home)

## :heart: Owner
Made with :heart:&nbsp;  by [Sahil Chachra](https://github.com/SahilChachra)

## :eyes: License
MIT © [Sahil Chachra]()
