# Natural Language Personas - Predicting Personality Through Written Text

---

Project Goal: Classify the big five personality traits of film protagonists through their spoken dialogue. 

---

For the data, we will be utilizing the UCSC Film Corpus 2.0. For this project we will be only covering dialogue instances within the Action/Adventure genre.

---

In addition, we will be investigating the IBM Watson Personality Insights platform to see if we can build off this for the productized version (more on this below)

The hypothesis for this project is that we can find archetypal consistencies between fictional and nonfictional dialogue that can be mapped to general personality traits (i.e. Big Five Traits). The hope is to utilize these finds as a baseline for a generative narrative delivery being developed for project 5. 

The overarching idea for project 5 can be thought of as essentially the antithesis of the Youtube algorithm. Youtube funnels the user down a path of more and more ‘extreme’ content based on your watch history. A user who watches a video that might have some right-wing tendency (or comments) for example might then be given a video with slightly more right-leaning views and so on. The end result is that the user is entrenched in content from a hyper specific viewpoint. 

For this project, we would like to establish a baseline categorical classification for any given user, marry them to the corresponding ‘fictional’ characterization and expose them to divergent patterns of thinking through a customized narrative delivery. Said another way, we’d like to open up the user to previously unexplored patterns of thinking, to broaden their viewpoint and ultimately help them to break out of established patterns of thought.

While there exists many psychological and behavioral tests to determine things like depression, addiction or personality etc, we will be using machine learning to stand in for such tests. In other words, rather than give individuals a test that ranks them on some scale, we’ll be using machine learning to classify users based on their online metadata or provided responses. (social media sites etc.) There are two options here:
Users opt in for our finished app to parse through their social media profiles. The algorithm will dynamically read through all their written online text and will categorize them on the backend (the label will not be known to the user)
Users will be given a text box and a prompt to write about themselves in story form. This could be built off of IBM Watson’s personality insights platform and specifically could look something like the demo found here: https://personality-insights-demo.ng.bluemix.net/ 

We will explore the above in more detail at a later time...

In addition to classifying the users based on public profile information, we will utilize the Cornell movie script corpus to classify characters within fictional works. We can capture the overarching classification in a protagonist or work and use this as a baseline for our generative narrative framework in project 5. 

While the findings in this project will dictate the direction for the project 5 narrative delivery, we are working off the framework proposed in Robin Carhill-Harris’ paper on neurological entropy as a function of the DMN (default mode network). Namely that low entropic states indicate an overactive DMN and are characterized by excessive self-rumination and diagnosable markers like depression or OCD. On the other hand, high-entropy states indicate a less active DMN, more openness and inclination toward imagination and possibility.  For the narrative, we would seek to map low entropy personas to low entropy characterizations and move the character in the narrative (and by extension the individual) from low to high throughout the experience resulting in a subtle transformation (or at least perspective shift). 

Along the same lines, we may find more success on the user side to prompt for story rather than a parsing of status updates. For past immersive experiences that have been conducted under Screenshot Productions, we have had users fill out detailed questionnaires that dictated the content of their experiences. For this project, we could have a singular prompt that calls for them to input a story from personal experience into a framework built off IBM’s personality insights to calibrate them for the story. The positives here are two-fold:

We may get a more reliable classification here based on scientific research done at UCSF: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4809527/
We don’t have to obtain users permission in accessing their social media profile. This could be a source of friction for some users (understandably) and we want this to be as inclusive as possible for the audience. 

If we reject the hypothesis and there is no mapping overlapping clusters between the fictional and nonfictional datasets, that is fine. While it surely would be interesting for there to be a mapping between the two, if there is not we can still move forward with project 5. (more on this later...)

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
