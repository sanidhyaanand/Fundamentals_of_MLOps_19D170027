# Question 1
## AIOps vs MLOps
1. AIOps can be referred to as the practice of improving already existing IT infrastructure by using analytical tools and Machine Learning techniques. <br> 
2. This is done by using the data collected by the same organisation (which is owning the infrastructure). <br> 
3. Instead of being part of DevOps practices, it contributes to making the methods and systems selected by DevOps/MLOps engineers more efficient, with automation of such systems being a key focus. <br>
4. In contrast, MLOps focuses primarily on optimising the end to end pipeline for model development, training and deploying/monitoring. It can be said that one application of AIOps would be making the various processes of MLOps more robust and efficient.<br> <br>

[Sources](https://opensource.com/article/21/2/aiops-vs-mlops)

# Question 2
## Interpretable Linear Regression
Linear Regression is a wildly used algorithm due to its simpleness and ease of use, which contributes to easy interpretation. This fact arises as it is a simple linear sum of feature components multiplied by their weights, with a constant intercept term added. Interpretation of the parameters (weights) of linear regression can be done in the following ways:<br>
1. Feature Change: Assuming other features do not change, a single unit change in a feature xk will result in an overall change of bk in the output (if bk corresponded to the feature xk in the linear sum).
2. Binary Features: A change in the 0,1 value of a binary feature xk results in a change in output by bk.
3. Categorical Features: These features may be one hot encoded and converted to binary features, thus retaining the same above properties of change.
4. Feature Importance: Feature Importance can be measured by the weight of the corres. feature divided by the variance of the weight. If a feature is important, it will have high weight and low variance for it.
5. R-Squared: R-Squared is a derived parameter from which the explanation for variance in your data can be inferred. <br><br>

[Sources](https://christophm.github.io/interpretable-ml-book/limo.html#interpretation)