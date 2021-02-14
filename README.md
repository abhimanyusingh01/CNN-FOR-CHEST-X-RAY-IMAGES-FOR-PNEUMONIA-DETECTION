# ML2020 Assignment CA Chest X ray
Github - https://github.com/abhimanyusingh01/ML2020
Kaggle - https://www.kaggle.com/abhimanyuchauhan/chest-x-rays-for-pneumonia-detection
The dataset used is ChestX-ray14 released by Wang et al. (2017) also publicly available on the Kaggle [21] platform
which consists of 112,120 frontal chest X-ray images from 30,085 patients. Each radiographic image in the dataset is
labeled with one or more out of different 14 thoracic diseases. These labels were concluded through Natural
Language Processing (NLP) by text-mining disease-classification from the associated radiological reports and are
expected to be more than 90% accurate. For the sake of this work, following the approaches from the past, we treat
the labels as ground truth for the purpose of pneumonia detection. Prior to the release of this dataset, the largest
publicly available dataset of chest radio-graphs was Openi which consisted of roughly 4,143 X-ray images. All the
radio-graph images in the dataset are of 1024 by 1024 resolution. Out of these 112,120 images, 1431 images are
found to be labeled with pneumonia. In order to balance the dataset for binary classification, 1431 normal X-ray
images (labeled with ’No Findings’) have been selected from the dataset. Altogether, the final dataset used for the
classification task is the subset of the original dataset which consists of 1431 positive image samples (images labeled
with ’Pneumonia’) and 1431 negative image samples (images labeled with ’No Findings’). After that, the dataset was
divided into two parts out of which for the testing, 573 images were randomly selected from the whole final dataset.
The images were downscaled from 1024 by 1024 resolution to 224 by 224 resolution before they were given input to
the network.
