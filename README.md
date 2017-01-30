# pattern_count

This program counts the frequency of a given pattern in a genome. 


# frequent_words

The function frequentWords() creates the algorithm for finding the most frequent k-mers in a DNA string.
The complexity of this algorith is O(n^2*k), where n is the length of the text.

The function fasterFrequentWords() performs the same job but increases performance.

The function patternToNumber() and patternToNumber2() solves the same problem, where they transform a k-mer pattern into an integer, which is the index of the pattern in the frequency array. The frequency array orders all 4^k k-mers lexicographically. The difference between the two functions is patternToNumber2() uses recursion.


# reverse_complement_string

The function reverseComplementString() finds the reverse complement of a DNA string.


# pattern_match

The function patternMatch() takes the two strings, pattern and genome, and returns a collection of space-separted integers specifying all starting positions where pattern appears as a substring of genome.

# clump_finding

The function clumpFinding() outpus all distinct k-mers forming (L,t)-clumps in a genome, where L is the length of ori in the genome. A k-mer pattern forms an (L,t)-clump inside a genome if there is an interval of genome of length L in which this k-mer appears at least t times. The input is a string genome, and integers k, L, and t. A clump is also sometimes called a cluster.