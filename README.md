### Link to Jupyter Notebook
https://github.com/d-veli/car_price/blob/main/prompt_findings.ipynb

### Motivation: What Drives the Price of a Car
In the notebook, we attempt to understand what factors make a car more or less expensive by building a regression model that predicts the price of used cars, provided certain features. From this model, we then extract the importance of each feature within the model. This information will inform us of the most important factors.

More technically, we will leverage Python, along with the supporting data science and machine learning libraries, namely Pandas, Numpy, and Sklearn. GridSearchCV will be used to search for the optimal regression model and optimal hyperparameters in order to achieve the data mining goal stated above.

### Findings and actionable items

We set out to understand what factors make a car more or less expensive. From our modeling on the used car dataset, we were able to extract the most important factors to the price of a used car in the marketplace. 

**Actionable items**

The model ranked the following five features highest in importance. We expand on it with the following recommendations. When refining your inventory, place emphasis on the following five points most:

- Model: Choose models that have a blend of high average price and volume in the marketplace. For example the top four vehicles in this vein are the F-150 and the Silverado, ranging from $14-18K on average and have high inventory to move around.

- Type: Relatedly, the marketplace values Trucks, Pick-ups, and Off-road cars. These average from $16-20K and are more than double the price of the least favourable cars, such as hatchbacks and sedans.
- Paint Color: White and black command among the highest average price between $14-15K. Avoid exotic colors other than Orange. Orange nets the highest average price at over $16K.
- Drive: The marketplace prefers 4WD most and desire FWD least. On average 4WD price is double that of a FWD, with 4WDs priced at $16K on average.

Lastly, the obvious that cannot be overstated:

- Condition: Select inventory that is in the best condition possible, the average price drops $5K in value moving down each condition level. From 'new' to 'like new' that drop is even higher at $10K on average.

**Next steps and recommendations**

- Immediately refine inventory where possible to maximize your lot capacity with used cars sharing the features above that the marketplace values, thereby improving your sales volume and sales margins. Lot space and labour costs are not free after all - make every spot count!

- We recommend using the available predictive model as a starting point when attempting to price new inventory competitively, which will reduce a used car's time on your lot and improve inventory turnover.

- Lastly, continue to collect data on your used car sales going forward so that the predictive model can be iterated upon with first-hand data.
