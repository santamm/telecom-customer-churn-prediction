# Telecom Customer Churn Prediction

### Table of Contents

1. [Project Analysis](#motivation)
1. [Installation](#installation)
3. [Metric](#metric)
4. [File Descriptions](#files)
5. [Results](#results)
6. [Licensing, Authors, and Acknowledgements](#licensing)

## Project Analysis<a name="motivation"></a>
Customer attrition, also known as customer churn, customer turnover, or customer defection, is the loss of clients or customers.

Telephone service companies, ISPs, Pay TV companies, insurance firms, and alarm monitoring services, often use customer attrition analysis and customer attrition rates as one of their key business metrics  because the cost of retaining an existing customer is far less than acquiring a new one. Companies from these sectors often have customer service branches which attempt to win back defecting clients, because recovered long-term customers can be worth much more to a company than newly recruited clients.

Companies usually make a distinction between voluntary churn and involuntary churn. Voluntary churn occurs due to a decision by the customer to switch to another company or service provider, involuntary churn occurs due to circumstances such as a customer's relocation to a long-term care facility, death, or the relocation to a distant location. In most applications, involuntary reasons for churn are excluded from the analytical models. Analysts tend to concentrate on voluntary churn, because it typically occurs due to factors of the company-customer relationship which companies control, such as how billing interactions are handled or how after-sales help is provided.

Predictive analytics use churn prediction models that predict customer churn by assessing their propensity of risk to churn. Since these models generate a small prioritized list of potential defectors, they are effective at focusing customer retention marketing programs on the subset of the customer base who are most vulnerable to churn.

## Installation <a name="installation"></a>
The code in this project is written in Python 3.6.6 :: Anaconda custom (64-bit).
The following additional libraries have been used:
* pandas
* numpy
* matplotlib
* seaborn
* sklearn
* warnings
* time
* progressbar
* plot_learning_curve
* xgboost (see installation notes below)

In order to install XGBoost on Mac, please follow the steps below:
```
# This is from https://machinelearningmastery.com/install-xgboost-python-macos/
# except I didn't install gcc using MacPorts but brew. Also assumed python 3.6
# already installed


# Open a terminal and install latest gcc (gcc-8) in your home dir
brew install gcc

# Add the following lines to .bash-profile in the home directory
alias gcc='gcc-8'
alias cc='gcc-8'
alias g++='g++-8'
alias c++='c++-8'
export CC='gcc-8'
export CXX='g++-8'

# Install xgboost

git clone --recursive https://github.com/dmlc/xgboost

cd xgboost/

cp make/config.mk ./config.mk

make -j8

# Final install xgboost into python

cd python-package

sudo python setup.py install

# And that should be it! You can verify if everything works with this code
$ python
Python 3.6.6 |Anaconda custom (64-bit)| (default, Jun 28 2018, 11:07:29)
[GCC 4.2.1 Compatible Clang 4.0.1 (tags/RELEASE_401/final)] on darwin
Type "help", "copyright", "credits" or "license" for more information.
>>> import xgboost
>>> print("xgboost", xgboost.__version__)
xgboost 0.81
>>>
```



## Metric<a name="metric"></a>


## File Descriptions <a name="files"></a>
The Jupyter notebooks included in this project are:
- <>.ipynb

Python Files:
- <>.py  utility function to plot learning curves

Data files (under data directory):
- <>csv  dataframe of feature description




## Results<a name="results"></a>


## Licensing, Authors, Acknowledgements<a name="licensing"></a>
For licensing see LICENSE file.
