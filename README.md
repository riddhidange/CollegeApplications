# CollegeApplications


# Aim:
The process of deciding which universities to apply to is very crucial as most universities have a holistic approach in deciding which application is strong. Therefore, to decide whether an application is strong enough for an applicant to get a college of their choice, we implement Machine Learning algorithms on our  dataset consisting of important attributes contributing towards this result. ![image](https://user-images.githubusercontent.com/67019064/230849964-dbbaa05a-c21f-474f-aa77-20fd2b654fad.png)


# Conclusion:
Linear Regression

As we can notice that the Linear Regression (over selected features) performs best as we had selected the most important values needed for prediction and hence it gave us the least error without dimensional reduction. Even after PCA reduction it wasn't able to provide a better prediction since the reduction leads to some loss of data which could have caused this change in error.

Support Vector Regression

In contrast, SVR works better after PCA reduction because unlike linear regression which tries to fit a best line in the scatter plot, SVR fits a line within a threshold of values (decision boundaries). So, dimensional reduction helps the model to tighten those boundaries better with more additional information (features).

