### Discrete Uniform Distribution
The discrete uniform distribution is a distribution that assigns equal probability to all integers between two specified values \(a\) and \(b\). 

#### Formula
\[ P(X=x) = \frac{1}{b-a+1} \]

### Bernoulli Distribution
The Bernoulli distribution is a discrete distribution with only two possible outcomes, usually coded as 0 and 1. It is parameterized by \(p\), the probability of success (1).

#### Formula
\[ P(X=x) = 
  \begin{cases} 
   p & \text{if } x = 1 \\
   1-p & \text{if } x = 0 
  \end{cases}
\]

### Binomial Distribution
The binomial distribution represents the number of successes in a fixed number of independent Bernoulli trials.

#### Formula
\[ P(X=k) = \binom{n}{k} p^k (1-p)^{n-k} \]

### Poisson Distribution
The Poisson distribution models the number of events occurring within a fixed interval of time or space.

#### Formula
\[ P(X=k) = \frac{\lambda^k e^{-\lambda}}{k!} \]

### Geometric Distribution
The geometric distribution models the number of trials until the first success in a sequence of independent Bernoulli trials.

#### Formula
\[ P(X=k) = (1-p)^{k-1} p \]

### Continuous Uniform Distribution
The continuous uniform distribution assigns equal probability to all points in the interval \([a, b]\).

#### Formula
\[ f(x) = \frac{1}{b-a} \]

### Normal Distribution
The normal distribution is a continuous distribution characterized by its mean \(\mu\) and standard deviation \(\sigma\).

#### Formula
\[ f(x) = \frac{1}{\sigma \sqrt{2\pi}} e^{-\frac{(x-\mu)^2}{2\sigma^2}} \]

### Exponential Distribution
The exponential distribution models the time between events in a Poisson process.

#### Formula
\[ f(x; \lambda) = \lambda e^{-\lambda x} \]

### Chi-Square (K2) Distribution
The chi-square distribution is a special case of the gamma distribution, often used in hypothesis testing.

#### Formula
\[ f(x; k) = \frac{1}{2^{k/2} \Gamma(k/2)} x^{(k/2)-1} e^{-x/2} \]

### Gamma Distribution
The gamma distribution generalizes the exponential distribution with shape parameter \(k\) and scale parameter \(\theta\).

#### Formula
\[ f(x; k, \theta) = \frac{x^{k-1} e^{-x/\theta}}{\theta^k \Gamma(k)} \]

