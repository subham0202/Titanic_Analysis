Titanic Dataset: Exploratory Data Analysis¶
In this notebook, we're going to analyse the famous Titanic dataset from Kaggle. The dataset is meant for supervised machine learning, but we're only going to do some exploratory analysis at this stage.

We'll try to answer the following questions:

Who were the passengers on the Titanic? (age, gender, class.. etc)
What deck were the passengers on and how does that relate to their class?
Those passanger who were having sibling/spouce and survived
Those passanger who were having sibling/spouce and Not survived
Those passanger who were not having sibling/spouce and survived
<code>
  import pandas as pd
