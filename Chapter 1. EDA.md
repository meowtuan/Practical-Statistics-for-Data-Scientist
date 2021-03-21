Chapter 1. Exploratory Data Analysis
===
3.21
---
* Exploratory Data Analysis-EDA
  To apply the statistical concepts, unstructured raw data must be processed and manipulated into a structured form.

* Data type: important to help determine the type of visual display, data analysis, or statistical model
    * -Numeric
        * continuous
        * discrete
    * -Categorical(enums)
        * binary(boolean/indicator)
        * ordinal(factor): ordered categories
            ex. numerical rating (1, 2, 3, 4, or 5)
    
* data structure
  * Rectangular data struture
    * Feature: column. (attribute/input/predictor/variable)
    * Outcome: often binary. (dependent variable/response/target/output)
    * Records: row. (instance/observation/sample/pattern)
    * For a statistician, predictor variables are used in a model to predict a response or dependent variable. For a data scientist, features are used to predict a target.

  * Nonrectangular data structure
    * time series data: successive measurements of the same variable
    * spatial data structures
    * graph/network data structures

* Estimate of location
  * Mean; Trimmed mean: drop a fixed number of sorted values at each end; Weighted mean
  * Median: even, average of middle two; Weighted median: the sum of the weights is equal for the lower and upper halves of the sorted list.
  * Outlier: somewhat subjective, should be identified and are usually worthy of further investigation.
  * Median, weighted median, trimmed mean are robust to outliers.
  * The trimmed mean can be thought of as a compromise between the median and the mean: it is robust to extreme values in the data, but uses more data to calculate the estimate for location.









