## Problem Ideas

### PageRank

### Linear Regression

### Gradient Descent

### Polynomial Regression

### Logistic Regression

Derive cross-entropy loss. Given a distribution $p$, what is the best way to encode it into bits?
Example with two flips of a coin. If the coin is fair, what's the best way to encode the outcome?
If the coin is biased, how does that change the encoding?

What is the expected number of bits to encode the outcomes?

Now suppose I don't know the distribution $p$ exactly, and I instead attempt to approximate it with a distribution $q$.
What is the expected number of bits to encode the outcomes if I used the encoding scheme for $q$ instead of $p$?

When we do use cross-entropy as a loss function for classification, we are minimizing the expected number of bits needed to encode the outcomes using the encoding scheme for $q$.
Why do we use the encoding of the approximation $q$ instead of the true distribution $p$ in practice?


