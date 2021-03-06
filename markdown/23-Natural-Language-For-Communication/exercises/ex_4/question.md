[Exercise 23.4](ex_4/)

Consider the following simple PCFG for noun phrases:

> 0.6: NP $\rightarrow$ Det\ AdjString\ Noun

> 0.4: NP $\rightarrow$ Det\ NounNounCompound

> 0.5: AdjString $\rightarrow$ Adj\ AdjString

> 0.5: AdjString $\rightarrow$ $\Lambda$

> 1.0: NounNounCompound $\rightarrow$ Noun

> 0.8: Det $\rightarrow$ **the**

> 0.2: Det $\rightarrow$ **a**

> 0.5: Adj $\rightarrow$ **small**

> 0.5: Adj $\rightarrow$ **green**

> 0.6: Noun $\rightarrow$ **village**

> 0.4: Noun $\rightarrow$ **green**

where $\Lambda$ denotes the empty string.

1.  What is the longest NP that can be generated by this grammar? (i)
    three words(ii) four words(iii) infinitely many words

2.  Which of the following have a nonzero probability of being generated
    as complete NPs? (i) a small green village(ii) a green
    green green(iii) a small village green

3.  What is the probability of generating “the green green”?

4.  What types of ambiguity are exhibited by the phrase in (c)?

5.  Given any PCFG and any finite word sequence, is it possible to
    calculate the probability that the sequence was generated by the
    PCFG?
