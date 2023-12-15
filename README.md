# VGGNet16 
<p align="justify"> VGG16 se refera la modelul VGG, numit si VGGNet. Este un model de retea neurala convoluzionala (CNN) cu suport pentru 16 straturi. Modelul VGG16 poate atinge o precizie de testare de 92,7% in ImageNet, un set de date care contine peste 14 milioane de imagini de antrenament din 1000 de clase de obiecte. Este unul dintre modelele de top din competitia ILSVRC-2014.
VGG16 aduce imbunatatiri fata de AlexNet si inlocuieste filtrele mari cu secvente de filtre mai mici de 3×3. In AlexNet, dimensiunea kernelului este de 11 pentru primul strat convoluzional si 5 pentru al doilea strat. Cercetatorii au antrenat modelul VGG timp de cateva saptamani folosind unitati de procesare grafica (GPU) NVIDIA Titan Black. 


<p align="justify"> The aim of this capstone project is to build a convolutional neural network that classifies different weather conditions while working reasonably well under constraints of computation. The work described in this report translates to two contributions to the field of weather classification. The first one is exploring the use of data augmentation technique, considering different Convolutional Neural Network (CNN) architectures for the feature extraction process when classifying outdoor scenes in a multi-class setting using general-purpose images. The second contribution is the creation of a new, open source dataset, consisting of images collected online that depict scenes of five weather conditions.

<p align="justify"> Transfer Learning with ResNet and VGG neural network architecture on multi-class weather classification problem with dataset collected online containing Creative Commons license retrieved from Flickr, Unsplash and Pexels. The final model (<b>ResNet101</b>) on test-data yields a <b>log-loss</b> of <b><i>0.080738</i></b> with valid accuracy of <b>96.67</b>%.

<div align="center">
    <img height="350" width="400" src="https://github.com/vijayg15/Multi-class-Weather-Classification/blob/master/figures_and_plots/cm_wo_norm.png">
</div>

The final report with model visualizations and validation plots is [here](https://github.com/vijayg15/Multi-class-Weather-Classification/blob/master/wp_project_report.pdf).


# Dependencies :
- Python 3.5
- keras `conda install keras`
- tensorflow `conda install tensorflow`

Note that keras and tensorflow have their own dependencies. I recommend using [Anaconda](https://www.anaconda.com/) for handlinng the packages.

# Dataset :
The Weather dataset can be downloaded from [Kaggle](https://www.kaggle.com/vijaygiitk/multiclass-weather-dataset) (that I've uploaded there).
<p align="center">
    <img height="108" width="90" src="https://github.com/vijayg15/Multi-class-Weather-Classification/blob/master/figures_and_plots/fol.jpg">
</p>

# Usage : 
- Use wp_EDA_preprocessing Notebook to split training and validation data into respective folders.
<p align="center">
    <img height="196" width="96" src="https://github.com/vijayg15/Multi-class-Weather-Classification/blob/master/figures_and_plots/fol_train_val.jpg">
</p>
        
- Read the [wp_project_report](https://github.com/vijayg15/Multi-class-Weather-Classification/blob/master/wp_project_report.pdf) report for understanding the approaches taken in solving this problem
- Notebooks are under the [Notebooks folder](https://github.com/vijayg15/Multi-class-Weather-Classification/tree/master/Notebooks)  and scripts are under the [scripts folder](https://github.com/vijayg15/Multi-class-Weather-Classification/tree/master/scripts).
- All the model diagrams and performance charts are provided.
- The [model weights](https://github.com/vijayg15/Multi-class-Weather-Classification/releases) can be downloaded [here](https://github.com/vijayg15/Multi-class-Weather-Classification/releases) to predict the weather condition.
