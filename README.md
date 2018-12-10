# Skin Lesion Classifier 
A predictive model that uses the HAM10000 dataset, trained on MobileNet to classify skin lesions into seven categories. Our model has been deployed on a web app. http://aryanmisra.me/skinpredict.html

We have trained the model locally using native Keras, then we converted it to TensorflowJS, allowing for a smooth web deployment. Our model's accuracy score settles around 82%, this is partly due to a small and unbalanced dataset. 

Our training process is documented in the jupyter notebook file. The TFJS files, Jupyter Notebook files, as well as our web deployment files are all accessible here. 

Our model was trained on a Paperspace P5000 Notebook; each epoch ran for roughly 15 minutes, totalling to 2 hours and 30 minutes for 10 epochs. 





## Contributers

Aryan Misra – aryanmisra@outlook.com
Alex Yu - alexjyu@yahoo.com

https://github.com/aryanmisra
https://github.com/uyxela

## Acknowledgements

1. (Marsh's Skin Lesion Analyzer) - [https://www.kaggle.com/vbookshelf/skin-lesion-analyzer-tensorflow-js-web-app/notebook]
2. (HAM10000 Dataset) - [https://arxiv.org/ftp/arxiv/papers/1803/1803.10417.pdf]
3. (Skin Lesion Classification) - [https://arxiv.org/pdf/1812.02316.pdf]