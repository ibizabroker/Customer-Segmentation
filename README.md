# Customer Segmentation
### Overview
Customer Segmentation is a popular application of unsupervised learning. Using
clustering, identify segments of customers to target the potential user base. They divide
customers into groups according to common characteristics like gender, age, interests,
and spending habits so they can market to each group effectively.
In this project we use K-means clustering and also visualize the gender and age distributions. Then
analyze their annual incomes and spending scores.

### Dataset
The customer dataset `Mall_Customers.csv` includes a total of 200 customers with the follwoing attributes of the customers:
- `CustomerID` : This is the identification number provided to each customer.
- `Gender` : The gender of the customer.
- `Age` : The age of the customer.
- `Annual Income` : The annual income in the form of thousand dollars.
- `Spending Score` : Spending score given to the customer on a scale of 1-100.

### Installation
This project uses Python 3.5 and the following python libraries:
- [matplotlib](https://matplotlib.org/)
- [pandas](https://pandas.pydata.org/)
- [numpy](https://numpy.org/)
- [random](https://docs.python.org/3/library/random.html)

You will need to have [Jupyter Notebook](https://jupyter.org/) installed to execute this program.

If you don't have the above mentioned packages installed you can use the following commands on the command window:
```
pip install matplotlib
pip install pandas
pip install numpy
pip install notebook
```
If you don't have Python installed yet, it is recommended that you install the [Anaconda]() distribution of Python which already has the above mentioned packages and more included in it. Make sure to select Python 3.x installer.

**Run commands**: 

Command window/Anaconda prompt:
```
jupyter notebook "Customer segmentation.ipynb"
```