# A-B-Test-Case-Study

**Requirements**
The following packages are needed to run the notebook code :

Python 3.7+

NumPy (pip install numpy)

Pandas (pip install pandas)

SciPy (pip install scipy)

If you are using anaconda virtual environment, you can install the above packages by running conda install package-name.

**List of files**
AB-Test-Case-Study.ipynb : This is a jupyter notebook. **It contains python code for a hypothetical A/B test which is one type of a statistical experiment.**

homepage-experiment-data.csv : This file contains all the data collected during the experiment for both the control and experiment groups participating in it.

**Description of the problem**
A software company is trying to raise the revenue of one of their software products which they sell online. A visitor when on the company website can nevigate to the software page to download it on their machine. The product currently comes with a free one week trial period starting from the day of download. After one week, users are required to purchase the license for the software to continue using it without any disruption. The current aim of the company is to entice more and more visitors to use the software during the available free trial period and then eventually buy it.

With this in mind, they have decided to make some changes in the layout of the site homepage emphasizing more on the available one week free trial period. The hope is that this will encourage more people to download and use the software. But before deploying any such change, the company has decided to conduct an experiment to understand whether these changes will bring any statistically significant increment in the presently observed rates of the download as well as puchase of the software.

**A look into the code**
The entire analysis is divided into five main parts :
* Constructing a user funnel
* Deciding on metrics
* Computing the size of the experiment
* Analysis of the data
* Conclusion

The notebook contains detailed discussion on each of the above component of the analysis. Statistical calculations and data analysis have been performed to understand the information collected from the experiment and finally to reach a conclusion.
