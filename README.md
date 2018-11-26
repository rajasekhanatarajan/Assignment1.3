# Assignment1.3

Skip to content
 
Search or jump to…

Pull requests
Issues
Marketplace
Explore
 @rajasekhanatarajan Sign out
0
0 0 badz11/assignment1.3
 Code  Issues 0  Pull requests 0  Projects 0  Wiki  Insights
assignment2.1
 4 commits
 1 branch
 0 releases
 1 contributor
 @badz11
badz11 Update README.md
Latest commit 34c6b9d  on Sep 10
Type	Name	Latest commit message	Commit time
README.md	Update README.md	3 months ago
assignment2.1.txt	Add files via upload	3 months ago
 README.md
assignment1.3
What are the different methods to call a function in R?
ans:First, you use () as usual, to denote a call to a function, immediately after the keyword function : this can specify the argument, in the example x ;

Secondly, a () couple encircles the function(x) declaration and body;

call(name, …)

is.call(x)

as.call(x)

call returns an unevaluated function call, that is, an unevaluated expression which consists of the named function applied to the given arguments (name must be a quoted string which gives the name of a function to be called).

Note that although the call is unevaluated, the arguments … are evaluated.

call is a primitive, so the first argument is taken as name and the remaining arguments as arguments for the constructed call: if the first argument is named the name must partially match name.

The lazy evaluation of a function means, the argument is evaluated only if it is evaluated only if it is used
inside the body of the function.

ans:True

State True or False:
a. Insights driven from descriptive analytics is not meaningful.

ans: False

b. The number of values in each Elements of a list, should be equal.

ans:True

c. The datasets are not stored in memory of the computer using R.

ans: False

d. Data frames and matrices are two dimensional however the array is multidimensional.

ans:True

© 2018 GitHub, Inc.
Terms
Privacy
Security
Status
Help
Contact GitHub
Pricing
API
Training
Blog
About
Press h to open a hovercard with more details.
