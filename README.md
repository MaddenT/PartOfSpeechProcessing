# Part of Speech Tagging

## What is Part of Speech Tagging?
In corpus linguistics, part-of-speech tagging (POS tagging or PoS tagging or POST) is the process of marking up a word in a text(corpus) as corresponding to a particular part of speech, based on both its definition and its context — i.e., its relationship with adjacent and related words in a phrase, sentence, or paragraph. [According to the Part-of-speech tagging Wikipedia page.](https://en.wikipedia.org/wiki/Part-of-speech_tagging)

## What uses does Part of Speech Tagging have?
POST has a varity of uses including, but not limited to:

  -Text to Speech.  POS is used to distinguish between words spelled the same, but pronouced different.  i.e: the word refUSE(the verb      that means to deny) is pronouced differently than the word REFuse(the noun meaning garbage). 
  
  -Corpus(Text) Generation.  Corpus Generators that do not use POS exist, however, the text generated by them is often nonsensical and     grammerly incorrect(r/subredditsimulator is a good example of one of these).  By using Part of Speech Tagging grammatical errors can     be corrected, potentially increasing readability as well as decreasing the chance of output being word salad.
  
## Potential Algorithms used with POST

  -Implementing a Hidden Markov Model w/ Viterbi Algorithm
  
  -Implementing a Hidden Markov Model w/ Baum-Welch Alogrithm
  
  -Brill Tagger(Rules-based Algorithm)
  
  -Inside-Outside Algorithm(not too commonly talked about from what I could tell, but this might also be more impressive to try)
  
  -Any other suggested/found algorithms
  
## Project Ideas with POST

### Corpus(text) Generator
Pros:

  -Once POST algorithms are in place generating text from them is rather simple
  
  -Easy criteria to determine how effective certain algorithms are.
  
Cons: 

  -Not particurarily original
  
  -Algorithms might be somewhat impressive, but application is a bit lackluster

Potential Criteria for Determining Effectiveness:

  -Efficiency/Time taken to run(Big-O)
  
  -Usage of Computational Resources
  
  -Percentage of sentences that follow proper grammar rules
  
  -Percentage of sentences that aren't word salad
  
### Mad Libs Generator
Pros:

  -More original than a simple corpus generator but most likely not too much more complicated
  
  -Would showcase the ability to learn grammer structures by being able to leave a blank at a proper spot and request the correct part      of speech to fill that spot.
  
  -Could continue learning new words by adding words entered into the program to the dataset.
  
Cons: 

  -More original than a general corpus generator, but no guarantees that Dr. Tag would like it.
  
  -Even if generated text makes sense in one sentence, often times the next sentence has nothing to do with the previous one.       
  Some constraints on subject and other parts of speech might be necessary to optimize paragraph generation.
  
Potential Criteria for Determining Effectiveness:

  -Efficiency/Time taken to run(Big-O)
  
  -Usage of Computational Resources
  
  -Percentage of sentences that follow proper grammar rules/place blanks in correct spots with part of speech label that makes sense
  
  -Percentage of sentences that aren't word salad
  
  ## Resources
  
  https://hackernoon.com/from-what-is-a-markov-model-to-here-is-how-markov-models-work-1ac5f4629b71
  
  https://medium.freecodecamp.org/an-introduction-to-part-of-speech-tagging-and-the-hidden-markov-model-953d45338f24
  
  https://medium.freecodecamp.org/a-deep-dive-into-part-of-speech-tagging-using-viterbi-algorithm-17c8de32e8bc
  
  https://nlp.stanford.edu/~wcmac/papers/20050421-smoothing-tutorial.pdf
  
  http://www.cs.jhu.edu/~langmea/resources/lecture_notes/hidden_markov_models.pdf
  
  [Info on Viterbi/Buam-Weltch as it applies to HMM POST](http://pages.cs.wisc.edu/~jerryzhu/cs769/HMM.pdf)
  
  [More info on Viterbi HMM POST](http://www.cs.columbia.edu/~mcollins/hmms-spring2013.pdf)
  
  [Info on Inside-Outside Algorithm](https://courses.cs.washington.edu/courses/cse599d1/16sp/lari-young-90.pdf)
  
  [Really good info on Brill Tagger w/ pseudo-code](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.60.8670&rep=rep1&type=pdf)
  
  [More Info on Brill Tagger](http://stp.lingfil.uu.se/~bea/publ/megyesi-BrillsPoSTagger.pdf)
  
  
