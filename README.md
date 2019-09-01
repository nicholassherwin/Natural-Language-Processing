# Natural Language Personas - Predicting Personality Through Written Text

---

Project Goal: Classify the big five personality traits of film protagonists through their spoken dialogue. 

---

For the data, we will be utilizing the UCSC Film Corpus 2.0. For this project we will be only covering dialogue instances within the Action/Adventure genre.

---

In addition, we will be investigating the IBM Watson Personality Insights platform to see if we can visualize personality traits and build off existing research for the productized version (more on this below)

The hypothesis for this project is that we can find archetypal consistencies between fictional and nonfictional dialogue that can be mapped to general personality traits (i.e. Big Five Traits). The hope is to utilize these finds as a baseline for a generative narrative delivery currently being developed. 

The overarching idea for this generative delivery can be thought of as essentially the antithesis of the Youtube algorithm. Youtube funnels the user down a path of more and more ‘extreme’ content based on your watch history. A user who watches a video that might have some right-wing tendency (or comments) for example might then be given a video with slightly more right-leaning views and so on. The end result is that the user is entrenched in content from a hyper specific viewpoint. 

For this project, we would like to establish a baseline categorical classification for any given user, marry them to the corresponding ‘fictional’ characterization and expose them to divergent patterns of thinking through a customized narrative delivery. Said another way, we’d like to open up the user to previously unexplored patterns of thinking, to broaden their viewpoint and ultimately help them to break out of established patterns of thought through story.

--- 

Process: (text-classifier / topic modeling) 

Non-Fiction:
Import the corpus
Clean + Preprocess the text
Tokenize
Vectorize Tokens
Reduce Dimensionality 
Cluster Dimensions 

--- 
## Conclusion

We find that while we were not able to cluster by personalities in the Action/Adventure genre, we were able to uncover some insight. Namely, we have uncovered the toxicity of action protagonists. We see many commanding and mysogonist words throughout the corpus, especially in topic 1. 

In addition, we were successfully able to visualize the big five personality traits of any given character utilizing the existing IBM architecture. The findings are in the personality insights notebook.
