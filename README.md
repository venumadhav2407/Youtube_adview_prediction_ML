# Youtube_adview_prediction_ML
To build a machine learning regression to predict youtube adview count based on other youtube metrics

> Download the Datasets from here 👉 :

<a href="https://github.com/venumadhav2407/Youtube_adview_prediction_ML/raw/f2819d334bb2ecf958bedd8f46c11d9f48ca246d/Datasets/train.csv" download> train.csv</a>
<a href="https://github.com/venumadhav2407/Youtube_adview_prediction_ML/blob/69c430874445ffdcd7e8c732561dc8e713fb09bd/Datasets/test.csv" download> test.csv</a>


> Attribute Information
- 'vidid' : Unique Identification ID for each video
- 'adview' : The number of adviews for each video
- 'views' : The number of unique views for each video
- 'likes' : The number of likes for each video
- 'dislikes' : The number of likes for each video
- 'comment' : The number of unique comments for each video
- 'published' : The data of uploading the video
- 'duration' : The duration of the video (in min. and seconds)
- 'category' : Category niche of each of the video

> Steps and Tasks
1. Import the datasets and libraries, check shape and datatype.
2. Visualise the dataset using plotting using heatmaps and plots. You
can study data distributions for each attribute as well.
3. Clean the dataset by removing missing values and other things.
4. Transform attributes into numerical values and other
necessary transformations
5. Normalise your data and split the data into training, validation and test
set in the appropriate ratio.
6. Use linear regression, Support Vector Regressor for training and get
errors.
7. Use Decision Tree Regressor and Random Forest Regressors.
8. Build an artificial neural network and train it with different layers
and hyperparameters. Experiment a little. Use keras.
9. Pick the best model based on error as well as
generalisation.
10.Save your model and predict on the test set.

