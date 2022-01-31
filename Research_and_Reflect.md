Considering how powerful the tools and skills that I am learning and honing are I wanted to do something meaningful for my last project. Because of that, the topic I settled on is echo chambers.
An echo chamber refers to an environment in which beliefs are amplified or reinforced by communication and repetition inside a closed system and insulated from rebuttal.
Can these echo chambers be found and can I quantify an echo chamber metric for these communities?
As you might imagine, this problem might take more than just me working on it for a fortnight.
And therefore I will limit communities to Reddit “subreddits” and second I will focus on a small subset of the problem main. That small subset being word embedding’s.
	Because of the time constraint of this presentation I will lay out my work and findings in a very simplified way.
	To start off, what are word embedding’s?
	They are a mathematical technique where words are changed into numerical vectors, based on the distributional hypothesis.
The distributional hypothesis states that words that occur in the same contexts tend to have similar meanings.*** Or stated another way, “You shall know a word by the company it keeps”.
A vector is just a set of numbers. A one dimensional vector, has 1 number. Dictating where in that dimension, the vector currently resides. It is limited to that dimension, e.i. can only move left to right. A two dimensional vector, has two numbers. A number for the left/right dimension and a number for the back/forwards dimension. A three dimensional vector adds another number for the up/down dimension. A 4th dimensional vector adds a 4th number, not possible for you, but math doesn’t care. 
The actual number of dimensions of the word vectors is 500. Meaning each word is a combination of 500 individual numbers.
The reason we go through all this trouble is that once complete, these vectors are very useful in providing information about the data they were trained on.
The are two characteristics of the vectors which will be important. 
The distance between vectors is correlated to the linguistic similarity of words. The closest vectors are the most similar they are. For example, when calculating the most similar words to from the following comes up: **** https://nlp.stanford.edu/projects/glove/***
The second characteristics of vectors is that the vectors have underlying properties that can be accessed through the use of algebra.
The most famous example being by taking the vector of king, subtracting the vector for man, and adding the vector for woman gives you vector that is very close to the vector for queen. 
Now this generalizes to more relationships not just male/female. A few examples are on screen. 
For example you know the distance between “Canada – Ottawa” you can calculate all other Countries/Capital words pair from either just a Country or just a capital. The vector Canada-Ottawa is = to the vector that you get when subtract any other capital vector from that counties vector.
We can’t see 500 dimensions, but with a little bit of approximation we can squish these 500 dimensions into 2, and generate something like you see on the screen. As you can see, for example the red dots, signifying city words and they are grouped together. Same for the green dots representing body parts.
Usually the usefulness is evaluated in two ways: 1. Extrinsic evaluation, meaning how useful are these vectors when used in another model. This is usually the most important part of the evaluation, as these embedding’s are generally a small part of a bigger model. 
And the second evaluation and the one I wish to focus on is Intrinsic evaluation. The intrinsic evaluation can be done a few ways. You can have the model guess the related word, e.g. (given the word bed, which word is closest: couch, airplane, job).
You can also analogy tests. E.g. (puppy:dog, kitten:?)
One of these analogies was the title of a 2016 paper “Man is to computer programmer as woman is to homemaker?”  The authors were not only able to point out issues with the sexist embedding’s but were able to show that the embedding’s have a “gender” substrate that can be manipulated.
The last concept I wish to introduce is the Word Embedding Association Test.  In a very simplified way, we are going to reduce the dimensions of the embedding again, but this time we have different priorities. Our main goal here is to separate the words from one group in front us and a secondary group behind us. Once separated, the new vectors correspond to the bias of the vector in relation to the two groups. 
For example. In the afformentioned paper the authors were able to link the embeddings to real world data by setting one group to female names and the other to male names. This acted as a gender association.  Using this association in combination with the real-world occupation data, the authors found a strong correlation between the strength of association and ground truth.
The strength of this association was further established in a paper titled “Word embeddings Quantify 100 Years of Gender and Ethnic Stereotypes”. The authors demonstrated that this association can be used on historical data.


