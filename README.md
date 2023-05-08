# Economic Crisis Predictooor

The goal of this project is to attempt predicting banking crises using different indices for various Latin American countries. We are using data from The World Bank, the Heritage Foundation’s Economic Freedom Index, the Fraser Institute’s Economic Freedom Index, and Reinhart and Rogoff’s dataset recording economic crises for their book “This Time Is Different” was used for the generation of these models. 

### Tools
Python with TensorFlow and Keras machine learning libraries, and MatLab with Classification Learner.

### MatLab
In order to view the Decision Tree in MatLab, use the following code:
view(trainedModel.ClassificationTree,'Mode','graph')

Change "trainedModel" for whatever you named your model to.

### Python
Dependencies
---------------
pip install "tensorflow<2.11"<br>
pip install wbgapi<br>

optional

pip install netron<br>
pip install seaborn<br>
pip install plotly<br>

### Data
Most of the data was gathered from World Bank [website](https://datatopics.worldbank.org/world-development-indicators/)<br>
It can be selected manually on the website or pulled with an API <br>
### API
There is a great library called [wbgapi](https://github.com/tgherzog/wbgapi) that can pull the data from World Bank API<br>
API key is not necessary to request data!<br>





