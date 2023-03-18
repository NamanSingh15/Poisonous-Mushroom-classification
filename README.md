# Poisonous-Mushroom-classification


This repository contains code to explore and visualize a mushroom dataset. The secondary_data.csv file was used to perform data analysis and create visualizations.

Table of Contents
Installation
Usage
Dataset
Visualizations
Installation
To run this code, you need Python 3 installed on your system. You can download and install the latest version of Python from the official website here. Additionally, the following packages need to be installed to run the code:

numpy
pandas
matplotlib
seaborn
You can install these packages using pip. Run the following command in your command prompt or terminal:

Copy code
pip install numpy pandas matplotlib seaborn
Usage
After installing the necessary dependencies, you can clone this repository to your local machine using Git. Run the following command in your command prompt or terminal:

bash
Copy code
git clone https://github.com/<username>/<repository>.git
Change the current directory to the cloned repository:

bash
Copy code
cd <repository>
Run the Python script:

Copy code
python mushroom_analysis.py
Dataset
The mushroom dataset used in this project contains information about mushrooms such as cap diameter, cap shape, cap surface, cap color, etc. The dataset is stored in the secondary_data.csv file. This dataset is used to perform data analysis and create visualizations.

The dataset has the following columns:

class
cap-diameter
cap-shape
cap-surface
cap-color
does-bruise-or-bleed
gill-attachment
gill-spacing
gill-color
stem-height
stem-width
stem-root
stem-surface
stem-color
veil-type
veil-color
has-ring
ring-type
spore-print-color
habitat
season
Visualizations
The Python script creates a pairplot to visualize the relationship between different columns in the dataset. The pairplot is created using seaborn. The pairplot shows the distribution of each variable and the relationship between each pair of variables. The hue parameter is set to the 'class' column to differentiate between edible and poisonous mushrooms.
