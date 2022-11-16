# Project 3 Response

## Summary

The third project focused on building predictive models on a data set and automating report generation and analyses through R Markdown. We read in a data set, formatted it to be suitable for automation, conducted exploratory data analysis, fitted models, then compared the model outputs, all as separate reports for different levels of a variable.

## Reflection

The most challenging aspect of the project for me was figuring out the interactions between the R Markdown automation and github/file formatting. Since all of the processing happens behind the scenes, at times it was difficult to follow how/why files were being processed, or why things needed to be formatted a certain way to work, or if they were working. 

If I were to approach a similar project in the future, I would try to find another method for the R markdown automation. The approach used worked well, but we needed to render the whole report on one level of the parameter in order to generate the list of parameters needed to automate across all levels. It would be interesting to see if there is a viable or practical way to generate a dynamic list without having to run the report an extra time.

Major take-aways from the project are that R Markdown can be useful for automating dynamic reporting and that feasibility can have a significant impact on modeling. It would have been ideal to train the random forest model on a larger selection of variables, for example, but the processing time required made it unrealistic.

You can find the final report [here](https://lrperki2.github.io/Project3/) and repo [here](https://github.com/lrperki2/Project3).
