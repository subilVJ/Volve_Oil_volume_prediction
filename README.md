For Production engineer one of the most important work is to estimate the oil production from the operational parameters such as bottomhole pressure, tubing differential pressure, wellhead pressure etc. either using nodal analysis or by using empirical correlations. But most of these workflows assume the physics in some sort, which involves a lot of assumptions itself. So, in this article, we will try to use a totally different approach The Data-Driven Approach, where the computer will learn physics purely based on data. No Assumptions, No Complex Physics, Just Pure Data Based. Using daily production data of the Volve field, we will apply Linear,Polynomial and CatBoost regression to build a model and predict oil production.
## Conclusion

Prediction of Bore Oil Volume using Production Parameters is one of the most important work for a production engineer. The conventional way to do this is using empirical correlations which have a lot of assumptions and also these empirical correlations are derived from some specific field, so it is possible that these are not valid for some other fields. So, if we have sufficient production data from a field we can derive DATA BASED CORRELATIONS for that field by using machine learning algorithms. These correlations will be helpful for predicting bore oil volume for some new well at various production parameters in that field, and also these don't have any assumptions, just PURE DATA and STATS.

The models can be improved further by doing some more Feature Engineering and Trying other algorithms like Neural Networks, Support Vector etc.

## Reference and Links

Data-Driven Hydrocarbon Production Forecasting, Using Machine Learning Techniques, Masoud Safari Zanjani, Mohammad Abdus Salam, and Osman Kandara,Department of Computer Science, Southern University, Baton Rouge, Louisiana, USA
Link to codes-
Link to code of Exploratory Data Analysis - https://github.com/jaiyesh/Machine-Learning/blob/main/firstnb_scratchpafinald.ipynb
Link to code of the Machine Learning Models - https://github.com/jaiyesh/Machine-Learning/blob/main/Prediction%20of%20Bore%20Oil%20Volume%20.ipynb
Link to Volve Production Data - https://github.com/jaiyesh/M.Tech-Project/blob/master/Volve-2/Volve%20production%20data.xlsx
Link to my Repository on Oil and Gas Data Analysis Projects - https://github.com/jaiyesh/Gold-from-Jurrasic
