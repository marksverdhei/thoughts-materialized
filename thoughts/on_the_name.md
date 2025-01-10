By Markus Heiervang  

## On the name: Language is the materialization of thoughts    

Artificial intelligence, linguistics, philosophy  

---

Human language is profound, and essential to our humanity. 
It is the most efficient general way of communicating information that we know of, and that we'll ever invent.  
Thought is something that we ourselves have not sufficiently understood. 
But we know that thought exists in multiple forms. 

There are many cognitive tasks that the brain completes within milliseconds.  
Facial recognition, audio identification, odor detection are cognitive tasks completed within milliseconds. 
In most cases, we do not need to reason to solve these tasks. This is called "automaticity".  

The domain in which my main expertise lies is the domain of artificial intelligence.  
My background is specifically in NLP: the field of making computers understand human language and using computation to better undestand language. 
This is relevant because it describes the trajectory that took me to the realization that language as materialization of thought is a useful and somewhat accurate description.  

In the field of linguistics, a popular theory was proposed by Noam Chomsky that describes the underlying cognition that generates human language as something that posesses universal properties of human language.
The term "Universal grammar" was thus coined. 

Why am I bringing this up? 
In the current landscape of AI, words are represented as data discrete data in the sense that a character, token, or word is a 
one-hot encoded vector of some vocabulary, and a text is a sequence of such vectors.

The most advanced, task-performant and general approaches to NLP tasks turn sequences of discrete vectors encoding character sequences into continuous (in theory) vector representations of very high dimensions.  
Language models model language, meaning that it will learn any cognition* necessary to most accurately model the language it is trained on.  
If some component of universal grammar is needed to model any language, language modelling is approximation of universal grammar machines.
I understand it so that there is overwhelming scientific evidence that langugage models benefitfrom transfer learning when utilizing data of sufficient volumes of multiple languages.  
It appears that language similarity plays a role in the number of steps necessary to learn a separate language, something that applies both to AI and humans.
The current evidence might not be as overwhelming on the following hypothesis that I hold, but I hypothesize that for any language that has been invented by human,
a language model of an existing architecture with a sufficient size would exhibit transfer learning when training on the two languages. 

Ilya Sutskever who is considered the brain behind OpenAI by many, formulated "The Deep Learning Hypothesis" as: "Anything a human can do in 0.1 seconds, a big 10-layer neural network can do, too!". 
What are the implications of this claim? It is mathematically proven that a deep neural network with two hidden layers can approximate any function, meaning that if it is true, a big 2-layer nn could also do anything a human brain can do in 0.1 seconds. 
The brain does things during its entire lifespan, wich is can be estimated** to be around 30 years considering every human that has ever died. 
So an average prehistoric brain does 9,467e+9 things that some artificial neural network of two layers could do as there are 9,467e+9 deciseconds in 30 years.  
What I'm trying to say is that if the literal interpretation of the hypothesis is true, an artificial neural network can do everything a human brain can do in theory.  

Maybe you can now see now how this connects to automaticity. Automaticity is compressing cognition steps for problem solving. 
And statistical learning itself is in itself compression as explained in Ilya's "An observation on generalization".
For dynamic problem solving compsite cognition steps are used, and sometimes verbal cognition, or reasoning language.  

Recently, neural language modelling methods have seen improvement by mapping reasoning to a continious representation space, as demonstrated by Meta's Coconut paper and Large Concept Model paper. 
In the LCM paper they lay forth likely empirical evidence that learning to reason in latent space improves multilinguality.
To me, that is a clear argument in favor of both the proposition that language models approximate universal grammar, 
that learning universal grammar can be optimized for more directly than naively predicting next token, and in some sense the existence of universal grammar itself.  

With this context, you might understand why I chose this name, but if not, i will end the piece with these fews sentences:

Human language is materialization of thought.
It is encoding concepts created by the inner workings of a human mind into a discrete space of sound sequences that again are encoded into writing: a discrete space of symbol sequences with the purpose of reconstructing the thought.
This text is materialization of thought, as it is material, both existing as a pattern of light on your screen, but also existing as series of bytes inside a computer.
This is thoguhts, materialized.

---

*you can substitute this word with something else if you think using the term cognition is too presumptous
**estimated by ChatGPT o1