The vanilla Viterbi algorithm is a simple probability based technique to Part of Speech (POS) tagging the words of sentences. However this algorithm is too naïve when it encounters unknown words (i.e. not present in the training set), as it assigns an incorrect tag arbitrarily. This is because, for unknown words, the emission probabilities for all candidate tags are 0, so the algorithm arbitrarily chooses (the first) tag.
Here I would modify the Viterbi algorithm to solve the problem of unknown words using two techniques namely,
- Regular expression based approach
- Modified Viterbi algorithm

I would use python nlkt’s penn treebank dataset for our hands-on analysis.
