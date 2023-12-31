
## Breast-Cancer-Detector

Live Web App: 

<br>

<img src="http://histo.test.woza.work/assets/histo_sample.png" width="350"></img>

<br>

This is a prototype for a freely available online tool that can detect two forms of Breast Cancer in histopathology image patches. The current histopathology process is time consuming and small malignant areas can be missed. This app can help speed up a pathologist's workflow and provide diagnosis support.

<hr>

<b>The app has two models. Each model can detect one of the following:</b>

1. Metastatic Cancer - Cancer that has spread from the site of origin to other area/s of the body.
2. Invasive Ductal Carcinoma - The most common subtype of breast cancer.


<b>These are the papers that discuss the datasets that I used to train the two models:</b>

1399 H&E-stained sentinel lymph node sections of breast cancer patients: the CAMELYON dataset<br>
https://academic.oup.com/gigascience/article/7/6/giy065/5026175

Automatic detection of invasive ductal carcinoma in whole slide images with Convolutional Neural Networks<br>
https://www.researchgate.net/publication/263052166_Automatic_detection_of_invasive_ductal_carcinoma_in_whole_slide_images_with_Convolutional_Neural_Networks


The python code to build and train the models is included in the Jupyter notebook. All the javascript, css and html files are also freely available here. The trained models are also available.

<hr>


Most web browsers don't support the tiff image format. This needs to be kept in mind when pre-processing training data if the intention is to build a web app.
Because Tensorflowjs is a new technology, web apps bulit using it may not work in some browsers. The user will see a message saying the "Ai is loading..." but that message will never go away because the app is actually frozen. It's better to advise users to use the latest version of Chrome.
