# decision-tree-classifier

This repository contains an implementation of a **Decision Tree Classifier** for predicting gender based on biological and self-reported activity traits of college students. The dataset, obtained from the **JSE Data Archive**, includes various demographic and behavioral attributes.

## Project Overview
- **Objective:** Build a decision tree classifier to predict gender based on features such as eye color, age, school year, height, and activity levels.
- **Dataset:** A dataset from a 2013 study on biological traits and behaviors of college students.
- **Methods Used:** Data preprocessing, Gini impurity calculation, and decision tree classification.

## Dataset Description
The dataset includes the following features:
- `Color` - Eye color (Blue, Brown, Green, Hazel, Other)
- `Age` - Age in years
- `YearinSchool` - First, Second, Third, Fourth, Other
- `Height` - Height in inches
- `Miles` - Distance from home town of student to Ames, IA
- `Brothers` - Number of brothers
- `Sisters` - Number of sisters
- `CompTime` - Hours spent on a computer per week
- `Exercise` - Whether the student exercises (Yes/No)
- `ExerTime` - Hours spent exercising per week
- `MusicCDs` - Number of music CDs owned
- `PlayGames` - Hours spent playing games per week
- `WatchTV` - Hours spent watching TV per week
- `Gender` - Target variable (Male/Female)

For more details on the dataset, refer to the original source: [JSE Data Archive](http://jse.amstat.org/v21n2/froelich/eyecolorgender.txt).

## Key Features
- **Exploratory Data Analysis (EDA):** Understanding feature distributions and correlations.
- **Gini Impurity Calculation:** Computing impurity for categorical feature splits.
- **Decision Tree Training:** Implementing a basic decision tree classifier.
- **Performance Evaluation:** Assessing classification accuracy.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/decision-tree-classifier.git
   cd decision-tree-classifier
