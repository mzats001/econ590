# econ590
HW stuff
Problem Set 1
Special Topics in Economics (Econ 590)
Cal State Fullerton
Due: Febrary 11, 11:59 pm PST
Rules
Submit a single file named assighment1 Name Lastname.pdf to Canvas by the date and time above.
You can convert Jupyter Notebook file (.ipynb) to pdf file by clicking File-Download-Pdf via Latex.
This file must contain problem set writeup, code, and output.
Problem 1: For Loop (10 points)
Use a for loop to:
a. Print the numbers 0 to 100
b. Print the numbers 0 to 100 that are divisible by 7
c. Print the numbers 1 to 100 that are divisible by 5 but not by 3
d. Print for each of the numbers x = 2; : : : 20, all numbers that divide x, excluding 1 and x. Hence,
for 18, it should print 2 3 6 9.
e. The smallest number that is divisible by 2, 3 and 4 is 12. Find the smallest number that is divisible
by all integers between 1 and 10.
Problem 2: Numpy (20 points)
Generate matrices A, with random Gaussian entries B, a Toeplitz matrix, where A ∈ R
nxm , B ∈ R
mxm,
for n = 200, m = 500.
a. Calculate A + A, AAT
;AT A and AB.
b. Solving a linear system. Generate a vector b with m entries and solve Bx = b.
c. Nearest neighbor. Write a for loop that takes a value z and an array A and finds the element in A
that is closest to z. it should print the closest value, not index.
Hint: Use the built-in functionality of Numpy rather than writing code to find this value manually.
In particular, use brackets and argmin.
1
Problem 3: Pandas (20 points)
Complete three exercises that we started during the class.
Problem 4: Pandas (20 points)
We are going to analyze the cost of college data scorecard provided by the federal government. Here is
the link - https://collegescorecard.ed.gov/data/. Columns of interests are Columns of interest UNITID,
INSTNM, STABBR, CITY, GRAD DEBT MDN SUPP, SAT AVG
a. Find the top 10 median 10 year debt
b. Find the top 10 median earnings
c. Find the top 10 schools with the best sat scores
d. Find the top 10 best return of investment
e. Find average median earnings per state
f. Compute the correlation between the SAT scores and median income
Problem 5: Data anaylsis and visualization(30)
You will use Pandas to analyze the Google Play Store data set. I will ask you to manipulate the data in
certain ways in order to show different interesting visualizations. Specifically, you will:
a. Load the googleplaystore user reviews.csv (reviews) and googleplaystore.csv (apps) data sets
as pandas DataFrames. You should use the pd.read csv() function for this purpose.
b. Delete any review that does not contain either a Translated Review or a Sentiment. The pd.dropna
function will be helpful for this.
c. Remove any apps whose Rating is invalid (higher than 5).
d. Produce a pie chart with the Android Ver requirements for the different apps. Group together all
versions that make up less than 5% of the total apps into a single ‘Others’ category. This should
look similar to Figure 1a.
e. Create a similar pie chart for app Category. In this case, group together categories that make up
less than 3% of the apps. The resulting graph should look something like Figure 1b.
f. Show histograms of the Rating and Reviews across all apps, with 20 bins each. Example histograms
can be seen in Figure 1c.
g. Plot a bar chart with the different Sentiment. The sentiments chart should look similar to Figure
1d.
h. Combine the two DataFrames into a single one, based on the App names. You should make sure
that all apps from the apps DataFrame are kept, and no app beyond those is added. The pd.merge
function will be useful for this.
2
Figure 1: A boat.
i. Group the Sentiment by rounded Rating, and produce a bar chart where you display the different
sentiments grouped by rating. You might find the pd.groupby, np.round, and df.unstack
functions helpful for this task. The grouped sentiments plot should look like Figure 1e.
3
