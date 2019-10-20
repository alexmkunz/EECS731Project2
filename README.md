# EECS 731 Project 2: To Be, or Not to Be
Use a decision tree to predict the character speaking in Shakespeare plays.

## Data Set
**Shakespeare_data.csv**: Shakespeare play information.

## Juypter Notebook
**toBeOrNotToBe.ipynb**: notebook that contains data analysis, preparation, and encoding, as well as a decision tree classification model.

## Data Analysis and Preparation
Drop any rows that include a NaN.

### Columns
- **Dataline**: pointless column tracking the column number. Removed.
- **Play**: the play the character is in. One-hot encoded.
- **PlayerLinenumber**: the line number the character is speaking. Used as a feature variable.
- **ActSceneLine**: The act, scene, and line when the character is speaking. Used as a feature variable after label encoding.
- **PlayerLine**: the words the character is saying. Removed because it is not correlated to the character.
- **Player**: the character speaking, which is our target variable. One-hot encoded.

## Decision Tree
- **Splitting the data**: 80% train, 20% test
- **Accurary**:  0.7806095763396891
