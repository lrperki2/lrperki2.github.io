# Variable Selection

Before considering variable selection, I would plan to first conduct Exploratory Data Analysis. This will indicate broader measures like the shape of the distribution and spread of the data, as well as identify any outliers that could potentially influence the model. Additionally, producing a correlation matrix can be useful in identifying possible candidates for variable selection if any have strong linear relationships with the response. Then, I would rely on knowledge of the subject matter, as that would inform natural or logical variable selections. From there, I would use an algorithm-based technique, such as stepwise selection. 

Despite this method not having theoretical support, it is favorable in the sense that it is computationally efficient when compared to an approach like “all-possible subsets”, and can still produce usable results, particularly in situations where one may not have enough subject matter expertise to use a more traditional or thorough approach. 

From there, I would use a penalized criterion to evaluate the effectiveness of models, such as adjusted r-squared or AICc, because those methods balance the risks of overfitting and underfitting. Each additional variable will tend to give a better fit, but at a certain point stops generalizing well.
