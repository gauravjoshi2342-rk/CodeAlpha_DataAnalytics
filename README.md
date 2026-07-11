 Task 2: Exploratory Data Analysis (EDA)

Goal: Understand the dataset inside-out before drawing any conclusions from it.

What's inside:
Checked the data structure — shape, column types, missing values
Cleaned messy fields (e.g. parsed the helpful votes column, converted review dates)
Explored rating distribution, review volume over time, and top-reviewed products
Compared review length across star ratings
Ran a statistical hypothesis test to check if negative reviews are longer than positive ones (they are — confirmed with a t-test)
Flagged data-quality issues like duplicates and inconsistent helpfulness counts

Tools used: Python, Pandas, Matplotlib, Seaborn, SciPy

Key takeaway: The dataset is skewed towards positive reviews (~74% are 4-5 stars), review activity spikes around certain months, and a small set of products account for a large share of all reviews — all important context for the sentiment analysis that follows.
