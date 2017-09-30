STAT 231
===

#### Lecture 1: Sep 8, 2017

STAT 230 question: A fair coin is tossed 100 times. Find the probability that we have exactly 60 heads. 
STAT 231 question: Say we have a coin and toss it 100 times. We observe 60 heads. What can we say about the "fairness" of the coin? 

In STAT 230, population => sample. (Deductive)
In STAT 231, sample => population. (Inductive)

*Example 1*: Baseball - The disappearance of the 400 hitter. 
Batting average (BA) = # of successes / # of attempts
Batting champion = guy with highest batting average in a season
$ \leq 1941$: 13 batting champions with score $\geq 0.4$
$ > 1941$: 0
Why did the 400 hitter disappear? Will we ever see a 400 hitter again? 
Reason: hitters and pitchers both got better, making 400 hits almost impossible. 

*Example 2*: Challenger Disaster

*Example 3*: Testing of claims
Are experts truly experts? 
eg. weather Forecasters, ESPN pundits, stock predictions

*Example 4*: correlation unequals causation
How can we make the logical leap from correlation to causation? 


#### Lecture 2: Sep 11, 2017

Empirical studies: result changes from experiments to experiments

*Example 1*: Approval rating of Trump
Approval rating = # of people who says yes / total # of people interviewed
*Example 2*: Test claims of drug companies
*Example 3*: Predict number of km before tune-up

Two types of empirical study: 

- Experimental: data collector has control over some of the variables (physical sciences) 
- Observational: data collector has no control over the variables (social sciences)
	- Sample surveys: the population is finite and theoretically knowable

Errors are inevitable in empirical studies. We try to quantify and minimize errors.

Definitions: 

- Unit: evrey member of the population
- Variate: property of the unit we care about
$
    y_i= 
\begin{cases}
    0,& \text{if does not approve} \\
    1,  & \text{if does}
\end{cases}
 $
- Attribute: a function of the variate
$y_1, \dotsc, y_n  = f(y_1, \dotsc, f_n) = \text{attribute}$

	For example, we have the variates
	$y_i = $ salary of individual $i$ 
	A possible attribute is the average of the $y_i$'s. 

Types of data

- categorical
	- binary: two categories
	- ordinal: categorical variables have an underlying order
- numerical
	- discrete: can only take integer values; eg. counting
	- continuous: can only take real values; eg. measuring

The attributes of population will generally be unknown and denoted by Greek letters. 
The attributes of sample can be calculated; they are denoted by English letters. 
	$\mu =$ population mean
	$\bar{y} =$ sample mean

We try to summarize data and extract important information through the following properties: 

- measures of central tendency: center
- measures of dispersion: data spread
- measures of skewness: data symmetry
- measues of kurtosis: how common are the extreme observations; how long are the tails

####Lecture 3: Sep 13, 2017

**Measure of Location (Central Tendency)**
Data set: $\{y_1, ..., y_n\}$
Sample mean:  $\bar{y} = \frac{1}{n} \sum^n_{i=1} y_i$

Properties of sample mean: 

1. The sum of the deviations of all observations fromthe sample mean is 0
$(y_1 - \bar{y}) + \dotsc + (y_n - \bar{y}) = \sum^n_{i=1}(y_i - \bar{y}) = 0$

2. Say we have $x_1, \dotsc, x_n$ such that $y_i = a+bx_i$. Then, $\bar{y} = a+b\bar{x}$. 
*Proof*: Since $y_i = a+bx_i$, 
$\sum y_i = \sum(a+bx_i) = \sum a + b \sum{x_i}$, 
so $\bar{y} = \frac{na}{n} + \frac{b \sum x_i} {n} = a+ b\bar{x}$

Affine Transformation and Linear Transformation

*Ex 2*
Year 1: 4%. Year 2: 8%. Year 3: 12%
Let x be the average interest rate. Then, 
$(1+x)^3 = (1+0.04)(1+0.08)(1+0.12)$
Solve for x. 

Geometric mean = $(y_1 \cdot \dotsc \cdot y_n)^{1/n}$
Arithmetic mean = $(y_1 + \dotsc + y_n) / n$
Harmonic mean = $\frac{2}{1/a + 1/b}$

*Ex 3*: Harmonic mean
Travels $x$ km at 40kmph,and $x$ km at  60kmph. 
The average speed is $\frac{2x}{x/40 + x/60}$

Median ($\hat{m}$): middle-most observation, take mean the number of inputs is even

Quartiles
- Q1: lower quartile; observation below which 25% of the data lies
- Q3: upper quartile; observation below which 75% of the data lies
- Percentiles: data is divided into 100 parts
- Q2: median

Mode: observation that occurs with the maximum frequency


####Lecture 4: Sep 15, 2017

**Measure of dispersion**

- Range = max - min
- Sample variance: $s^2 = \frac{\sum(y_i - \bar{y})^2}{n-1}$
- The sample standard deviation is $s = \sqrt{s^2}$ 
- $IQR = Q_3 - Q_1$

Properties of Variance

1. The variance can be expressed by two expressions. 
$s^2 = \frac{1}{n-1} \sum \left( y_i - \bar{y} \right)^2 =  \frac{1}{n-1} \sum \left( y_i^2 - n \bar{y}^2 \right) $

2. Original data set $\{x_i\}$. Transformed to $\{y_i\}$ by $y_i = a + bx_i$. 
Then, $s_y^2 = b^2 s_x^2$. 

3. $IQR = Q_3 - Q_1$
Given percentile $p$ and an array of data $A$. Arrange data set in ascending order. 
Then, let $m = (n+1) p$
If $m$ is an integer, $A[m]$ is the quantile. Else, take the mean of the two nearest observations. 

**Measure of Skewness**
If data is symmetric, then mean = median
skewness = mean-median

$$g_1 = \frac{1/n \sum(y_i - \bar{y})^3}{ \left( 1/n \sum (y_i - \bar{y})^2 \right) ^{3/2}}$$

mean > median: possibly right skewed
mean < median: possibly left skewed

**Applications**

1. Disappearance of 400 hitter
	- Pitchers' improvement is not greater than batters' improvements. This is evidenced by the average of average batters remaining constant over the years. If pitchers improved more, the average batting average would be expected to fall. 
	- It is caused by the decrease in the variance over the year. 
	- Extremes disappears, no more horrible pitchers to boost scores. 
2. Gould
	- Diagnosed with aggressive cancer, median survival rate of 8 months. 
	- If the data is symmetric, Gould would be dead around 8 months. 
	- Assymetric data with long tails to the right => Gould survived the cancer. 
Normal Distribution

####Lecture 5: Sep 18, 2017

**Measure of Kurtosis**
95% of all observations are within $\mu$ +/- 2 $\sigma$
99% of all observations are within $\mu$ +/- 3 $\sigma$

$X \sim N (\mu, \sigma^2)$: 
\begin{align*}
q(|X-\mu) \leq 3\sigma) &= P\left( \left|\frac{X-\mu}{\sigma} \right| \leq 3 \right) \\
&=  P\left(  -3 \leq \frac{X-\mu}{\sigma} \leq 3 \right) \\
&= P\left(  -3 \leq z \leq 3 \right) \\
&= 0.99 \quad \textrm{(given by z table)}
\end{align*}

Kurtosis > 3: fatter tails compared to normal distributions
Kurtosis < 3: thinner tails compared to normal distributions. 

Applications: Financial data typically have kurtosis > 3. 


**Bivariate Data**
We have two variables $X$ and $Y$. 
Objective: To come up with a measure that calculates the degree of association between the two variables. 

*Categorical Variables*
Example: Smoking and income. 
Smoker vs. non-smoker, poor vs. rich

$A$ and $B$ are independent if $P(A|B) = P(A)$ and $P(A|B^C) = P(A)$. In other words, 
$$\frac{P(A|B)}{P(A|B^C)} = 1$$

Given the data, 
$$
\begin{array}{c|ccc}
 & \text{Smoker} & \text{Non-smoker} &  \\
\hline
\text{Poor} & y_{11} & y_{12} & y_{11}+y_{12} \\
\text{Rich} & y_{21} & y_{22} & y_{21} + y_{22} \\
\end{array}
$$

The probability of smoking given poor is
\begin{align*}
P(smoking|poor) &= \frac{P(smoking, poor)}{P(poor)} \\
&= \frac{y_{11}}{y_{11}+y_{12}}
\end{align*}

The probability of smoking given rich is
\begin{align*}
P(smoking|rich) = \frac{y_{21}}{y_{21} + y_{22}}
\end{align*}

If the data is independent, the the Relative Risk (R.R) should be
\begin{align*}
\frac{y_{11} / (y_{11} + y_{12})} {y_{21} / (y_{21}+y_{22})} = 1
\end{align*}


If $R.R = 1$, there is evidence of no association. 
If $R.R >> 1$ or $R.R << 1$, there is evidence of association. 
In Chapter 7, we answer the question "how high is too high?".

*Numerical Variable* 

Sample Correlation Coefficient: 
$$r_{xy} = \frac{\sum (x_i - \bar{x}) (y_i - \bar{y})}{ \left( \sum(x_i - \bar{x}) ^2\right) ^{1/2} \left( \sum(y_i - \bar{y}) ^2\right)^{1/2} }$$

Example: 
$X = $ the number of beers an individual drinks. 
$Y = $ their mark in STAT 231. 

If $x_i > \bar{x}$, we would expect $y_i < \bar{y}$, and $(x_i - \bar{x}) (y_i - \bar{y}) < 0$
If $x_i < \bar{x}$, we would expect $y_i > \bar{y}$, and $(x_i - \bar{x}) (y_i - \bar{y}) < 0$

So the numerator tells you the direction of the relationship. 

Properties of $r$: 

1. $|r_{xy}| \leq 1$
2. If $y=a+bx$, r = 1 (if b > 0) and -1 (if b < 0)
However, the reverse is not true. 


#### Lecture 6, Sep 20, 2017

**Correlation Coefficient**

Two numerical variates, $x$ and $y$. To come up with a measure that calculates the direction and strength of the relationship between $x$ and $y$. 

$$r_{xy} = \frac{\sum (x_i - \bar{x}) (y_i - \bar{y})}{ \left( \sum(x_i - \bar{x}) ^2\right) ^{1/2} \left( \sum(y_i - \bar{y}) ^2\right)^{1/2} }$$

- If $r_{xy} \approx 0$: very little evidence of linear association. 
- If $|r_{xy} \approx 1$: strong evidence of linear association. 
- $-1 \leq r_{xy} \leq 1$. 
- If $y=a+bx_i$, $r_{xy} = 1$ if $b> 0 and $r_{xy} = -1$ if $b< 0
- It is possible that r_{xy} misses the non-linear part of the relationship. 

**Graphical Data Summaries**
Pictorial representation of the data set, to identify its main properties. 

Histogram: 

- data is grouped
- x-axis: data divided into groups
- y-axis: some function of the frequency of that group

Density Histogram (Relative frequency histogram)

- Area of rectangle: relative frequency of that group
- y-axis: density; height is chosen in such a way such that the area of the rectangle is the relative frequency
- Each class needs not be of the same width. 
- The area under the histogram = 1 and we would be able to compare it with knowntheoretical distribution with known desnity function
- It tells us the shape of the r.v. from which the data is drawn. 
- Disadvantages: The shape depends on how the groups were selected. 

Box-Plots

- We use box plots to compare two different data sets. 
- Box and Whiskers plot
- Upper whisker stops at the maximum value of the data set that is less or equal to $Q_3 + 1.5IQR$
- Lower whisker stops at minimum point of data set that is greater or equal to $Q_1 - 1.5IQR$. 
- Anything outside the two whiskers are outliers and are marked individually
- The box-plot gives an idea of the shape of the graph and give the fivenum summary. 

Empirical CDF

- $F(y) = \frac{\textrm{# of obs.} \leq y}{n}$where $n$ is the total number of observations. 
- The graph $(y, F(y))$ is the ECDF graph. 