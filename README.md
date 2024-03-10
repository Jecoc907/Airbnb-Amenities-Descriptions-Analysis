# Airbnb-Amenities-Descriptions-Analysis
In this project, our team is interested in looking into the effect of “Above and Beyond” Descriptions of Amenities on Airbnb Ratings in Los Angeles.

Definition:
"Above and Beyond" Descriptions of Amenities: After doing some research on airbnb listing, we found that there are numbers of default amenities that hosts could pick and choose to put on their listing. We noticed that some of them would customize their amenities by adding extra informations, such as mentioning "Fast" Wi-Fi comparing to Wifi. We believe these airbnb hosts are more willing to provide higher quality service to their visitors and we classified them as the "Above and Beyond" hosts.

Methodology and Approach:
We first go over the amenities in all listing in our dataset, whichever has extra description on Wi-fi and TV would be considered as our treatment group (adjective = 1) and the rest would be the control group (adjective = 0). OLS linear regression and two sample t-test were used to compare the rating performances of the two groups.

Result:
We found a slightly rating difference between the two groups (Treatment group in average have a higher rating). However, the low R-square value and the clustered and fan out residual plot proved that our model is suffered from skewness of the data, problem of heteroscedasticity and non-linearity.
