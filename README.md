# Module 11 Assignment 11.1 - Used Car Pricing

## Summary

This repository contains an analysis of a Kaggle provided used car dataset. The data has been pruned down from 3 million used cars to around 400,000. Some summary findings:

* The lack of an automatic transmission has a larger than expected positive influence on the price of a vehicle.
* Cars that aren't fueled by gasoline have a higher resale value. 
* Cars fueled by electricity have a bimodal distribution with a large segment around $40,000.
* If customers do want a gasoline engine, you will get more money for more cylinders.

## Analysis

The [Jupyter notebook](practical_applicaton_2.ipynb) contains the data analysis and recommendations. The notebook takes into consideration the effect of various used car features and transforms them as appropriate to ordinal or one-hot features.

Cleaning the data to have sufficiently populated fields and removing nonsense values like $0 sales took the majority of the time. Adding a feature value of "other" is not as useful as fully enumerating the values. With a complete set of values a field like the number of cylinders could be converted to ordinal.

The results of the analysis were that automatic transmissions and being fueled by something other than gasoline (particularly electricity) heavily influenced the selling price of used vehicles.

The repository also contains the [Prompt](prompt_II.ipynb) notebook with some introductory examination prompted by the course.