1. Perform manual tokenization for the following sentences.
* I’m a student.
* He didn’t return Mr. Smith’s book.
* “We have no useful information on whether users are at risk,” said James A. Talcott of Boston’s Dana-Farber Cancer Institute.

2. Assign POS tags to the sentence “They can ﬁsh.” How many valid POS sequences can be assigned? Draw the dependency tree structure of each interpretation.

3. Draw the constituent tree structures of “I saw the man with my telescope. ” and “I saw the man with my wallet.”, respectively. What are the main diﬀerences? Think about the main sources of information that be used to resolve their ambiguities.

4. Assign CCG supertags to the sentence “I saw her duck.” How many dif- ferent sequences can be assigned? Draw the CCG derivation of each. (Note: the lexical category of di-transitive verbs is (*S* *\**N* *P* )*/N* *P/N* *P* , transitive verbs (*S* *\**N* *P* )*/N* *P* and adjectives *N* *P/N* *P* .)

5. What are the similarities and diﬀerences between noun phrase (NP) chunking and named entity recognition?

6. Look up a dictionary for the senses of the words “bank” and “saw”, noting the correlation between senses and POS. The *citation form* of each word in a dictionary is called a **lemma**, which can be diﬀerent from **word** **forms** in a sentence. How many lemmas can have the word form “saw”?

7. What contexts do anotnyms commonly co-occur in? Can you deﬁne some simple regular expressions to mine out antonyms from large-scale text data? 

8. Draw the predicate-argument structures of the sentence “Many went to hicago, and visited John.” How many predicates are there in the sentence? Do the predicate-argument relations form a tree structure over the sentence?Discuss similarities and diﬀerences between predicate-argument structures and dependency tree structures.

9. Draw the logical forms of “Not all of Jason’s classmates like Jason.” and “None of Jason’s classmates like Jason.”, respectively. What are the main diﬀerences? The semantic diﬀerence is called **negation** **scope** ambiguities. NEGATIONSCOPE State the main diﬀerences between anaphora resolution and coreference resolution. 

10. Draw the logical forms of “Not all of Jason’s classmates like Jason.” and “None of Jason’s classmates like Jason.”, respectively. What are the main diﬀerences? The semantic diﬀerence is called **negation** **scope** ambiguities. NEGATION SCOPE 

11. State the main diﬀerences between anaphora resolution and coreference resolution. 

12. Which of the tasks below can beneﬁt from knowledge of POS in an input sentence?

    A. named entity recognition 

    B. discourse segmentation 

    C. morpho-logical analysis 

    D. machine translation

13. Which of the tasks below can beneﬁt from dependency syntax information of input sentences

    A. POS tagging 

    B. named entity recognition 

    C. semantic role labelling 

    D. relation extraction

14. *Open* *domain* *targeted* *sentiment* is the task to monitor a stream of text, detecting named entity mentions and the sentiment polarities towards each mention. Hence it consists of two sub tasks, namely NER and targeted sentiment classiﬁcation. What other tasks can be performed jointly? Discuss the advantage of doing the two tasks jointly as compared to a pipeline  method.

15. Summarisation can be solved using *abstractive* and *extractive* methods. The former synthesises a summary using text generation techniques, while the latter makes a summary from excerpts of the original articles. Think of the relative advantages and challenges of each method.

16. Automatic essay scoring is useful for students. Automatic stock prediction is useful for traders. Can you think of downstream NLP applications that are useful in other areas, such as entertainment?
