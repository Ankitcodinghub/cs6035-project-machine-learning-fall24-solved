# cs6035-project-machine-learning-fall24-solved
**TO GET THIS SOLUTION VISIT:** [CS6035 Project Machine Learning Fall24 Solved](https://www.ankitcodinghub.com/product/cs-6035-projects-machine-learning-2024-fall-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;125370&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CS6035 Project Machine Learning Fall24 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<h4><u></u><a href="https://www.ankitcodinghub.com/product/cs6035-machine-learning-2025-solved/"><span style="color: #0000ff;"><strong>2025 Solution link</strong></span></a></h4>
Task 1

For the first task, let’s get familiar with some pandas basics. pandas is a Python library that deals with Dataframes, which you can think of as a Python class that handles tabular data. In the real world, you would create graphics and other visuals to better understand the dataset you are working with. You would also use plotting tools like PowerBi, Tableau, Data Studio, and Matplotlib. This step is generally known as Exploratory Data Analysis. Since we are using an autograder for this class, we will skip the plotting for this project.

For this task, we have released a local test suite. If you are struggling to understand the expected input and outputs for a function, please set up the test suite and use it to debug your function.

It’s critical you pass all tests locally before you submit to Gradescope for credit. Do not use Gradescope for debugging.

Theory

In this Task, we’re not yet getting into theory. It’s more nuts and bolts – you will learn the basics of pandas. pandas dataframes are something of a glorified list of lists, mixed in with a dictionary. You get a table of values with rows and columns, and you can modify the column names and index values for the rows. There are numerous functions built into pandas to let you manipulate the data in the dataframe.

To be clear, pandas is not part of Python, so when you look up docs, you’ll specifically want <u>the official P</u>y<u>data pandas docs</u>. Note that we linked to the API docs here, this is the core of the docs you’ll be looking at.

You can always get started trying to solve a problem by looking at Stack Overflow posts in Google search results. There you’ll find ideas about how to use the pandas library. In the end, however, you should find yourself in the habit of looking directly at the docs for whichever library you are using, pandas in this case.

For those who might need a concrete example to get started, here’s how you would take a pandas dataframe column and return the average of its values:

import pandas as pd

<em># create a dataframe from a Python dict</em>

df = pd.DataFrame({“color”:[“yellow”, “green”, “purple”, “red”], “weight”:[124,4.56,384,-2]}) df <em># shows the dataframe</em>

Note that the column names are [“color”,”weight”] while the index is [0,1,2,3…] where […] the brackets denote a list.

Now that we have created a dataframe, we can find the average weight by summing the values under ‘weight’ and dividing them by the sum:

Note: In the example above, we’re not paying attention to rounding, you will need to round your answers to the precision asked for in each Task.

Also note, we are using slightly older versions of the pandas, Python and other libraries so be sure to look at the docs for the appropriate library version. Often there’s a drop-down at the top of docs sites to select the older version.

Refer to the <u>Submissions</u> page for details about submitting your work.

Useful Links:

<ul>
<li><u>pandas documentation — pandas documentation </u>(<u>or</u>g)</li>
<li><u>What is Explorator</u>y<u> Data Anal</u>y<u>sis? – IBM </u> <u>Top Data Visualization Tools – KDnu</u>gg<u>ets</u></li>
</ul>
Deliverables:

<ul>
<li>Complete the functions in task1.py</li>
<li>For this task we have released a local test suite please set that up and use it to debug your function.</li>
<li>Submit task1.py to gradescope</li>
</ul>
Instructions:

The Task1.py file has function skeletons that you will complete with Python code, mostly using the pandas library. The goal of each of these functions is to give you familiarity with the pandas library and some general Python concepts like classes, which you may not have seen before. See information about the function’s inputs, outputs, and skeletons below.

Table of contents

<ul>
<li><u>find_data_type</u></li>
<li><u>set_index_col</u></li>
<li><u>reset_index_col</u></li>
<li><u>set_col_type</u></li>
<li><u>make_DF_from_2d_array</u></li>
<li><u>sort_DF_b</u>y<u>_column</u></li>
<li><u>drop_NA_cols</u></li>
<li><u>drop_NA_rows</u></li>
<li><u>make_new_column</u></li>
<li><u>left_mer</u>g<u>e_DFs_b</u>y<u>_column</u></li>
<li><u>simpleClass</u></li>
<li><u>find_dataset_statistics</u></li>
</ul>
<h1>find_data_type</h1>
In this function you will take a dataset and the name of a column in it. You will return the column’s data type.

Useful Resources <u>https:</u>//<u>pandas.p</u>y<u>data.or</u>g/<u>pandas-docs</u>/<u>stable</u>/<u>reference/api/pandas.DataFrame.dtypes.html</u>

INPUTS

<ul>
<li>dataset – a pandas DataFrame that contains some data</li>
<li>column_name – a Python string (str)</li>
</ul>
OUTPUTS

np.dtype – data type of the column

Function Skeleton

def find_data_type(dataset:pd.DataFrame,column_name:str) -&gt; np.dtype: &nbsp;&nbsp;&nbsp;&nbsp;return np.dtype()

<h1>set_index_col</h1>
In this function you will take a dataset and a series and set the index of the dataset to be the series

Useful Resources <u>https:</u>//<u>pandas.p</u>y<u>data.or</u>g/<u>pandas-docs</u>/<u>stable</u>/<u>reference/api/pandas.Index.html</u>

INPUTS

<ul>
<li>dataset – a pandas DataFrame that contains some data</li>
<li>index – a pandas series that contains an index for the dataset</li>
</ul>
OUTPUTS

a pandas DataFrame indexed by the given index series

Function Skeleton

def set_index_col(dataset:pd.DataFrame,index:pd.Series) -&gt; pd.DataFrame:

return pd.DataFrame()

In this function you will take a dataset with an index already set and reindex the dataset from 0 to n-1, dropping the old index

Useful Resources <u>https:</u>//<u>pandas.p</u>y<u>data.or</u>g/<u>pandas-docs</u>/<u>stable</u>/<u>reference/api/pandas.DataFrame.reset_index.html</u>

INPUTS

<ul>
<li>dataset – a pandas DataFrame that contains some data</li>
</ul>
OUTPUTS

a pandas DataFrame indexed from 0 to n-1

Function Skeleton

def reset_index_col(dataset:pd.DataFrame) -&gt; pd.DataFrame: &nbsp;&nbsp;&nbsp;&nbsp;return pd.DataFrame()

<h1>set_col_type</h1>
In this function you will be given a DataFrame, column name and column type. You will edit the dataset to take the column name you are given and set it to be the type given in the input variable

Useful Resources <u>https:</u>//<u>pandas.p</u>y<u>data.or</u>g/<u>pandas-docs</u>/<u>stable</u>/<u>reference/api/pandas.DataFrame.astype.html</u>

INPUTS

<ul>
<li>dataset – a pandas DataFrame that contains some data</li>
<li>column_name – a string containing the name of a column</li>
<li>new_col_type – a Python type to change the column to</li>
</ul>
OUTPUTS

a pandas DataFrame with the column in column_name changed to the type in new_col_type Function Skeleton

<em># Set astype (string, int, datetime)</em>

def set_col_type(dataset:pd.DataFrame,column_name:str,new_col_type:type) -&gt; pd.DataFrame: &nbsp;&nbsp;&nbsp;&nbsp;return pd.DataFrame()

<h1>make_DF_from_2d_array</h1>
In this function you will take data in an array as well as column and row labels and use that information to create a pandas DataFrame

Useful Resources <u>https:</u>//<u>pandas.p</u>y<u>data.or</u>g/<u>pandas-docs</u>/<u>stable</u>/<u>reference/api/pandas.DataFrame.html</u>

INPUTS

<ul>
<li>array_2d – a 2 dimensional numpy array of values</li>
<li>column_name_list – a list of strings holding column names</li>
<li>index – a pandas series holding the row index’s</li>
</ul>
OUTPUTS

a pandas DataFrame with columns set from column_name_list, row index set from index and data set from array_2d

Function Skeleton

<em># Take Matrix of numbers and make it into a DataFrame with column name and index numbering </em>def make_DF_from_2d_array(array_2d:np.array,column_name_list:list[str],index:pd.Series) -&gt; pd.DataFr &nbsp;&nbsp;&nbsp;&nbsp;return pd.DataFrame()

<h1>sort_DF_by_column</h1>
In this function, you are given a dataset and column name. You will return a sorted dataset (sorting rows by the value of the specified column) either in descending or ascending order, depending on the value in the descending variable.

Useful Resources <u>https:</u>//<u>pandas.p</u>y<u>data.or</u>g/<u>pandas-docs</u>/<u>stable</u>/<u>reference/api/pandas.DataFrame.sort_values.html</u>

INPUTS

<ul>
<li>dataset – a pandas DataFrame that contains some data</li>
<li>column_name – a string that contains the column name to sort the data on</li>
<li>descending – a boolean value (True or False) for if the column should be sorted in descending order</li>
</ul>
OUTPUTS

a pandas DataFrame sorted by the given column name and in descending or ascending order depending on the value of the descending variable

Function Skeleton

<em># Sort DataFrame by values </em>def sort_DF_by_column(dataset:pd.DataFrame,column_name:str,descending:bool) -&gt; pd.DataFrame: &nbsp;&nbsp;&nbsp;&nbsp;return pd.DataFrame()

<h1>drop_NA_cols</h1>
In this function you are given a DataFrame. You will return a DataFrame with any columns containing NA values dropped

Useful Resources <u>https:</u>//<u>pandas.p</u>y<u>data.or</u>g/<u>pandas-docs</u>/<u>stable</u>/<u>reference/api/pandas.DataFrame.dropna.html</u>

INPUTS

<ul>
<li>dataset – a pandas DataFrame that contains some data</li>
</ul>
OUTPUTS

a pandas DataFrame with any columns that contain an NA value dropped

Function Skeleton

In this function you are given a DataFrame you will return a DataFrame with any rows containing NA values dropped

Useful Resources

<u>https:</u>//<u>pandas.p</u>y<u>data.or</u>g/<u>pandas-docs</u>/<u>stable</u>/<u>reference/api/pandas.DataFrame.dropna.html</u>

INPUTS

<ul>
<li>dataset – a pandas DataFrame that contains some data</li>
</ul>
OUTPUTS

a pandas DataFrame with any rows that contain an NA value dropped

Function Skeleton

def drop_NA_rows(dataset:pd.DataFrame) -&gt; pd.DataFrame: &nbsp;&nbsp;&nbsp;&nbsp;return pd.DataFrame()

<h1>make_new_column</h1>
In this function you are given a dataset, a new column name and a string value to fill in the new column. Add the new column to the dataset and return the dataset.

Useful Resources

<u>https:</u>//<u>pandas.p</u>y<u>data.or</u>g/<u>pandasdocs</u>/<u>stable/</u>g<u>ettin</u>g<u>_started</u>/<u>intro_tutorials</u>/<u>05_add_columns.html</u>

INPUTS

<ul>
<li>dataset – a pandas DataFrame that contains some data</li>
<li>new_column_name – a string containing the name of the new column to be created</li>
<li>new_column_value – a string containing a static value that will be set for the new column for every row</li>
</ul>
OUTPUTS

a pandas DataFrame with the new column created named new_column_name and filled with the value in new_column_value Function Skeleton

In this function you are given 2 datasets and the name of a column with which you will left join them on using the pandas merge method. The left dataset is dataset1 right dataset is dataset2, for example purposes.

Useful Resources

<u>https:</u>//<u>pandas.p</u>y<u>data.or</u>g/<u>pandas-docs</u>/<u>stable</u>/<u>reference/api/pandas.DataFrame.mer</u>g<u>e.html https:</u>//<u>stackoverflow.com/questions</u>/<u>53645882/pandas-mer</u>g<u>in</u>g<u>-101</u>

INPUTS

<ul>
<li>left_dataset – a pandas DataFrame that contains some data</li>
<li>right_dataset – a pandas DataFrame that contains some data</li>
<li>join_col_name – a string containing the column name to join the two DataFrames on</li>
</ul>
OUTPUTS

a pandas DataFrame containing the two datasets left joined together on the given column name

Function Skeleton

def left_merge_DFs_by_column(left_dataset:pd.DataFrame,right_dataset:pd.DataFrame,join_col_name:str) &nbsp;&nbsp;&nbsp;&nbsp;return pd.DataFrame()

<h1>simpleClass</h1>
This project will require you to work with Python Classes. If you are not familiar with them we suggest learning a bit more about them.

You will take the inputs into the class initialization and set them as instance variables (of the same name) in the Python class.

Useful Resources <u>https:</u>//<u>www.w3schools.com/p</u>y<u>thon/p</u>y<u>thon_classes.asp</u>

INPUTS

<ul>
<li>length – an integer</li>
<li>width – an integer</li>
<li>height – an integer</li>
</ul>
OUTPUTS

None, just setup the init method in the class.

Function Skeleton

class simpleClass(): &nbsp;&nbsp;&nbsp;&nbsp;def __init__(self, length:int, width:int, height:int): &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pass

<h1>find_dataset_statistics</h1>
Now that you have learned a bit about pandas DataFrames, we will use them to generate some simple summary statistics for a DataFrame. You will be given the dataset as an input variable, as well as a column name for a column in the dataset that serves as a label column. This label column contains binary values (0 and 1) that you also summarize, and also the variable to predict. In this context:

<ul>
<li>0 represents a “negative” sample (e.g. if the column is IsAVirus and we think it is false)</li>
<li>1 represents a “positive” sample (e.g. if the column is IsAVirus and we think it is true)</li>
</ul>
This type of binary classification is common in machine learning tasks where we want to be able to predict the field. An example of where this could be useful would be if we were looking at network data, and the label column was IsVirus. We could then analyze the network data of Georgia Tech services and predict if incoming files look like a virus (and if we should alert the security team).

Useful Resources

<ul>
<li><u>https:</u>//<u>learndatasci.com/</u>g<u>lossary</u>/<u>binar</u>y<u>-classification/</u></li>
<li><u>https:</u>//<u></u>g<u>oo</u>g<u>le.com</u>/<u>machine-learnin</u>g/<u>crash-course</u>/<u>framin</u>g/<u>ml-terminology</u></li>
</ul>
INPUTS

<ul>
<li>dataset – a pandas DataFrame that contains some data</li>
<li>label_col – a string containing the name of the label column</li>
</ul>
OUTPUTS

<ul>
<li>n_records (int) – the number of rows in the dataset</li>
<li>n_columns (int) – the number of columns in the dataset</li>
<li>n_negative (int) – the number of “negative” samples in the dataset (the argument label column equals 0)</li>
<li>n_positive (int) – the number of “positive” samples in the dataset (the argument label column equals 1)</li>
<li>perc_positive (int) – the percentage (out of 100%) of positive samples in the dataset</li>
</ul>
Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">def find_dataset_statistics(dataset:pd.DataFrame,label_col:str) -&gt; tuple[int,int,int,int,int]:

n_records = <em>#TODO </em>&nbsp;&nbsp;n_columns = <em>#TODO </em>&nbsp;&nbsp;n_negative = <em>#TODO </em>&nbsp;&nbsp;n_positive = <em>#TODO </em>&nbsp;&nbsp;perc_positive = <em>#TODO</em>

return n_records,n_columns,n_negative,n_positive,perc_positive
</td>
</tr>
</tbody>
</table>
Disclaimer: You are responsible for the information on this website. The content is subject to change at any time.

CS 6035

<u>Projects </u>/ <u>Machine Learning </u>/ Task 2

Task 2 (25 points)

Now that you have a basic understanding of pandas and the dataset, it is time to dive into some more complex data processing tasks.

Theory

In machine learning a common goal is to train a model on one set of data. Then we validate the model on a similarly structured but different set of data. You could, for example, train the model on data you have collected historically. Then you would validate the model against real-time data as it comes in, seeing how well it predicts the new data coming in.

If you’re looking at a past dataset as we are in these tasks, we need to treat different parts of the data differently to be able to develop and test models. We segregate the data into test and training portions. We train the model on the training data and test the developed model on the test data to see how well it predicts the results.

You should never train your models on test data, only on training data.

<h1>Notes</h1>
At a high level it is important to hold out a subset of your data when you train a model. You can see what the expected performance is on unseen sample. Thus, you can determine if the resulting model is overfit (performs much better on training data vs test data).

Preprocessing data is essential because most models only take in numerical values. Therefore, categorical features need to be “encoded” to numerical values so that models can use them. A machine learning model may not be able to make sense of “green”, “blue” and “red.” In preprocessing, we’ll convert those to integer values 1, 2 and 3, for example. It’s an interesting question as to what happens when you have training data that has “green,” “red” and blue,” but your testing data says “yellow.”

Numerical scaling can be more or less useful depending on the type of model used, but it is especially important in linear models. Numerical scaling is typically taking positive value and “compressing” them into a range between 0 and 1 (inclusive) that retains the relationships among the original data.

These preprocessing techniques will provide you with options to augment your dataset and improve model performance.

Useful Links:

<ul>
<li><u>Trainin</u>g<u> and Test Sets – Machine Learnin</u>g<u> – Goo</u>g<u>le Developers</u></li>
<li><u>Bias–variance tradeoff – Wikipedia</u></li>
<li><u>Overfittin</u>g<u> – Wikipedia</u></li>
<li><u>Cate</u>g<u>orical and Numerical Types of Data – 365 Data Science</u></li>
<li><u>scikit-learn: machine learnin</u>g<u> in P</u>y<u>thon — scikit-learn 1.2.1 documentation</u></li>
</ul>
Deliverables:

<ul>
<li>Complete the functions and methods in task2.py</li>
<li>For this task we have released a local test suite please set that up and use it to debug your function.</li>
<li>Submit task2.py to Gradescope when you pass all local tests. Refer to the <u>Submissions</u> page for details.</li>
</ul>
Instructions:

The Task2.py File has function skeletons that you will complete with python code (mostly using the pandas and scikit-learn libraries). The Goal of each of these functions is to give you familiarity with the applied concepts of Splitting and Preprocessing Data. See information about the Function’s Inputs, Outputs and Skeletons below

Table of contents

<ul>
<li><u>tts</u></li>
<li><u>PreprocessDataset</u></li>
</ul>
a <u>__init__ </u>b&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <u>One Hot Encoding </u>c&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <u>Min</u>/<u>Max Scaling</u>

<ul>
<li><u>PCA</u></li>
<li><u>Feature En</u>g<u>ineering </u>f <u>Preprocess</u></li>
</ul>
tts

In this function, you will take:

<ul>
<li>a dataset</li>
<li>the name of its label column</li>
<li>a percentage of the data to put into the test set</li>
<li>whether you should stratify on the label column</li>
<li>a random state to set the scikit-learn function</li>
</ul>
You will return features and labels for the training and test sets.

At a high level, you can separate the task into two subtasks. The first is splitting your dataset into both features and labels (by columns), and the second is splitting your dataset into training and test sets (by rows). You should use the scikit-learn train_test_split function but will have to write wrapper code around it based on the input values we give you.

Useful Resources

<ul>
<li><u>https:</u>//<u>scikit-learn.or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>model_selection.train_test_split.html</u></li>
<li><u>https:</u>//<u></u>g<u>oo</u>g<u>le.com</u>/<u>machine-learnin</u>g/<u>crash-course</u>/<u>framin</u>g/<u>ml-terminology</u></li>
<li><u>https:</u>//<u>com/questions</u>/<u>40898019</u>/<u>what-is-the-difference-between-a-featureand-a-label</u></li>
</ul>
INPUTS

<ul>
<li>dataset – a pandas DataFrame that contains some data</li>
<li>label_col – a string containing the name of the column that contains the label values (what our model wants to predict)</li>
<li>test_size – a float containing the decimal value of the percentage of the number of rows that the test set should be out of the dataset</li>
<li>stratify – a boolean (True or False) value indicating if the resulting train/test split should be stratified or not</li>
<li>random_state – an integer value to set the randomness of the function (useful for repeatability especially when autograding)</li>
</ul>
OUTPUTS

<ul>
<li>train_features – a pandas DataFrame that contains the train rows and the feature columns</li>
<li>test_features – a pandas DataFrame that contains the test rows and the feature columns</li>
<li>train_labels – a pandas DataFrame that contains the train rows and the label column</li>
<li>test_labels – a pandas DataFrame that contains the test rows and the label column</li>
</ul>
Function Skeleton

def tts(&nbsp; dataset: pd.DataFrame, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;label_col: str,&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; test_size: float, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;stratify: bool, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;random_state: int) -&gt; tuple[pd.DataFrame,pd.DataFrame,pd.Series,pd.Series]:

<em># TODO</em>

return train_features,test_features,train_labels,test_labels

<h1>PreprocessDataset</h1>
The PreprocessDataset Class contains a code skeleton with nine methods for you to implement. Most methods will be split into two parts: one that will be run on the training dataset and one that will be run on the test dataset. In Data Science/Machine Learning, this is done to avoid something called <em><u>Data Leaka</u></em><em>g<u>e</u></em>.

For this assignment, we don’t expect you to understand the nuances of the concept, but we will have you follow principles that will minimize the chances of it occurring. You will accomplish this by splitting data into training and test datasets and processing those datasets in slightly different ways.

Generally, for everything you do in this project, and if you do any ML or Data Science work in the future, you should train/fit on the training data first, then predict/transform on the training and test data. That holds up for basic preprocessing steps like task 2 and for complex models like you will see in tasks 3 and 4.

For the purposes of this project, you should never train or fit on the test data (and more generally in any ML project) because your test data is expected to give you an understanding of how your model/predictions will perform on unseen data. If you fit even a preprocessing step to your test data, then you are either giving the model information about the test set it wouldn’t have about unseen data (if you combine train and test and fit to both), or you are providing a different preprocessing than the model is expecting (if you fit a different preprocessor to the test data), and your model would not be expected to perform well.

Note: You should train/fit using the train dataset; then, once you have a fit encoder/scaler/pca/model instance, you can transform/predict on the training and test data.

You will also notice that we are only preprocessing the Features and not the Labels. There are a few cases where preprocessing steps on labels may be helpful in modeling, but they are definitely more advanced and out of the scope of this introduction. Generally, you will not need to do any preprocessing to your labels beyond potentially encoding a string value (i.e., “Malware” or “Benign”) into an integer value (0 or 1), which is called <em><u>Label Encodin</u></em><em>g</em>.

<h1>PreprocessDataset:__init__</h1>
Similar to the Task1 simpleClass subtask you previously completed you will initialize the class by adding instance variables (add all the inputs to the class).

Useful Resources

<ul>
<li><u>https:</u>//<u>w3schools.com/p</u>y<u>thon/p</u>y<u>thon_classes.asp</u></li>
</ul>
INPUTS

<ul>
<li>one_hot_encode_cols – a list of column names (strings) that should be one hot encoded by the one hot encode methods</li>
<li>min_max_scale_cols – a list of column names (strings) that should be min/max scaled by the min/max scaling methods</li>
<li>n_components – an int that contains the number of components that should be used in Principal Component Analysis</li>
<li>feature_engineering_functions – a dictionary that contains feature name and function to create that feature as a key value pair (example shown below)</li>
</ul>
Example of feature_engineering_functions:

<table width="679">
<tbody>
<tr>
<td width="679">def double_height(dataframe:pd.DataFrame):

return dataframe[“height”] * 2

def half_height(dataframe:pd.DataFrame):

return dataframe[“height”] / 2

&nbsp;

feature_engineering_functions = {“double_height”:double_height,”half_height”:half_height}
</td>
</tr>
</tbody>
</table>
Don’t worry about copying it we also have examples in the local test cases this is just provided as an illustration of what to expect in your function.

OUTPUTS

None, just assign all the input parameters to class variables.

Also per the instructions below, you’ll return here and create another instance variable: a scikitlearn OneHotEncoder with any Parameters you may need later.

Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">def __init__(self,

one_hot_encode_cols:list[str], &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;min_max_scale_cols:list[str], &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;n_components:int,

feature_engineering_functions:dict &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;):

<em># TODO: Add any instance variables you may need to make your functions work </em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return
</td>
</tr>
</tbody>
</table>
PreprocessDataset:one_hot_encode_columns_train and one_hot_encode_columns_test

One Hot Encoding is the process of taking a column and returning a binary vector representing the various values within it. There is a separate function for the training and test datasets since they should be handled separately to avoid data leakage (see the 3rd link in Useful Resources for a little more info on how to handle them).

Pseudocode

one_hot_encode_columns_train()

<ul>
<li>In the PreprocessDataset __init__() method initialize an instance variable containing a scikitlearn OneHotEncoder with any parameters you may need.</li>
<li>Split train_features into two DataFrames: one with only the columns you want to one hot encode (using one_hot_encode_cols) and another with all the other columns.</li>
<li>Fit the OneHotEncoder using the DataFrame you split from train_features with the columns you want to encode.</li>
<li>Transform the DataFrame you split from train_features with the columns you want to encode using the fitted OneHotEncoder.</li>
<li>Create a DataFrame from the 2D array of data that the output from step 4 gave you, with column names in the form of columnName_categoryName (there should be an attribute in</li>
</ul>
OneHotEncoder that can help you with this) and the same index that train_features had.

<ul>
<li>Concatenate the DataFrame you made in step 5 with the DataFrame of other columns from step 2. one_hot_encode_columns_test()</li>
<li>Split test_features into two DataFrames: one with only the columns you want to one hot encode (usingone_hot_encode_cols) and another with all the other columns.</li>
<li>Transform the DataFrame you split from test_features with the columns you want to encode using the OneHotEncoder you fit in one_hot_encode_columns_train()</li>
<li>Create a DataFrame from the 2D array of data that the output from step 2 gave you, with column names in the form of columnName_categoryName (there should be an attribute in</li>
</ul>
OneHotEncoder that can help you with this) and the same index that test_features had.

<ul>
<li>Concatenate the DataFrame you made in step 3 with the DataFrame of other columns from step 1.</li>
</ul>
Example Walkthrough (from Local Testing suite):

INPUTS:

one_hot_encode_cols

[“color”,”version”]

Train Features

2.

DataFrame with columns to encode:

5.

One Hot Encoded DataFrame with Index and Column Names

Final DataFrame with passthrough/other columns joined back

TEST DATAFRAMES AT EACH STEP:

1.

DataFrame with columns to encode:

DataFrame with other columns:

One Hot Encoded 2d array:

One Hot Encoded DataFrame with Index and Column Names

Final DataFrame with passthrough columns joined back

Note: For the local tests and autograder use the column naming scheme of joining the previous column name and the column value with an underscore (similar to above where Type -&gt; Type_Fruit and Type_Vegetable)

Note 2: Since you should only be fitting your encoder on the training data, if there are values in your test set that are different than those in the training set, you will denote that with 0s. In the example above, let’s say we have a row in the test set with pizza, which is neither a fruit nor vegetable for the Type_Fruit and Type_Vegetable. It should result in a 0 for both columns. If you don’t handle these properly, you may get errors like Test Failed: Found unknown categories.

Note 3: You may be tempted to use the pandas function get_dummies to solve this task, but its a trap. It seems easier, but you will have to do a lot more work to make it handle a train/test split. So, we suggest you use scikit-learn’s OneHotEncoder.

Useful Resources

<ul>
<li><u>https:</u>//<u>educative.io</u>/<u>blo</u>g/<u>one-hot-encoding</u></li>
<li><u>https:</u>//<u></u>g<u>oo</u>g<u>le.com</u>/<u>machine-learnin</u>g/<u>data-prep</u>/<u>transform</u>/<u>transform-cate</u>g<u>orical</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.preprocessin</u>g<u>.OneHotEncoder.html#sklearn.prepr ocessin</u>g<u>.OneHotEncoder</u></li>
<li><u>https:</u>//<u>stackexchan</u>g<u>e.com/questions</u>/<u>103211</u>/<u>do-we-need-to-pre-process-boththe-test-and-train-data-set</u></li>
</ul>
INPUTS

<ul>
<li>Use the needed instance variables you set in the __init__ method</li>
<li>train_features – a dataset split by a function similar to tts which should be used in the training/fitting steps</li>
<li>test_features – a dataset split by a function similar to tts which should be used in the test steps</li>
</ul>
OUTPUTS

a pandas DataFrame with the columns listed in one_hot_encode_cols one hot encoded and all other columns in the DataFrame unchanged

Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">def one_hot_encode_columns_train(self,train_features:pd.DataFrame) -&gt; pd.DataFrame:

one_hot_encoded_dataset = pd.DataFrame() &nbsp;&nbsp;&nbsp;&nbsp;return one_hot_encoded_dataset def one_hot_encode_columns_test(self,test_features:pd.DataFrame) -&gt; pd.DataFrame:

one_hot_encoded_dataset = pd.DataFrame() &nbsp;&nbsp;&nbsp;&nbsp;return one_hot_encoded_dataset
</td>
</tr>
</tbody>
</table>
PreprocessDataset:min_max_scaled_columns_train and min_max_scaled_columns_test

Min/Max Scaling is a process to transform numerical features to a specific range, typically [0, 1], to ensure that input values are comparable (similar to how you may have heard of “normalizing” data) and is a crucial preprocessing step for many machine learning algos. In particular this standardization is essential for algorithms like linear regression, logistic regression, k-means, and neural networks, which can be sensitive to the scale of input features, whereas some algos like decision trees are less impacted.

By applying Min/Max Scaling, we prevent feature dominance, to ideally improve performance and accuracy of these algorithms and improve training convergence. It’s a recommended step to ensure your models are trained on consistent and standardized data.

For the provided assignment you should use the scikit-learn MinMaxScaler function (linked in the resources below) rather than attempting to implement your own scaling function.

The <em>rough</em> implementation of the scikit-learn function is provided below for educational purposes.

X_std = (X – X.min(axis=0)) / (X.max(axis=0) – X.min(axis=0))

X_scaled = X_std * (max – min) + min

Note: There are separate functions for the training and test datasets to help avoid data leakage between the test/train datasets. Please refer to the 3rd link in Useful Resources for more information on how to handle this – namely that we should still scale the test data based on our “knowledge” of the train dataset.

Example Dataframe:

Note: For the Autograder use the same column name as the original column (ex: Price -&gt; Price)

Useful Resources

<ul>
<li><u>https:</u>//<u></u>g<u>oo</u>g<u>le.com</u>/<u>machine-learnin</u>g/<u>data-prep</u>/<u>transform</u>/<u>normalization</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.preprocessin</u>g<u>.MinMaxScaler.html#sklearn.preproc essin</u>g<u>.MinMaxScaler</u></li>
<li><u>https:</u>//<u>stackexchan</u>g<u>e.com/questions</u>/<u>103211</u>/<u>do-we-need-to-pre-process-boththe-test-and-train-data-set</u></li>
</ul>
INPUTS

<ul>
<li>Use the needed instance variables you set in the __init__ method</li>
<li>train_features – a dataset split by a function similar to tts which should be used in the training/fitting steps</li>
<li>test_features – a dataset split by a function similar to tts which should be used in the test steps</li>
</ul>
OUTPUTS

a pandas DataFrame with the columns listed in min_max_scale_cols min/max scaled and all other columns in the DataFrame unchanged

Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">&nbsp;&nbsp;&nbsp; def min_max_scaled_columns_train(self,train_features:pd.DataFrame) -&gt; pd.DataFrame:

min_max_scaled_dataset = pd.DataFrame() &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return min_max_scaled_dataset &nbsp;&nbsp;&nbsp;&nbsp;def min_max_scaled_columns_test(self,test_features:pd.DataFrame) -&gt; pd.DataFrame:

min_max_scaled_dataset = pd.DataFrame() &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return min_max_scaled_dataset
</td>
</tr>
</tbody>
</table>
<h1>PreprocessDataset:pca_train and pca_test</h1>
Principal Component Analysis is a dimensionality reduction technique (column reduction). It aims to take the variance in your input columns and map the columns into N columns that contain as much of the variance as it can. This technique can be useful if you are trying to train a model faster and has some more advanced uses, especially when training models on data which has many columns but few rows. There is a separate function for the training and test datasets because they should be handled separately to avoid data leakage (see the 3rd link in Useful Resources for a little more info on how to handle them).

Note 1: For the local tests and autograder, use the column naming scheme of column names: component_1, component_2 .. component_n for the n_components passed into the __init__ method.

Note 2: For your PCA outputs to match the local tests and autograder, make sure you set the seed using a random state of 0 when you initialize the PCA function.

Note 3: Since PCA does not work with NA values, make sure you drop any columns that have NA values before running PCA.

Useful Resources

<ul>
<li><u>https:</u>//<u>com</u>/<u>data-science</u>/<u>step-step-explanation-principal-component-anal</u>y<u>sis</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.decomposition.PCA.html#sklearn.decomposition.P</u></li>
</ul>
<u>CA</u>

<ul>
<li><u>https:</u>//<u>stackexchan</u>g<u>e.com/questions</u>/<u>103211</u>/<u>do-we-need-to-pre-process-boththe-test-and-train-data-set</u></li>
</ul>
INPUTS

<ul>
<li>Use the needed instance variables you set in the __init__ method</li>
<li>train_features – a dataset split by a function similar to tts which should be used in the training/fitting steps</li>
<li>test_features – a dataset split by a function similar to tts which should be used in the test steps</li>
</ul>
OUTPUTS

a pandas DataFrame with the generated pca values and using column names: component_1, component_2 .. component_n

Function Skeleton

def pca_train(self,train_features:pd.DataFrame) -&gt; pd.DataFrame:

<em># TODO: Read the function description in https://github.gatech.edu/pages/cs6035-tools/cs6035-to </em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pca_dataset = pd.DataFrame() &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return pca_dataset

def pca_test(self,test_features:pd.DataFrame) -&gt; pd.DataFrame:

<em># TODO: Read the function description in https://github.gatech.edu/pages/cs6035-tools/cs6035-to </em>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pca_dataset = pd.DataFrame() &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return pca_dataset

PreprocessDataset:feature_engineering_train, feature_engineering_test

Feature Engineering is a process of using domain knowledge (physics, geometry, sports statistics, business metrics, etc.) to create new features (columns) out of the existing data. This could mean creating an area feature when given the length and width of a triangle or extracting the major and minor version number from a software version or more complex logic depending on the scenario.

For this method, you will be taking in a dictionary with a column name and a function that takes in a DataFrame and returns a column. You’ll be using that to create a new column with the name in the dictionary key.

For example:

<table width="679">
<tbody>
<tr>
<td width="679">def double_height(dataframe:pd.DataFrame):

return dataframe[“height”] * 2 def half_height(dataframe:pd.DataFrame):

return dataframe[“height”] / 2

feature_engineering_functions = {“double_height”:double_height,”half_height”:half_height}
</td>
</tr>
</tbody>
</table>
Given the above functions, you would create two new columns named “double_height” and “half_height” in your Dataframe.

Useful Resources

<ul>
<li><u>https:</u>//<u>wikipedia.or</u>g/<u>wiki</u>/<u>Feature_en</u>g<u>ineering</u></li>
<li><u>https:</u>//<u></u>g<u>eeksfor</u>g<u>eeks.or</u>g/<u>what-is-feature-en</u>g<u>ineerin</u>g/</li>
</ul>
INPUTS

<ul>
<li>Use the needed instance variables you set in the __init__ method</li>
<li>train_features – a dataset split by a function similar to tts which should be used in the training/fitting steps</li>
<li>test_features – a dataset split by a function similar to tts which should be used in the test steps</li>
</ul>
OUTPUTS

a pandas dataframe with the features described in feature_engineering_train and

feature_engineering_test added as new columns and all other columns in the dataframe unchanged

Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">def feature_engineering_train(self,train_features:pd.DataFrame) -&gt; pd.DataFrame:

feature_engineered_dataset = pd.DataFrame() &nbsp;&nbsp;&nbsp;&nbsp;return feature_engineered_dataset def feature_engineering_test(self,test_features:pd.DataFrame) -&gt; pd.DataFrame:

feature_engineered_dataset = pd.DataFrame() &nbsp;&nbsp;&nbsp;&nbsp;return feature_engineered_dataset
</td>
</tr>
</tbody>
</table>
PreprocessDataset:preprocess_train, preprocess_test

Now, we will put three of the above methods together into a preprocess function. This function will take in a dataset and perform encoding, scaling, and feature engineering using the above methods and their respective columns. You should not perform PCA for this function.

Useful Resources

See resources for one hot encoding, min/max scaling and feature engineering above

INPUTS

<ul>
<li>Use the needed instance variables you set in the __init__ method</li>
<li>train_features – a dataset split by a function similar to tts which should be used in the training/fitting steps</li>
<li>test_features – a dataset split by a function similar to tts which should be used in the test steps</li>
</ul>
OUTPUTS

a pandas dataframe for both test and train features with the columns in one_hot_encode_cols encoded, the columns in min_max_scale_cols scaled and the columns described in

feature_engineering_functions engineered. You do not need to use PCA here.

Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">def preprocess_train(self,train_features:pd.DataFrame) -&gt; pd.DataFrame:

train_features = pd.DataFrame() &nbsp;&nbsp;return train_features

def preprocess_test(self,test_features:pd.DataFrame) -&gt; pd.DataFrame:

test_features = pd.DataFrame() &nbsp;&nbsp;return test_features
</td>
</tr>
</tbody>
</table>
Disclaimer: You are responsible for the information on this website. The content is subject to change at any time.

CS 6035

<u>Projects </u>/ <u>Machine Learning </u>/ Task 3

<h1>Task 3 (15 points)</h1>
In Task 2 you learned how to split a dataset into training and testing components. Now it’s time to learn about using a K-means model. We will run a basic model on the data to cluster files (rows) with similar attributes together. We will use an unsupervised model.

Theory

An <u>unsupervised model</u> has no label column. By constrast, in <u>supervised learning</u> (which you’ll see in Task 4) the data has features and targets/labels. These labels are effectively an answer key to the data in the feature columns. You don’t have this answer key in unsupervised learning, instead you’re working on data without labels. You’ll need to choose algorithms that can learn from the data, exclusively, without the benefit of lablels.

We start with <u>K-means</u> because it is simple to understand the algorithm. For the Mathematics people, you can look at the underlying data structure, <u>a Voronoi dia</u>g<u>ram</u>. Based on squared <u>Euclidian distances</u>, K-means creates clusters of similar datapoints. Each cluster has a centroid.

The idea is that for each sample, it’s associated/clustered with the centroid that is the “closest.”

Closest is an interesting concept in higher dimensions. You can think of each feature in a dataset as a dimension in the data. If it’s 2d or 3d, we can visualize it easily. Concepts of distance are clear in 2d and 3d, and they work similarly in 4+d.

If you read the Wikipedia articles for K-means you’ll see a discussion of the use of “squared Euclidean distances” in K-means. This is compared with simple Euclidean distances in the Weber problem, and better approaches resulting from k-medians and k-mediods is discussed.

Please use scikit-learn to create the model and Yellowbrick to determine the optimal value of k for the dataset.

So far, we have functions to split the data and preprocess it. Now, we will run a basic model on the data to cluster files (rows) with similar attributes together. We will use an unsupervised model (model with no label column), K-means. Again, use scikit-learn to create the model and Yellowbrick to determine the optimal value of k for the dataset.

Refer to the <u>Submissions</u> page for details about submitting your work.

Useful Links:

<ul>
<li><u>Clusterin</u>g<u> – Goo</u>g<u>le Developers</u></li>
<li><u>Clusterin</u>g<u> Al</u>g<u>orithms – Goo</u>g<u>le Developers</u></li>
<li><u>Kmeans – Goo</u>g<u>le Developers</u></li>
</ul>
Deliverables:

<ul>
<li>Complete the KmeansClustering class in task3.py.</li>
<li>For this task we have released a local test suite please set that up and use it to debug your function.</li>
<li>Submit task3.py to Gradescope when you pass all local tests. Refer to the <u>Submissions</u> page for details.</li>
</ul>
Instructions:

The Task3.py File has function skeletons that you will complete with Python code. You will mostly be using the pandas, Yellowbrick and scikit-learn libraries. The goal of each of these functions is to give you familiarity with the applied concepts of Unsupervised Learning. See information about the function’s Inputs, Outputs and Skeletons below.

<h2>KmeansClustering</h2>
The KmeansClustering Class contains a code skeleton with 4 methods for you to implement.

Note: You should train/fit using the train dataset then once you have a Yellowbrick/K-means model instance you can transform/predict on the training and test data.

<h2>KmeansClustering:__init__</h2>
Similar to Task 1, you will initialize the class by adding instance variables as needed.

Useful Resources

<ul>
<li><u>https:</u>//<u>w3schools.com/p</u>y<u>thon/p</u>y<u>thon_classes.asp</u></li>
</ul>
INPUTS

<ul>
<li>random_state – an integer that should be used to set the scikit-learn randomness so the model results will be repeatable which is required for the tests and autograder</li>
</ul>
OUTPUTS None

Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">def __init__(self,

random_state: int &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;):

<em># TODO: Add any state variables you may need to make your functions work </em>&nbsp;&nbsp;pass
</td>
</tr>
</tbody>
</table>
<h2>KmeansClustering:kmeans_train</h2>
Kmeans Clustering is a process of grouping together similar rows together and assigning them to a cluster. For this method you will use the training data to fit an optimal K-means cluster on the data.

To help you get started we have provided a list of subtasks to complete for this task:

<ul>
<li>Initialize a scikit-learn K-means model using random_state from the __init__ method and setting n_init = 10.</li>
<li>Initialize a yellowbrick KElbowVisualizer with the K-means model to search for the optimal value of k (between 1 and 10, exclusive).</li>
<li>Train the KElbowVisualizer on the training data and determine the optimal k value. 4 Now, train a K-means model with the proper initialization for that optimal value of k 5 Return the cluster ids for each row of the training set as a list.</li>
</ul>
Useful Resources

<ul>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.cluster.KMeans.html#sklearn.cluster.KMeans</u></li>
<li><u>https:</u>//<u>scikit-</u>y<u>b.or</u>g/<u>en</u>/<u>latest/api</u>/<u>cluster</u>/<u>elbow.html</u></li>
</ul>
INPUTS

<ul>
<li>Use the needed instance variables you set in the __init__ method</li>
<li>train_features – a dataset split by a function similar to tts which should be used in the training/fitting steps</li>
</ul>
OUTPUTS

a list of cluster ids that the K-means model has assigned for each row in the train dataset Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">def kmeans_train(self,train_features:pd.DataFrame) -&gt; list:

cluster_ids = list() &nbsp;&nbsp;&nbsp;&nbsp;return cluster_ids
</td>
</tr>
</tbody>
</table>
<h2>KmeansClustering:kmeans_test</h2>
K-means clustering is a process of grouping together similar rows together and assigning them to a cluster. For this method you will use the training data to fit an optimal K-means cluster on the test data.

To help you get started, we have provided a list of subtasks to complete for this task:

<ul>
<li>Use a model similar to the one you trained in the kmeans_train method to generate cluster ids for each row of the test dataset. You should either (1) reuse the same model from kmeans_train or (2) train a new model in the test method using the training data.</li>
<li>Return the cluster ids for each row of the test set as a list.</li>
</ul>
Useful Resources

<ul>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.cluster.KMeans.html#sklearn.cluster.KMeans </u>• <u>https:</u>//<u>www.scikit-</u>y<u>b.or</u>g/<u>en</u>/<u>latest/api</u>/<u>cluster</u>/<u>elbow.html</u></li>
</ul>
INPUTS

<ul>
<li>Use the needed instance variables you set in the __init__ method</li>
<li>test_features – a dataset split by a function similar to tts which should be used in the test steps</li>
</ul>
OUTPUTS

a list of cluster ids that the K-means model has assigned for each row in the test dataset

Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">def kmeans_test(self,test_features:pd.DataFrame) -&gt; list:

cluster_ids = list() &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return cluster_ids
</td>
</tr>
</tbody>
</table>
KmeansClustering:train_add_kmeans_cluster_id_feature, test_add_kmeans_cluster_id_feature

Using the two methods you completed above (kmeans_train and kmeans_test) you will add a new feature(column) to the training and test dataframes. This is similar to the feature engineering method in Task 2 where you appended new columns onto an existing dataframe.

To do this, use the output of the methods (the list of cluster ids you return) from the corresponding train or test method and add it as a new column named kmeans_cluster_id in the input dataframe, then return the full dataframe.

Useful Resources

INPUTS

Use the needed instance variables you set in the __init__ method and the kmeans_train and kmeans_test methods you wrote above to produce the needed output.

<ul>
<li>train_features – a dataset split by a function similar to tts which should be used in the training/fitting steps</li>
<li>test_features – a dataset split by a function similar to tts which should be used in the test steps</li>
</ul>
OUTPUTS

A pandas dataframe with the kmeans_cluster_id added as a feature and all other input columns unchanged, for each of the two methods train_add_kmeans_cluster_id_feature and

test_add_kmeans_cluster_id_feature.

Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">&nbsp;&nbsp;&nbsp; def train_add_kmeans_cluster_id_feature(self,train_features:pd.DataFrame) -&gt; pd.DataFrame:

output_df = pd.DataFrame() &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return output_df

def test_add_kmeans_cluster_id_feature(self,test_features:pd.DataFrame) -&gt; pd.DataFrame:
</td>
</tr>
</tbody>
</table>
output_df = pd.DataFrame() &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;return output_df

Disclaimer: You are responsible for the information on this website. The content is subject to change at any time.

CS 6035

<u>Projects </u>/ <u>Machine Learning </u>/ Task 4

Task 4 (25 points)

Now let’s try a few supervised classification models:

<ul>
<li>A naive model you’ll build yourself</li>
<li>Logistic Regression</li>
<li>Random Forest</li>
<li>Gradient Boosting</li>
</ul>
We have chosen a few commonly used models for you to use here, but there are many options. In the real world, specific algorithms may fit a specific dataset better than other algorithms.

You won’t be doing any hyperparameter tuning yet, so you can better focus on writing the basic code. You will:

<ul>
<li>Train a model using the training set.</li>
<li>Predict on the training/test sets.</li>
<li>Calculate performance metrics.</li>
<li>Return a ModelMetrics object and trained scikit-learn model from each model function.</li>
</ul>
(Note on feature importance: You should use RFE for determining feature importance of your Logistic Regression model, but do NOT use RFE for your Random Forest or Gradient Boosting models to determine feature importance. Please use their built-in values for this.)

Useful Links:

<ul>
<li><u>scikit-learn: machine learnin</u>g<u> in P</u>y<u>thon — scikit-learn 1.2.1 documentation</u></li>
<li><u>Trainin</u>g<u> and Test Sets – Machine Learnin</u>g<u> – Goo</u>g<u>le Developers</u></li>
<li><u>Bias–variance tradeoff – Wikipedia</u></li>
<li><u>Overfittin</u>g<u> – Wikipedia</u></li>
</ul>
<u>An Introduction to Classification in Machine Learnin</u>g<u> – builtin </u>•&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <u>Classification in Machine Learnin</u>g<u>: An Introduction – DataCamp</u>

Deliverables:

<ul>
<li>Complete the functions and methods in task4.py</li>
<li>For this task we have released a local test suite please set that up and use it to debug your function.</li>
<li>Submit task4.py to Gradescope when you pass all local tests. Refer to the <u>Submissions</u> page for details.</li>
</ul>
Instructions:

The Task4.py File has function skeletons that you will complete with Python code (mostly using the pandas and scikit-learn libraries).

The goal of each of these functions is to give you familiarity with the applied concepts of training a model, using it to score records and calculating performance metrics for it. See information about the function inputs, outputs and skeletons below.

Table of contents

<ul>
<li><u>ModelMetrics</u></li>
<li><u>calculate_naive_metrics</u></li>
<li><u>calculate_lo</u>g<u>istic_re</u>g<u>ression_metrics</u></li>
<li><u>calculate_random_forest_metrics</u></li>
<li><u>calculate_</u>g<u>radient_boostin</u>g<u>_metrics</u></li>
</ul>
ModelMetrics

<ul>
<li>In order to simplify the autograding we have created a class that will hold the metrics and feature importances for a model you trained.</li>
<li>You should not modify this class but are expected to use it in your return statements.</li>
<li>This means you put your training and test metrics dictionaries and feature importance DataFrames inside a ModelMetrics object for the autograder to handle. This is for each of the Logistic Regression, Gradient Boosting and Random Forest models you will create.</li>
</ul>
You do not need to return a feature importance DataFrame in the ModelMetrics value for the naive model you will create, just return None in that position of the return statement, as the given code does.

calculate_naive_metrics

A Naive model is a very simple model/prediction that can help to frame how well a more sophisticated model is doing. At best, such a model has random competence at predicting things. At worst, it’s wrong all the time.

Since a naive model is incredibly basic (often a constant or randomly selected result), we can expect that any more sophisticated model that we train should outperform it. If the naive Model beats our trained model, it can mean that additional data (rows or columns) is needed in the dataset to improve our model. It can also mean that the dataset doesn’t have a strong enough signal for the target we want to predict.

In this function you will use the approach of a single / constant output naive model. You will use a given constant integer (as a parameter) as your naive prediction. You will then calculate 4 metrics (accuracy,recall,precision and fscore) for the training and test datasets. The integer is passed into the function as the variable naive_assumption. As noted above here you do not return a feature importance object, just return None in that place of the ModelMetrics object you return.

Useful Resources

<ul>
<li><u>https:</u>//<u>machinelearnin</u>g<u>master</u>y<u>.com</u>/<u>how-to-develop-and-evaluate-naive-classifier-strate</u>g<u>iesusin</u>g<u>-probability/</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.accurac</u>y<u>_score.html#sklearn.metrics.accu rac</u>y<u>_score</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.recall_score.html#sklearn.metrics.recall_s core</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.precision_score.html#sklearn.metrics.preci sion_score</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.f1_score.html#sklearn.metrics.f1_score</u></li>
</ul>
INPUTS

train_features – a dataset split by a function similar to the tts function you created in task2

<ul>
<li>test_features – a dataset split by a function similar to the tts function you created in task2</li>
<li>train_targets – a dataset split by a function similar to the tts function you created in task2</li>
<li>test_targets – a dataset split by a function similar to the tts function you created in task2</li>
<li>naive_assumption – an integer that should be used as the result from the naive model you will create</li>
</ul>
OUTPUTS

A completed ModelMetrics object with a training and test metrics dictionary with each one of the metrics rounded to 4 decimal places

Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">def calculate_naive_metrics(train_features:pd.DataFrame, test_features:pd.DataFrame, train_targets:

train_metrics = { &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“accuracy” : 0,

“recall” : 0,

“precision” : 0, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“fscore” : 0

}

test_metrics = { &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“accuracy” : 0,

“recall” : 0,

“precision” : 0, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“fscore” : 0

}

naive_metrics = ModelMetrics(“Naive”,train_metrics,test_metrics,None) &nbsp;&nbsp;&nbsp;&nbsp;return naive_metrics
</td>
</tr>
</tbody>
</table>
p

calculate_logistic_regression_metrics

A logistic regression model is a simple and more explainable statistical model that can be used to estimate the probability of an event (<u>lo</u>g<u>-odds</u>). At a high level, a logistic regression model uses data in the training set to estimate a column’s weight in a linear approximation function.

Conceptually this is similar to estimating m for each column in the line formula you probably know well from geometry: y = m*x + b. If you are interested in learning more, y<u>ou can read up on the math</u> behind how this works. For this project, we are more focused on showing you how to apply

&nbsp;

these models, so you can simply use a scikit-learn Logistic Regression model in your code.

For this task use scikit-learn’s LogisticRegression class and complete the following subtasks:

<ul>
<li>Train a Logistic Regression model (initialized using the kwargs passed into the function)</li>
<li>Predict scores for training and test datasets and calculate the 7 metrics listed below for the training and test datasets using predictions from the fit model. (All rounded to 4 decimal places)</li>
<li>Use RFE to select the top 10 features</li>
<li>Train a Logistic Regression model using these selected features (initialized using the kwargs passed into the function)</li>
<li>Create a Feature Importance DataFrame from the model trained on the top 10 features:</li>
<li>Use the top 10 features sort by absolute value of the coefficient from biggest to smallest.</li>
<li>Make sure you use the same feature and importance column names as set in ModelMetrics in feat_name_col [Feature] and imp_col [Importance].</li>
<li>Round the importances to 4 decimal places (do this step after you have sorted by Importance)</li>
<li>Reset the index to 0-9. You can do this the same way you did in task1.</li>
</ul>
NOTE: Make sure you use the predicted probabilities for roc auc

Useful Resources

<ul>
<li><u>https:</u>//<u>libretexts.or</u>g/<u>Bookshelves</u>/<u>Introductor</u>y<u>_Statistics</u>/<u>OpenIntro_Statistics_</u>(<u>Diez_et_a</u></li>
</ul>
<u>l).</u>/<u>08%3A_Multiple_and_Lo</u>g<u>istic_Re</u>g<u>ression</u>/<u>8.04%3A_Introduction_to_Lo</u>g<u>istic_Re</u>g<u>ression</u>

<ul>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.linear_model.Lo</u>g<u>isticRe</u>g<u>ression.html#sklearn.linea r_model.Lo</u>g<u>isticRe</u>g<u>ression</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.accurac</u>y<u>_score.html#sklearn.metrics.accu rac</u>y<u>_score</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.recall_score.html#sklearn.metrics.recall_s core</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.precision_score.html#sklearn.metrics.preci sion_score</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.f1_score.html#sklearn.metrics.f1_score</u></li>
<li><u>https:</u>//<u>wikipedia.or</u>g/<u>wiki</u>/<u>Confusion_matrix</u></li>
<li><u>https:</u>//<u>scikit-learn.or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>metrics.roc_auc_score.html</u></li>
</ul>
INPUTS

The first 4 are similar to the tts function you created in Task 2:

<ul>
<li>train_features – a Pandas Dataframe with training features</li>
<li>test_features – a Pandas Dataframe with test features</li>
<li>train_targets – a Pandas Dataframe with training targets</li>
<li>test_targets – a Pandas Dataframe with test targets</li>
<li>logreg_kwargs – a dictionary with keyword arguments that can be passed directly to the scikitlearn Logistic Regression class</li>
</ul>
OUTPUTS

<ul>
<li>A completed ModelMetrics object with a training and test metrics dictionary with each one of the metrics rounded to 4 decimal places</li>
<li>A scikit-learn Logistic Regression model object fit on the training set</li>
</ul>
Function Skeleton

def calculate_logistic_regression_metrics(train_features:pd.DataFrame, test_features:pd.DataFrame, t &nbsp;&nbsp;&nbsp;&nbsp;model = LogisticRegression() &nbsp;&nbsp;&nbsp;&nbsp;train_metrics = { &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“accuracy” : 0,

“recall” : 0,

“precision” : 0,

A Random Forest model is a more complex model than the naive and Logistic Regression Models you have trained so far. It can still be used to estimate the probability of an event, but achieves this using a different underlying structure: <u>a tree-based model</u>.

Conceptually, this looks a lot like many if/else statements chained together into a “tree”. A Random Forest expands on this and trains different trees with different subsets of the data and starting conditions. It does this to get a better estimate than a single tree would give. For this project, we are more focused on showing you how to apply these models, so you can simply use the scikitlearn Random Forest model in your code.

For this task use scikit-learn’s Random Forest Classifier class and complete the following subtasks:

<ul>
<li>Train a Random Forest model (initialized using the kwargs passed into the function)</li>
<li>Predict scores for training and test datasets and calculate the 7 metrics listed below for the training and test datasets using predictions from the fit model. (All rounded to 4 decimal</li>
<li>Area Under the Curve of Receiver Operating Characteristics Curve (roc_auc)</li>
<li>Create a Feature Importance DataFrame from the trained model:</li>
<li>Do Not Use RFE for feature selection</li>
<li>Use the top 10 features selected by the built in method (sorted from biggest to smallest)</li>
<li>Make sure you use the same feature and importance column names as ModelMetrics shows in feat_name_col [Feature] and imp_col [Importance]</li>
<li>Round the importances to 4 decimal places (do this step after you have sorted by Importance)</li>
<li>Reset the index to 0-9 you can do this the same way you did in task1</li>
</ul>
NOTE: Make sure you use the predicted probabilities for roc auc

Useful Resources

<ul>
<li><u>https:</u>//<u>blo</u>g<u>.dataiku.com</u>/<u>tree-based-models-how-the</u>y<u>-work-in-plain-en</u>g<u>lish</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.ensemble.RandomForestClassifier.html</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.accurac</u>y<u>_score.html#sklearn.metrics.accu rac</u>y<u>_score</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.recall_score.html#sklearn.metrics.recall_s core</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.precision_score.html#sklearn.metrics.preci sion_score</u></li>
<li></li>
</ul>
<table>
<tbody>
<tr>
<td width="68"></td>
</tr>
<tr>
<td></td>
<td></td>
</tr>
</tbody>
</table>
<ul>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.f1_score.html#sklearn.metrics.f1_score</u></li>
<li><u>https:</u>//<u>wikipedia.or</u>g/<u>wiki</u>/<u>Confusion_matrix</u></li>
<li><u>https:</u>//<u>scikit-learn.or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>metrics.roc_auc_score.html</u></li>
</ul>
INPUTS

<ul>
<li>train_features – a dataset split by a function similar to the tts function you created in task2</li>
<li>test_features – a dataset split by a function similar to the tts function you created in task2</li>
<li>train_targets – a dataset split by a function similar to the tts function you created in task2</li>
<li>test_targets – a dataset split by a function similar to the tts function you created in task2</li>
<li>rf_kwargs – a dictionary with keyword arguments that can be passed directly to the scikit-learn RandomForestClassifier class</li>
</ul>
OUTPUTS

<ul>
<li>A completed ModelMetrics object with a training and test metrics dictionary with each one of the metrics rounded to 4 decimal places</li>
<li>An scikit-learn Random Forest model object fit on the training set</li>
</ul>
Function Skeleton

A Gradient Boosted model is more complex than the Naive and Logistic Regression models and similar in structure to the Random Forest model you just trained. A Gradient Boosted model expands on the tree-based model by using its additional trees to predict the errors from the previous tree. For this project, we are more focused on showing you how to apply these models, so you can simply use the scikit-learn Gradient Boosted Model in your code.

For this task use scikit-learn’s Gradient Boosting Classifier class and complete the following subtasks:

<ul>
<li>Train a Gradient Boosted model (initialized using the kwargs passed into the function)</li>
<li>Predict scores for training and test datasets and calculate the 7 metrics listed below for the training and test datasets using predictions from the fit model. (All rounded to 4 decimal</li>
<li>Area Under the Curve of Receiver Operating Characteristics Curve (roc_auc)</li>
<li>Create a Feature Importance DataFrame from the trained model:</li>
<li>Do Not Use RFE for feature selection</li>
<li>Use the top 10 features selected by the built in method (sorted from biggest to smallest)</li>
<li>Make sure you use the same feature and importance column names as ModelMetrics shows in feat_name_col [Feature] and imp_col [Importance]</li>
<li>round the importances to 4 decimal places (do this step after you have sorted by Importance)</li>
<li>Reset the index to 0-9 you can do this the same way you did in task1</li>
</ul>
NOTE: Make sure you use the predicted probabilities for roc auc

Refer to the <u>Submissions</u> page for details about submitting your work.

Useful Resources

<ul>
<li><u>https:</u>//<u>blo</u>g<u>.dataiku.com</u>/<u>tree-based-models-how-the</u>y<u>-work-in-plain-en</u>g<u>lish</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.ensemble.GradientBoostin</u>g<u>Classifier.html</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.accurac</u>y<u>_score.html#sklearn.metrics.accu rac</u>y<u>_score</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.recall_score.html#sklearn.metrics.recall_s core</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.precision_score.html#sklearn.metrics.preci sion_score</u></li>
<li><u>https:</u>//<u>or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>sklearn.metrics.f1_score.html#sklearn.metrics.f1_score</u></li>
<li><u>https:</u>//<u>wikipedia.or</u>g/<u>wiki</u>/<u>Confusion_matrix</u></li>
<li><u>https:</u>//<u>scikit-learn.or</u>g/<u>stable</u>/<u>modules/</u>g<u>enerated</u>/<u>metrics.roc_auc_score.html</u></li>
</ul>
INPUTS

<ul>
<li>train_features – a dataset split by a function similar to the tts function you created in task2</li>
<li>test_features – a dataset split by a function similar to the tts function you created in task2</li>
<li>train_targets – a dataset split by a function similar to the tts function you created in task2</li>
<li>test_targets – a dataset split by a function similar to the tts function you created in task2</li>
<li>gb_kwargs – a dictionary with keyword arguments that can be passed directly to the scikit-learn GradientBoostingClassifier class</li>
</ul>
OUTPUTS

<ul>
<li>A completed ModelMetrics object with a training and test metrics dictionary with each one of the metrics rounded to 4 decimal places</li>
<li>An scikit-learn Gradient Boosted model object fit on the training set</li>
</ul>
Function Skeleton

<table width="679">
<tbody>
<tr>
<td width="679">def calculate_gradient_boosting_metrics(train_features:pd.DataFrame, test_features:pd.DataFrame,&nbsp;&nbsp;&nbsp;&nbsp; model = GradientBoostingClassifier() &nbsp;&nbsp;&nbsp;&nbsp;train_metrics = { &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“accuracy” : 0,

“recall” : 0,

“precision” : 0,

“fscore” : 0,

“fpr” : 0,

“fnr” : 0, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“roc_auc” : 0

}

test_metrics = { &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“accuracy” : 0,

“recall” : 0,

“precision” : 0,

“fscore” : 0,

“fpr” : 0,

“fnr” : 0, &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;“roc_auc” : 0

}

gb_importance = pd.DataFrame()

gb_metrics = ModelMetrics(“Gradient Boosting”,train_metrics,test_metrics,gb_importance)

return gb_metrics,model
</td>
</tr>
</tbody>
</table>
tra

Example of Feature Importance DataFrame

Disclaimer: You are responsible for the information on this website. The content is subject to change at any time.

CS 6035

<u>Projects </u>/ <u>Machine Learning </u>/ Task 5

<h1>Task 5 (20 points)</h1>
Now that you have written functions for different steps of the model-building process, you will put it all together. You will write code that trains a model with hyperparameters you determine (you should do any tuning locally or in a notebook, i.e., don’t tune your model in gradescope since the autograder will likely timeout).

Refer to the <u>Submissions</u> page for details about submitting your work.

For Task 5 you should write your own local tests to pass before submitting to Gradescope. Do not share these tests with other students.

train_model_return_scores

Instructions (10 points):

Your function will:

<ul>
<li>Take in the CLAMP training and test data csv filepaths (Note: the “class” column is the target for this dataset).</li>
<li>Train a model</li>
<li>Predict on a test set (“class” column will be removed to simulate new files that will be classified by your model)</li>
<li>Output values from 0 to 1 (values close to 0 being less likely to be malicious and closer to 1 being more likely to be malicious) for each row</li>
</ul>
Our autograder will compare your predictions with the correct answers, and to get credit, you will need a roc auc score of .9 or higher on the test set (should not require much hyperparameter tuning for this dataset). This is basically a simulation of how your model would perform in a “production” system using batch inference.

<ul>
<li>Use any of the techniques we covered in this project to train models and return predicted probabilities for each row of the test sets as a DataFrames with columns index (same as your index from the input test df) and malware_score (predicted probabilities).</li>
</ul>
<h2>INPUTS</h2>
<ul>
<li>train_df_path – a filepath which contains the location of the CLAMP training data (same file you are given in the local testing task5 folder). This file will contain the class column for you to train your model.</li>
<li>test_df_path – a filepath which contains the location of the CLAMP test data (unseen data used to test the robustness of your model). This file will not contain the class</li>
</ul>
Sample Submission:

def train_model_return_scores(train_df_path,test_df_path) -&gt; pd.DataFrame:

<em># TODO: Read the function description in https://github.gatech.edu/pages/cs6035-tools/cs6035-too </em>&nbsp;&nbsp;&nbsp;&nbsp;test_scores = pd.DataFrame() &nbsp;&nbsp;&nbsp;&nbsp;return test_scores

train_model_unsw_return_scores

Instructions (10 points):

Your function will:

<ul>
<li>Take in the UNSW training and test data csv filepaths (Note: the “class” column is the target for this dataset).</li>
<li>Train a model</li>
<li>Predict on a test set (“class” column will be removed to simulate new files that will be classified by your model)</li>
<li>Output values from 0 to 1 (values close to 0 being less likely to be class=1 and closer to 1 being more likely to be class=1) for each row</li>
</ul>
Our autograder will compare your predictions with the correct answers, and to get credit, you will need a roc auc score of .55 or higher on the test set which will give 1/4 credit (2.5 points) and should not require much hyperparameter tuning for this dataset. We also add thresholds of .75 which will give half credit (5 points) and will likely require parameter tuning. The full credit (10 points) threshold is .76 which will give full credit and will likely require parameter tuning.

This is basically a simulation of how your model would perform on unseen data in a “production” system using batch inference.

Use any of the techniques we covered in this project to train models and return predicted probabilities for each row of the test sets as a DataFrames with columns index (same as your index from the input test df) and prob_class_1 (predicted probabilities).

<h2>INPUTS</h2>
<ul>
<li>train_df_path – a filepath which contains the location of the UNSW training data (same file you are given in the local testing task5 folder). This file will contain the class column for you to train your model.</li>
<li>test_df_path – a filepath which contains the location of the UNSW test data (unseen data used to test the robustness of your model). This file will not contain the class Function Skeleton</li>
</ul>
Sample Submission:

Deliverables:

<ul>
<li>We encourage you to write your own tests for this task with the provided data.</li>
<li>Do not share these tests.</li>
<li>Once you are satisfied with your local results, you can submit task5.py to Gradescope. Refer to the <u>Submissions</u> page for details.</li>
</ul>
More Information

<ul>
<li>The ClaMP (Classification of Malware with PE Headers) dataset is a malware classifier dataset built with header fields’ values of Portable Executable files. You can learn more about Portable Executable files at <u>Microsoft – PE Format</u> or <u></u></li>
</ul>
Visit the <u>public GitHub respositoy</u> for more general information. For this project, we use the 55 feature ClaMP_Raw-5184.csv file referenced in the Dataset Files section of the repository.

There are also papers that have been written using the dataset, such as <u>Investi</u>g<u>ation and preprocessin</u>g<u> of CLaMP malware dataset for machine learnin</u>g<u> models</u>.

<ul>
<li>The UNSW-NB15 dataset was created by the IXIA PerfectStorm tool in the Cyber Range Lab of UNSW Canberra for generating a hybrid of real modern normal activities and synthetic contemporary attack behaviors.</li>
</ul>
You can visit the project’s <u>website</u> for more general information. Of particular use may be the <u>dataset description</u> and <u>feature descriptions</u> provided by the creators at UNSW Canbrerra. Please note, we do not use all features or classes in the project.

Disclaimer: You are responsible for the information on this website. The content is subject to change at any time.
