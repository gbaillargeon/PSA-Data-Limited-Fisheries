# PSA-Data-Limited-Fisheries
Repository for Publication: "Improving the Productivity-Susceptibility Analysis for Data-Limited Fisheries"

This code requires a file with the foloowing columns: productivity, susceptibility, vulnerability, and species. Which houses the PSA resutls data. 

You will need the following packages: pandas, numpy, matplot lib patches, transforms, pyplot, and sklearn.

The code is organized in the following sections: Importing data, Defining an ellipse, GMM definiton and parameters, Preparing data for GMM plotting organized by cluster, and plotting the PSA data wiht ellipses generated by the GMM.

The code and comments are tailored to my PSA data set consisting of 32 marine aquarium fish species.  However, the sustainability labeling of clusters produced for other datasets will neeed to be re-assessed on a case by case basis.  Although this Gaussian Mixture Model (GMM) clustring alogrithm was produced for clustering PSA results, it can be applied to any PSA dataset using this code. 



