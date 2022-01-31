At this point, this file mostly contains the literature I am basing this project on. Will do a real write up once completed.


Jurnals/Refrences:


1. Speech and Language Processing (Book)
https://web.stanford.edu/~jurafsky/slp3/ed3book.pdf
Speech and Language Processing
An Introduction to Natural Language Processing,
Computational Linguistics, and Speech Recognition

1957.  (Firth, J. R. 1957:11)
You shall know a word by the company it keeps (Firth, J. R. 1957:11)
https://annabellelukin.edublogs.org/files/2013/07/Firth_Ethographicanalysis-and-language-wrt-Malinowskis-views-1ta232q.pdf


2012. Improving Word Representations via Global Context and Multiple Word Prototypes
Huang, Eric H., et al. "Improving word representations via global context and multiple word prototypes." Proceedings of the 50th Annual Meeting of the Association for Computational Linguistics (Volume 1: Long Papers). 2012.

2012.  Semantic regularities.
Jurgens, David, et al. "Semeval-2012 task 2: Measuring degrees of relational similarity." * SEM 2012: The First Joint Conference on Lexical and Computational Semantics–Volume 1: Proceedings of the main conference and the shared task, and Volume 2: Proceedings of the Sixth International Workshop on Semantic Evaluation (SemEval 2012).
https://aclanthology.org/S12-1047.pdf
key points - Semantic test
TO DO = Mimick Semantic test

4. Intro to words as vec
Mikolov, Tomáš, Wen-tau Yih, and Geoffrey Zweig. "Linguistic regularities in continuous space word representations." Proceedings of the 2013 conference of the north american chapter of the association for computational linguistics: Human language technologies. 2013.
https://aclanthology.org/N13-1090.pdf
Key points - Proof of concept
    Introduction of “King - Man + Woman = Queen”
    Introduction of Analogy Questions
    Semantic regularities - from Semeval-2012
TO DO - Pull graph
    Minic analogy test


2013. Word2vec
Mikolov, Tomas, et al. "Efficient estimation of word representations in vector space." arXiv preprint arXiv:1301.3781 (2013).
https://arxiv.org/pdf/1301.3781.pdf
https://code.google.com/archive/p/word2vec/

Key points - "Finally, we found that when we train high dimensional word vectors on a large amount of data, the
resulting vectors can be used to answer very subtle semantic relationships between words, such as
a city and the country it belongs to, e.g. France is to Paris as Germany is to Berlin. Word vectors
with such semantic relationships could be used to improve many existing NLP applications, such
as machine translation, information retrieval and question answering systems, and may enable other
future applications yet to be invented.
"


2014. Glove model
Pennington, Jeffrey, Richard Socher, and Christopher D. Manning. "Glove: Global vectors for word representation." Proceedings of the 2014 conference on empirical methods in natural language processing (EMNLP). 2014.


2015. Tan, Liling, Rohit Gupta, and Josef van Genabith. "Usaar-wlv: Hypernym generation with deep neural nets." Proceedings of the 9th international workshop on semantic evaluation (semeval 2015). 2015.
https://aclanthology.org/S15-2155.pdf

2016.  Basically what I want to do, but not sunonyms, 
Leeuwenberg, Artuur, et al. "A minimally supervised approach for synonym extraction with word embeddings." The Prague Bulletin of Mathematical Linguistics 105.1 (2016): 111.
https://ufal.mff.cuni.cz/pbml/105/art-leeuwenberg-et-al.pdf
TO DO - read in more detail
    - Bring relative cosine similarity

2016. 
Bolukbasi, Tolga, et al. "Man is to computer programmer as woman is to homemaker? debiasing word embeddings." Advances in neural information processing systems 29 (2016): 4349-4357.
Git hub - https://github.com/tolga-b/debiaswe
To do - graphs, calculation for the 


2017. Semantics derived automatically from language corpora contain human-like biases
https://purehost.bath.ac.uk/ws/portalfiles/portal/168480066/CaliskanEtAl_authors_full.pdf
TO do - Pull graphs from page 7
    - Figure out the math on how to 

2017. Word embeddings quantify 100 years of gender and ethnic stereotypes
https://arxiv.org/pdf/1711.08412.pdf

2018. Interactive Analysis of Word Vector Embeddings
https://par.nsf.gov/servlets/purl/10064419

2018. How Copyright Law Can Fix Artificial Intelligence's Implicit Bias Problem
https://digitalcommons.law.uw.edu/cgi/viewcontent.cgi?article=5042&context=wlr

2019. 
Swinger, Nathaniel, et al. "What are the biases in my word embedding?." Proceedings of the 2019 AAAI/ACM Conference on AI, Ethics, and Society. 2019.
https://arxiv.org/pdf/1812.08769.pdf


2019. A survery on bias and fairness in ML (2019)
https://arxiv.org/pdf/1908.09635.pdf
Key points - Lists of bias
    list of discrimination


2019. Lipstick on a Pig: Debiasing Methods Cover up Systematic Gender Biases in Word Embeddings But do not Remove Them
https://arxiv.org/abs/1903.03862


2019. Understanding the Origins of Bias in Word Embeddings
Brunet, Marc-Etienne, et al. "Understanding the origins of bias in word embeddings." International Conference on Machine Learning. PMLR, 2019.
https://aclanthology.org/P19-1166.pdf
https://kawine.github.io/blog/nlp/2019/09/23/bias.html
Import infor - RIPA

2019. Attenuating Bias in Word Vectors
https://arxiv.org/pdf/1901.07656.pdf
Looks promising

2019. Assessing Social and Intersectional Biases in Contextualized Word Representations
https://arxiv.org/pdf/1911.01485.pdf

2020. Language (Technology) is Power: A Critical Survey of “Bias” in NLP
https://arxiv.org/pdf/2005.14050.pdf
Import info - 
(Barocas et al., 2017; Crawford, 2017).
Allocational harms arise when an automated system allocates resources (e.g., credit) or  opportunities (e.g., jobs) unfairly to different social groups
representational harms arise when a system (e.g., a search engine) represents some social groups in a less favorable light than others, demeans them, or fails to recognize their existence altogether

2020. Bias in word embeddings
https://dl.acm.org/doi/pdf/10.1145/3351095.3372843

2021. VERB: Visualizing and Interpreting Bias Mitigation Techniques for Word Representations
https://arxiv.org/pdf/2104.02797.pdf#page=10&zoom=100,60,929
https://github.com/tdavislab/verb







Info:
Gibberish-Detector from - https://towardsdatascience.com/5-lesser-known-python-libraries-for-your-next-nlp-project-ff13fc652553

Map of embeddings
https://ruder.io/word-embeddings-1/


Word Analogy Predictor:
https://github.com/naren1991/word-analogies
List of similarities:
https://aclweb.org/aclwiki/Similarity_(State_of_the_art)

Code:
From - https://www.kaggle.com/pierremegret/gensim-word2vec-tutorial
As we do not plan to train the model any further, we are calling init_sims(), which will make the model much more memory-efficient:
w2v_model.init_sims(replace=True)
OVERALL good for spacy 


The dimensions did not seem to play a large role.
The windowsize was ~4 with some improvments for certain subreddits