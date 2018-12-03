This Folder Contains scripts for the image analysis performed as part of the
2018 Physical Underpinnings of Biological Systems class at UCSF through the Intergrative
Program in Quantative Biology (IPQB)

The LAMMDAS team is Laurel Estes, Ajikarunia Palar, Maru Jamie, Matt Johnson and Snow Niang
Scripts were written by Ajikarunia Palar with input from Sy Redding

Scripts are meant to be run in a jupyter notebook. See installation instructions at http://jupyter.org/install

FILES IN THIS DIRECTORY

UNLESS OTHERWISE NOTED ALL SCRIPTS WERE WRITTEN IN PYTHON 3

CALCULATE_PUNCTANESS
	This Script calculates a quantfiable property from each image, "punctaness",
	which is a geometric sum of all pixel intensities considered puncta.
	It relies on the white top hat filtering algorithm. See scikit image morphological 
	filtering tutorials. 
	Writes an output file of the punctaness for each image stack.
	This data is saved as punctaness.txt

VISUALIZE_ALGORITHMS
	This script contains functions for parsing the data output data of calculate_punctaness
	It performs a ttest on each data set
	It has other functions for visualizing and testing calculate_punctaness

punctaness.txt
	The output data from CALCULATE_PUNCTANESS
	The input data for Visualize_Algorithm

visualize_algorithm.png
	This supplementary figure shows what the calculate punctaness algorithm is doing
	
fig_pval_microscopy.png
	The primary result of the image analysis, a box plot showing most significant difference between conditions

nd2as8bit/
	Holds 8-bit jpegs for generating figures
FOR INQURIES CONTACT AJIKARUNIA PALAR AT aji.palar@ucsf.edu



