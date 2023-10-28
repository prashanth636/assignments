##README##
#TITLE
	ML Assignment 1
#OVERVIEW
The project has two part.
	Part 1: Linear regression over Winequalilty-red dataset.
	Part 2: Logistic regression over Penguins dataset.

#PREREQUISITES
	Requires python 3, Jupyter notebook.
	imports seaborn, matplotlib, numpy and pandas.

Launch Jupyter Notebook by typing jupyter notebook in the command prompt (Windows) or terminal (Mac/Linux).
Navigate to the directory where the Penguins and WineQuality ipynb files are located.

#FILE-STRUCTURE
	The directory contains:
		penguins.ipynb
		penguins.csv
		WineQuality.ipynb
		winequality-red.csv
		titanic.ipynb
		titanic.csv

#USAGE
	Click on the ipynb file to open it in Jupyter Notebook.
	run each cell or all cells to see and visualize the outputs.
	
#MODEL-ARCHITECTURE
	Part-1: Linear Regression
		The linear regression uses a closed form solution to find out the weights vector.
		Using the weights vector thus found, predict the results on the test data.
		compare the predicted values against actual values.
	Part-2: Logistic Regression
		The code uses a basic binary classification.
		The preprocessing of the data involves.
			1) Dealing with NA values.
			2) Normalizing the data.
		Selected Hyper-parameters.
		Apply cost function over sigmoid to make a prediction of the test data.
		Compare the predicted values against actual values.
		Plot the loss vs Epochs graph to find out how fast the gradient descends