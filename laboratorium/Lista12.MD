# Task List 12
##  Hidden Markov models (HMM) - learning

### Knowledge & Skills:

 - HMM
 - Viterbi algorithm

### Exercises:

1. Use already implemented HMM representation
2. Use already implemented Viterbi algorithm
3. Prepare training data (sequences of symbols [AABBCC, ABCDE etc.], find existing dataset)
4. Implement Viterbi learning:
	- iterate until changes > epsilon
	- compute Viterbi paths for given data
	- update transition/emission matrices according to frequencies from Viterbi paths
5. Test trained model providing data with noise:
	- for symbols randomly change symbols and check if hidden states are same
	- for existing data use train/test split

### Remarks
 - Do not repeat yourself, check if the implementation of one task is also the implementation of others,
 - Do not copy your code, create functions and reuse them
 - Use env that will help you solve problems not create new ones in given task
 - [YT](https://www.youtube.com/watch?v=7tN5Ngf4iJE)
 - [PDF](http://www.cs.columbia.edu/4761/notes07/chapter4.3-HMM.pdf)
 - [PDF](https://ocw.mit.edu/courses/electrical-engineering-and-computer-science/6-047-computational-biology-fall-2015/lectures_slides/MIT6_047F15_Lecture05.pdf)
 - [PDF NLP](http://www.phontron.com/slides/nlp-programming-en-04-hmm.pdf)