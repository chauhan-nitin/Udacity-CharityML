# Data Scientist Nanodegree
## Supervised Learning

* ```Challenge:``` Udacity Data Scientist Nanodegree project for supervised learning titled as 'Finding Donors for CharityML' is a fictitious charity organization located in the heart of Silicon Valley that was established to provide financial support for people eager to learn machine learning. After nearly 32,000 letters were sent to people in the community, CharityML determined that every donation they received came from someone that was making more than $50,000 annually. To expand their potential donor base, CharityML has decided to send letters to residents of California, but to only those most likely to donate to the charity. 

* ```Solution:``` Using Data Exploration identify any skewness in the features since it affects understanding of the data summary. Normalized the continuous varibale, preprocessed and cleaned the data. Created a baseline model and evaluated it against a model using feature selection.

### Software and Libraries
This project uses the following software and Python libraries: <br>
NumPy, pandas, scikit-learn (v0.17), Matplotlib

Code
Template code is provided in the finding_donors.ipynb notebook file. You will also be required to use the included visuals.py Python file and the census.csv dataset file to complete your work. While some code has already been implemented to get you started, you will need to implement additional functionality when requested to successfully complete the project. Note that the code included in visuals.py is meant to be used out-of-the-box and not intended for students to manipulate. If you are interested in how the visualizations are created in the notebook, please feel free to explore this Python file.

* ```Result:``` Using the following software and Python libraries: NumPy, Pandas, Scikit-Learn (v0.17), Matplotlib. Thus, as a result of above approach we concluded by listing out customers which are likely to donate and would be suitable for the charity organization to approach them. Also, we could estimate the amount of donation the charity could collect from each customer.

### Code File
Open file jupyter notebook finding_donors.ipynb

### Data Description
The modified census dataset consists of approximately 32,000 data points, with each datapoint having 13 features. This dataset is a modified version of the dataset published in the paper "Scaling Up the Accuracy of Naive-Bayes Classifiers: a Decision-Tree Hybrid", by Ron Kohavi. You may find this paper online, with the original dataset hosted on UCI.

*Features*

* ```age```: Age
* ```workclass```: Working Class (Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked)
* ```education_level```: Level of Education (Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool)
* ```education-num```: Number of educational years completed
* ```marital-status```: Marital status (Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse)
* ```occupation```: Work Occupation (Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces)
* ```relationship```: Relationship Status (Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried)
* ```race```: Race (White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black)
* ```sex```: Sex (Female, Male)
* ```capital-gain```: Monetary Capital Gains
* ```capital-loss```: Monetary Capital Losses
* ```hours-per-week```: Average Hours Per Week Worked
* ```native-country```: Native Country (United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands)
* ```income```: Income Class (<=50K, >50K) [Target]

