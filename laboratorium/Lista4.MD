# Task List 4
## Bayesian concept learning

### Knowledge & Skills:
- likelihood
- apriori
- aposteriori
- maximum likelihood estimate
- maximum aposteriori estimate


### Exercises:
 
    Number game rules:
    - program takes number(numbers) and prints selected hypothesis using apropriate method
    - numbers are in range [1-500] (inclusive)
    - hyphotesis space : odd numbers, even numbers, arithmetic sequences ([2,4,6,8,10,12,...], [3,6,9,12,15,...], ..., [40,80,120,160,...], ...)

1. Implement a simple number game based only on the likelihood:
    - the program takes a number or an array of numbers 
    - print likelihood of each possible concept (satisfied by given number/numbers) sorted by likelihood

2. Implement a simple number game based only on the posterior:
    - the program takes an array of numbers and representation of prior probabilities(in any form, ex. lambda function, array etc.)
    - print posterior of each possible concept (satisfied by given number) sorted by posterior

3. Implement a number game:
    - we can specify concepts manually using lambda functions
        - lambda function says if given number is in given concept or not
    - the program accepts input numbers in an array
    - print sorted likelihood and posterior of hypothesis satisfying given numbers
    - use the MAP to select a correct hypothesis

4. Check if MAP converges to ML:
    - create chart:
        - X axis - number of examples (up to whole concept)
        - Y axis - MAP and ML
    - test for 5 different hypothesis 
    - assume some prior probabilities

### Remarks
 - Do not repeat yourself, check if the implementation of one task is also the implementation of others,
 - Do not copy your code, create functions and reuse them
 - (book)[https://github.com/jonesgithub/book-1/blob/master/ML%20Machine%20Learning-A%20Probabilistic%20Perspective.pdf]