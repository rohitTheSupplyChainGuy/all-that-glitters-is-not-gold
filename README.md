# all-that-glitters-is-not-gold
Aren't Linear models the darling of data analysts ? Easier to interpret and test hypotheses, linear models definitely outweigh other models due to their simplicity. But then, sometimes this tendency and likeliness towards linear models can blind us.
In this project, I attempt to embark upon an important prerequisite for productionalizing a linear model and that is homoscadesticity.
The project also highlights the fact that a high R-squared, high correlation coefficient and low p-values are desirable in linear models. But that is not where it ends.  It is important to validate the residuals obtained from model for homoscadesticity along the operating range (range of fitted values). If these residuals are distributed randomly and do not form any patterns, we are good to go in most cases!
If not, try transforming the dataset. Here I attempt to transform the dependent variable using a Box-Cox transformation only to realize that even transformations do not always work.

And all of this is done on a dataset that I came across while preparing for Tableau Desktop Certified Specialist. A link to that is here: https://www.tableau.com/learn/tutorials/on-demand/trend-lines?playlist=484037

Acknowledgements statisticsbyjim:
https://statisticsbyjim.com/regression/heteroscedasticity-regression/

Files for the project:
wind-mill-dataset.csv: Dataset
allThatGlittersIsNotGold.Rmd: R-markdown file containing the source code
allThatGlittersIsNotGold.html: HTML file containing key insights and outputs from the R-code. Can be skimmed through
Figs folder: Contains the image files of the output from the .Rmd file
