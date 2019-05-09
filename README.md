# Heart Disease Predicition
## Supervised Machine Learning

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [seaborn](http://seaborn.pydata.org/index.html)
- [scikit-learn](http://scikit-learn.org/stable/)
- [PyDotPlus](https://pydotplus.readthedocs.io/#)
- [Graphviz](https://www.graphviz.org/)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://ipython.org/notebook.html)

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](http://continuum.io/downloads) distribution of Python, which already has the above packages and more included. 

### Code

The code is provided in the `Heart_disease.ipynb` file.

### Run

In a terminal or command window, navigate to the top-level project directory (that contains this README) and run one of the following commands:

```bash
ipython notebook Heart_disease.ipynb
```  
or
```bash
jupyter notebook Heart_disease.ipynb
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

This dataset consists of 303 observations each consisting of 14 features. It comes from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Heart+Disease). It is called `heart.csv` and is available in this repository.

The cost of teh different tests is included in the `heart-disease.cost` file.

**Features**

1. Age
2. Sex
3. cp : Chest Pain Type :
    * Value 1: typical angina 
    * Value 2: atypical angina 
    * Value 3: non-anginal pain 
    * Value 4: asymptomatic 
4. trestbps : resting blood pressure (in mm Hg on admission to the hospital)
5. chol : serum cholestoral in mg/dl
6. fbs : fasting blood sugar > 120 mg/dl (1 = true; 0 = false)
7. restecg : resting electrocardiographic results
    * Value 0: normal 
    * Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV) 
    * Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria 
8. thalach : maximum heart rate achieved during exercise
9. exang : exercise induced angina (1 = yes; 0 = no)
10. oldpeak : ST depression induced by exercise relative to rest
11. slope : the slope of the peak exercise ST segment
    * Value 1: upsloping 
    * Value 2: flat 
    * Value 3: downsloping
12. ca : number of major vessels (0-3) colored by flourosopy
13. thal : thalium heart scan
    * 3 = normal 
    * 6 = fixed defect
    * 7 = reversable defect


**Predicted feature**

14. target : diagnosis of heart disease (angiographic disease status)
    * Value 0: < 50% diameter narrowing 
    * Value 1: > 50% diameter narrowing 
