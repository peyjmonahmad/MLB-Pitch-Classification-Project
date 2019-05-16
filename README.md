# MLB-Pitch-Classification-Project
This repository consists of the workflow for classifying approximately 719,000 different pitches from the 2011 MLB season.

The main objective at hand dealt with solving a multiclass classification problem.  With the pitch type as the target variable, the goal was to correctly identify between 18 different types of pitches.  The most commonly seen pitches included the four-seam fastball (238,541 occurrences) and the slider (109,756 occurrences).  Just these two pitches accounted for nearly half of the pitches in the dataset.

The beginning stages included extensive cleaning, imputing values, and dropping many columns that had no use towards ultimately predicting the correct type of pitch.  Next, I performed some exploratory data analysis, which was critical for understanding distributions of unique variables, correlations, and necessary data type conversions.

Once the data was in shape for modeling, the main algorithms applied were Logistic Regression and Random Forest.  Logistic Regression performed very poorly, while the data appeared to fit the Random Forest model very well.  The best results achieved were 87% weighted precision and recall scores, meaning that about 623,512 out of 716,681 total pitches were correctly classified as the true pitch delivered.

My entire workflow and analysis can be seen in my MLB_Pitch_Classification_Project.ipynb notebook.



