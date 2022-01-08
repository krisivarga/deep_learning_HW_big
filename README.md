<div id="top"></div>


<!-- TABLE OF CONTENTS -->

<details>

<summary>Table of Contents</summary>

<ol>

<li>

<a  href="#about-the-project">About The Project</a>

<ul>

<li><a  href="#built-with">Built With</a></li>

</ul>

</li>

<li>

<a  href="#getting-started">Getting Started</a>

<ul>

<li><a  href="#prerequisites">Prerequisites</a></li>



</ul>

</li>

<li><a  href="#usage">Usage</a></li>

<li><a  href="#roadmap">Roadmap</a></li>

<li><a  href="#contributing">Contributing</a></li>

<li><a  href="#license">License</a></li>

<li><a  href="#contact">Contact</a></li>

<li><a  href="#acknowledgments">Acknowledgments</a></li>

</ol>

</details>

# MKZs deep learning project
  
  

<!-- ABOUT THE PROJECT -->

## About The Project

  This project is an implementation of our semester assignment for "Deep Learning in Practice with Python and LUA" which is a course at Budapest University of Technology and Economics. The aim of  project is to create a well designed and sofisticated deep learning model which is capable of classifying news articles based on their titles and descriptions. In the initial implementation our plan is to train the model to be able to recognise the 5 most popular categories, in later implementation we plan to widen the spectrum of categories as well as the precision of our model. 

<p  align="right">(<a  href="#top">back to top</a>)</p>

  
  
  

### Built With
*  [Python](https://www.python.org/)
*  [TensorFlow](https://www.tensorflow.org/)
*  [skicit-learn](https://scikit-learn.org/stable/)
*  [keras-tuner](https://keras.io/keras_tuner/)


  

<p  align="right">(<a  href="#top">back to top</a>)</p>

  
  
  

<!-- GETTING STARTED -->

## Getting Started



  

### Prerequisites

  

In order to be able to run all scripts, the following packages will be needed.

Python 3.8.* which can easily be installed by installing [Anaconda studio](https://www.anaconda.com/products/individual) which will install the most common libraries for python and jupyter notebook as well.

Besides that users must install TensorFlow and scikit-learn:

```
$ pip install tensorflow
```
```
$ pip install -U scikit-learn
```
```
$ pip install keras-tuner
```

<!-- USAGE EXAMPLES -->

## Usage

Our implementation was done using Google Colab Pro so the whole the whole process can be ran from the same notebook. The model is capable of predicting the categories of news articles base on the categories of input articles. Input sentences should be tokenized and encoded before running training. [data prep and training with fine-tuning] (https://github.com/krisivarga/deep_learning_HW_big/blob/main/LSTM_Text_Class.ipynb) This model creates and saves the best model, which can be later used.

Testing the model can be done by using [testing]( https://github.com/krisivarga/deep_learning_HW_big/blob/main/LSTM_Text_Class_tester.ipynb) notebook. This notebook prepares the data then loads the best model. After that, random sentences are selected which can be used for prediction tests.

Evaluation is done in a separate notebook [eval]( https://github.com/krisivarga/deep_learning_HW_big/blob/main/LSTM_Text_Class_eval.ipynb).


Documentation can be found here: [Documentation]( https://github.com/krisivarga/deep_learning_HW_big/blob/main/documentation.docx) 


Presentation of our work in a video format can be found here: [youtube video]( https://www.youtube.com/watch?v=m5kj9FAvt1k) 
and the presentation slides are here [ppt]( https://github.com/krisivarga/deep_learning_HW_big/blob/46b49ffbf78593c4eab388294c2bbcc91a11bd5e/prez.pptx)

  

<p  align="right">(<a  href="#top">back to top</a>)</p>

  
  
  

<!-- ROADMAP -->

## Roadmap

  
-  [x] Implementation of data retrieval
-  [x] XML processing
-  [x] Getting to know the data we will work with / basic statistics
-  [x] Data processing
-  [x] Basic model implementation
-  [x] Testing initial performance
-  [x] Fine-tune data processing
-  [x] Build deep learing model
-  [x] Testing model performances
training
-  [x] Selecting best model to fine-tune
-  [x] Fine-tune model

 Possible future plans:
-  [x] Broaden choice of categories
-  [x] optimase training time
  
        

<p  align="right">(<a  href="#top">back to top</a>)</p>

  

  
  
  

<!-- LICENSE -->

## License
[GNU GPLv3](https://choosealicense.com/licenses/gpl-3.0/)
  



  

<p  align="right">(<a  href="#top">back to top</a>)</p>

  
  
  

<!-- CONTACT -->

## Contact

  

Győri Mihály - gyori.mihaly@edu.bme.hu <br  />
Varga Kristóf - varga.kristof@edu.bme.hu<br  />
Zsemle Zsolt - zsolt.zsemle@edu.bme.hu


  

Project Link: [https://github.com/krisivarga/deep_learning_HW_big](https://github.com/krisivarga/deep_learning_HW_big)

  

<p  align="right">(<a  href="#top">back to top</a>)</p>

 

  
  
  

<!-- MARKDOWN LINKS & IMAGES -->

© 2021 GitHub, Inc.
