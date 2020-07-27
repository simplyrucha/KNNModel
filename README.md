# Learning and Implementing KNN Algorithm
Predict a car's market price by applying KNN algorithm

This project is a learning instrument to understand the worflow of *K-Nearest Neighbors* algorithm for Calssification and Regression. KNN is a non-parametric method proposed by Thomas Cover, and is classified as supervised machine learning. More on KNN on [Wikipedia](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm#:~:text=k%20-NN%20is%20a%20type%20of%20instance-based%20learning%2C,and%20all%20computation%20is%20deferred%20until%20function%20evaluation).

The technical objective of the project is to predict a car's market price based on it's attributes(features) employing the KNN workflow. 

The dataset for this project was created and uploaded by Jeffrey C. Schlimmer at the UCI Machine Learning Repository. The dataset can be accessed from this [page](https://archive.ics.uci.edu/ml/machine-learning-databases/autos/imports-85.data) and detailed description is available [here](https://archive.ics.uci.edu/ml/datasets/automobile). 

The original dataset is also attached with this repository.

Since GitHub does not render the plotly plots, that I originally built this project with here is the NBViewer link to access the same. 

<a href="https://nbviewer.jupyter.org/github/simplyrucha/KNNModel/blob/master/GP_PredictingCarPrices.ipynb" target="_blank">Project with Plots</a>
<b><i>(Please use Ctrl+Left Click to open in new tab, or it will open in current tab itself!)</i></b>

<b>Data Dictionary:</b>

| Attribute	|Attribute Range|| Attribute |Attribute Range|
| --- | --- | --- | --- | --- |
| symboling	| -3, -2, -1, 0, 1, 2, 3|| normalized-losses	| continuous from 65 to 256|
| make	| alfa-romero, audi, bmw, chevrolet, dodge, honda, etc. (truncated)|| aspiration	| std, turbo|
| num-of-doors	| four, two|| body-style	| hardtop, wagon, sedan, hatchback, convertible|
| engine-location	| front, rear|| engine-type	| dohc, dohcv, l, ohc, ohcf, ohcv, rotor|
| drive-wheels	| 4wd, fwd, rwd|| wheel-base	| continuous from 86.6 120.9|
| length	| continuous from 141.1 to 208.1|| width	 | continuous from 60.3 to 72.3|
| height	| continuous from 47.8 to 59.8|| curb-weight	| continuous from 1488 to 4066|
| num-of-cylinders	| eight, five, four, six, three, twelve, two|| engine-size	| continuous from 61 to 326|
| fuel-type	| diesel, gas|| fuel-system	| 1bbl, 2bbl, 4bbl, idi, mfi, mpfi, spdi, spfi|
| bore	| continuous from 2.54 to 3.94|| stroke	| continuous from 2.07 to 4.17|
| horsepower	| continuous from 48 to 288|| peak-rpm	| continuous from 4150 to 6600|
| city-mpg	| continuous from 13 to 49|| highway-mpg	| continuous from 16 to 54|
| compression-ratio	| continuous from 7 to 23|| price	| continuous from 5118 to 45400|
