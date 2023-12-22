## Logistic Regression
Logistic Regression is an algorithm mainly used for binary classification. It is used to estimate the probability of data that belongs to a class (e.g.,what is the probability that this email is spam?). If the probability is greaterthan 50%, then the model predicts that it belongs to “1” class(positive), and otherwise it predicts that it does not i.e., it belongs to
the “0” class(negative).

The odd is the ratio of something occurring to something not occurring. it is different from probability as the probability is the ratio of something occurring to everything. So odd will be

$\ \frac{p(x)}{1-p(x)} '$ = e<sup>z</sup>     

Applying natural log on odd. then log odd will be

$\ \log \left[\frac{p(x)}{1-p(x)} \right] '$ = z  

$\ \log \left[\frac{p(x)}{1-p(x)} \right] '$ = w . X +b     

then the final logistic regression equation will be:

 p(X;b,w) = $\ \frac{e^{w\cdot X +b}}{1+e^{w\cdot X +b}} '\$ = $\ \frac{1}{1+e^{-w\cdot X +b}} \$    
