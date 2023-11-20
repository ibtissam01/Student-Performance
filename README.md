# Student Performance Data Set

This is a README document for the Student Performance Data Set, which focuses on student achievement in secondary education at two Portuguese schools. If you find this data set useful, an upvote is appreciated.

## Introduction
The Student Performance Data Set provides insights into the performance of students in secondary education at two Portuguese schools. The data includes various attributes, such as student grades, demographic information, social factors, and school-related features. The data was collected through school reports and questionnaires.

Two distinct datasets are provided in this data set, one for the performance in Mathematics (mat) and the other for the performance in Portuguese language (por). These datasets have been modeled for binary/five-level classification and regression tasks, as described in [Cortez and Silva, 2008].

## Important Note
It's important to note that the target attribute, G3, has a strong correlation with the attributes G2 and G1. This correlation exists because G3 represents the final year grade, issued at the 3rd period, while G1 and G2 correspond to the grades obtained in the 1st and 2nd periods, respectively.

Predicting G3 without considering G2 and G1 is more challenging, but the prediction becomes much more useful when all three grades are taken into account. For more details on this correlation and its implications, please refer to the paper source mentioned above.

## Usage
This data set can be utilized for various purposes, including but not limited to:
- Analyzing the factors influencing student performance in secondary education
- Developing classification models to predict student achievement levels
- Conducting regression analysis to estimate final year grades based on prior performance

## Attribution
Please acknowledge the following paper as the source of this data set:
- Cortez, P., & Silva, A. (2008). Using Data Mining to Predict Secondary School Student Performance. In A. Brito & J. Teixeira (Eds.), Proceedings of 5th Future Business Technology Conference (pp. 5-12).

## Upvote
If you find this Student Performance Data Set useful for your research or analysis, an upvote would be greatly appreciated. Your support encourages the sharing of valuable data sets and promotes further research in the field of education.

Thank you for using this data set, and we hope it proves beneficial for your work.
