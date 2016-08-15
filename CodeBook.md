#Overview

##Source of the original data:

*[https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
Full Description at the site where the data was obtained:]

*[http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones
Process]

##Variables

1. testData - table contents of test/X_test.txt
2. trainData - table contents of train/X_train.txt
3. X - Measurement data. Combined data set of the two above variables
4. testSub - table contents of test/subject_test.txt
5. trainSub - table contents of test/subject_train.txt
6. S - Subjects. Combined data set of the two above variables
7. testLabel - table contents of test/y_test.txt
8. trainLabel - table contents of train/y_train.txt
9. Y - Data Labels. Combined data set of the two above variables.
10. featuresList - table contents of features.txt
11. features - Names of for data columns derived from featuresList
12. keepColumns - logical vector of which features to use in tidy data set
13. activities - table contents of activity_labels.txt. Human readable
14. tidyData - subsetted, human-readable data ready for output according to project description.
15. uS - unique subjects from S
16. nS - number of unique subjects
17. nA - number of activities
18. nC - number of columns in tidyData
19. td - second tiny data set with average of each variable for each activity and subject

##Output

##tidyData.txt

*tidyData.txt is a 10299x68 data frame.

1. The first column contains subject IDs.
2. The second column contains activity names.
3. The last 66 columns are measurements.
4. Subject IDs are integers between 1 and 30.

##tidyData2.txt

*tidyData2.txt is a 180x68 data frame.

1. The first column contains subject IDs.
2. The second column contains activity names.
3. The averages for each of the 66 attributes are in columns 3-68.