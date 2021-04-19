# Titanic-Survival-Classification

## Overview
In this study, we explore and analyse the data from titanic dataset. By this tragedy many people died, however, some people could still survive during the shipwreck! This dataset, including 15 columns including some information such as gender, age distribution and the residency-class of passengers. By classification, we may undestand if the survival of the passengers might have been dependent on their residency-classes, age or their genders.

Source of dataset: The Dataset of Titanic (as a csv. file) is available on the Kaggle.com. you may also find it under the projects profile.



There is female and male gender identified and here is the distribution of total number of passengers based on the gender:

![image](https://user-images.githubusercontent.com/64262003/115146297-2e56bc80-a056-11eb-82ba-fb6a8daee5b6.png)
Clearly, there were more male passengers.

![image](https://user-images.githubusercontent.com/64262003/115146332-5ba36a80-a056-11eb-8b51-875813677732.png)
In this line, we can observe the proportion of survivals vs. dead passengers based on the gender classification:
![image](https://user-images.githubusercontent.com/64262003/115146538-319e7800-a057-11eb-8031-6f1503956a43.png)

A facet.map (or a box-plot) may help us to see how the age of mentioned classifications distributed:

![image](https://user-images.githubusercontent.com/64262003/115147966-bbe9da80-a05d-11eb-8139-94c99167c4d8.png)


From the diagrams above, we can see clearly that age distribution is not even. Histograms are right-skewed and there ouliers in 'male survival' dataset. Moreover, the age distributions remark the age groups from children to elder people. Therefore, it could be helpful to define arbitrarily new categories of passengers but according to their age-classes such as children, youth, adult and old. Afterward we can analyze how the survival of these group and their percentual distributions look like:

The first pie-diagram presents the whole percentual distributions, however, the second one collects the the percents of the survivals:

![image](https://user-images.githubusercontent.com/64262003/115148160-a1fcc780-a05e-11eb-890c-ab1aa81c6509.png)
![image](https://user-images.githubusercontent.com/64262003/115148235-f738d900-a05e-11eb-9cdd-7c2c34221ea4.png)

The second pie-diagram reveals that the adult had the highest chance and the elder people had the lowest chance to survive.

The last study is about the proportion of survivals vs. their classes. For more study, please refer to the notebook of the project.
