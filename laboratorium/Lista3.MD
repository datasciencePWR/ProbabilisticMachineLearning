# Task List 3
## Data manipulation and statistics

### Knowledge & Skills:
- central limit theorem
- correlation
- covariance
- data acquisition
- pandas


### Exercises:
1. (2 p.)Visualize how CLT is observable and depends on the number of trials with experiments described by Bernoulli, binomial and multinomial distributions. Explain observations.
    How to:

    1. Simple introduction:

	    - Generate k samples of size n from an exponential distribution
	    - Draw a histogram of a mean value of each sample
	    - Create histogram animation using n parameter (animation starts with n=0, increase in each frame)

    2. Bernoulli:

	    - generate n Bernoulli trials (with probability p)
	    - Count number of successes in each trial
	    - Visualize histogram of the number of successes
	    - Create histogram animation using n parameter (animation starts with n=0, increase in each frame)

    3. Binomial:

		- Have you alredy done it? Think about it.

    4. Multinomial:

		- As in Bernoulli

2. (3 p.)Acquire two appropriate datasets from [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/) (script within notebook/collaboratory, using pandas for manipulation) and provide an exploratory analysis of its content:

    Dataset requirements:

	    - at least five numerical attributes attributes
	    - at least 1000 instances

    Tasks:
    
	    - scatter plot of EACH attribute pair (matrix of plots), on diagonal we want to see histogram of given attribute ([link](https://seaborn.pydata.org/tutorial/distributions.html), [link](https://seaborn.pydata.org/generated/seaborn.PairGrid.html#seaborn.PairGrid), [link](https://pandas.pydata.org/pandas-docs/stable/visualization.html#scatter-matrix-plot))
	    - scatter plot of each attribute pair with histograms on axes (write a function that generates plot for given attributes pair) ([link](https://seaborn.pydata.org/generated/seaborn.jointplot.html#seaborn.jointplot))
	    - correlation (for EACH attribute pair, if appropriate)
	    - covariances (for EACH attribute pair, if appropriate)

Elaborate on results.


### Remarks

1. Animation means animation, not painting again on same canvas with a wired artefact.
2. Use appropriate tools to solve tasks, if the selected tool does not allow to create animation than change the tool
3. Collaboratory allows you to create animation easily (look at List 1 code snippet)
4. Do not repeat your self, write functions and loops instead of copying code
5. Use documentation of libraries (API, tutorials etc.)
