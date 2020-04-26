# Survey-Analysis

## Dependencies
To run ```correlation_filtering.ipynb``` you'll need Anaconda (and Jupyter Notebook), numpy and pandas. Versions of each library are listed inside ```ipynb``` file.

## Assumptions
It is assumped features from different groups are independent.

## Output
There will be two output directories: ```result``` includes all correlation coefficients between each feature and each output; ```results_groups``` includes all correlation coefficients between each groups and each output, named by ```group_output_corr.csv```. You can also modify outputs by uncommenting code snippets inside the ```ipynb``` file.