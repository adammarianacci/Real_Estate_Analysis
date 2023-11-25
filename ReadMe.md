# Coldwell Banker Real Estate Agency Needs Analysis

**Author**: [Adam Marianacci](mailto:adam.marianacci@gmail.com)

## Overview

This project analyzes the resource needs of Coldwell Banker Real Estate Agency. 

## Business Understanding

Coldwell Banker wants to buy undervalued homes in certain zipcodes to minimally renovate and sell for a profit. It is my job to find homes that are being listed significanty lower than the median price and look into what variables are causing these lowered prices so that I can properly advise Coldwell Banker on which homes to target. 

## Data Understanding

This project uses the King County House Sales dataset. It contains over 30,000 entries of data related to the sale price of houses, number of bedrooms,bathrooms and floors, square footage, addresses, and more. The main dataframe used in this project only contained roughly 14,000 entries. A limitation of the data was that it is fairly small since we are dealing with predictive modeling. Also the features of the data were strongly correlated with each other (multicolinearity) rather than the target variable. The dataset is suitable for this project because it has information to reveal which homes are truly being undervalued in certain zipcodes. After analyzing the price, location, and other various specifications and amenities of homes I will be able to make informed recommendations to the real estate agency.

## Data Preperation

## Modeling

This project uses Linear regression modeling to predict various features of homes against the target variable of price.

## Results


## Conclusions

## Evaluation

The "kitchen sink" model is the best performing model. It has the highest variance of the 3 models but it is still fairly low at 33.2%. It has the lowest root mean squared error of the 3 models at roughly 312,000 which is still very large. For these reasons the model should not be used for predictive measures. From the model we did learn that one unit of square footage is approximately equal to to about 128 USD in price. A 1 unit increase in grade is approximately equal to 96,000 USD in price which seems high. It also shows that an additional bathroom is equal to about 17,000 USD in price. These are the features that seem to have the biggest impact on price.

## Limitations

## Next Steps

We need a lot more data/records (hundreds of thousands) specifically in the zipcodes below the median price for homes in the county. Ideally trying to find features that do not have a lot of multicolinearity. Also obtaining data on schools in the district as well as crime reports in the county would be helpful as the would definitely have an impact on price. This kind of data would not be correlated with standard features of a home. Gathering data on revonvation costs would also be useful as it is important to know if certain renovations are even worth doing to increase the value of a home. 

## Recommendations


## For More Information

See the full analysis in the [Jupyter Notebook](.ipynb) or review this [presentation](.pdf).

For additional info, contact Adam Marianacci (mailto:adam.marianacci@gmail.com)


## Repository Structure

```
├── data
├── images
├── README.md
├── Presentation.pdf
└── notebook.ipynb
```
