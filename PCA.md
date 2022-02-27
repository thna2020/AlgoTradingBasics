# Principal Component Analysis (PCA)

## Why PCA?
Your team surveys 1,000 users about a particular mobile phone application. The survey has 7 statements, and the users are asked to indicate their opinion on a scale of 1 (very disastified) to 5 (very satisfied) about the app. The statements are:

1. The app is easy to install.
2. The app is easy to use.
3. The app is secure.
4. Support team is timely for assistance.
5. Support team does a great job of answering user's questions.
6. Documentation is clear to follow.
7. The app is worth its price.

Your team collects data in a 1,000 x 7 matrix Y. Each column is for one statement. Each row corresponds to one user.

Some statements are correlated, so the team might not need all the data &rarr; PCA.

## Covariance Matrix
1. Find the mean of each column and subtract the mean from each element of the column.
2. Call the new 1,000 x 7 matrix X. Each column of X has mean zero.
3. Let K = (X^T)X, where K is the 7 x 7 matrix of covariances.
- The diagonal entries give the variances of the variables.
- The (3,4) entry gives the covariance between the 3rd and 4th statements.
- High covariance means close to a linear relationship. Zero covariance means no correlation.
