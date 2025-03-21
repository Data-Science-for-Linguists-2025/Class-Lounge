# German and English Mono- and Bilingual Language Analysis Guest Book
[linked here :)](https://github.com/Data-Science-for-Linguists-2025/DEU-ENG-Mono-and-Billingual-Speakers)
#### Contact Information: 
Lillian Carlson
lkc43@pitt.edu
Pittsburgh, PA

Welcome to my analysis of mono- and bilingual speakers of German and English!! Stay a while and leave a note :)

comments from jenna :o (lillian!! I beat you here!! smh)
1. you found a great variety of data 
2. explain what you mean by 'formality' (as far as I know, German doesn't have a "formal" speech like japanese's honorific speech or french's tu/vous distinction with 2PL)
3. idk if there's anything in particular that I've learned yet since this is just data colection
other comments:
- how do you plan on doing the ML with audio data? (jbc we haven't gone over how to use audio data in class)
- btw there's a typo in [LoadingREUGData.ipynb](https://github.com/Data-Science-for-Linguists-2025/DEU-ENG-Mono-and-Billingual-Speakers/blob/main/LoadingRUEGData.ipynb) where it says 'langauge'
- if you have the speaker ID, could you calculate the true number of mono/bilingual speakers present in the data?

Comments from Jana:
1. The “what to be included in the data frame” section is very clear and helpful. It helped me understand what you will be focusing on and laid out your goals and notebook content really well. Also, on the same line, the subsection “Exploring what kind of data we have and what it consists of”  was a great way to get a sense of what the data you’re working on is like and a very useful and informative summary as a reader of the notebook.  
2. In the jupyter notebook loading the RUEG corpus,  I would probably avoid flushing so much data, as it makes it harder to navigate it.  I also like to look at the data when working with it. Still, I think that, for example, when printing the lemmas out, with only part of the lines, the readers of the notebook can already get the idea of what you were working on and what you did without having such a long output. It just requires a lot of scrolling and might make it harder for us to get the ideas or steps, which are incredibly relevant and so much work on your part. I think it would make it stand out even more. 
3. A dataset I’m working with had both XML and CoNLL formats. I went with the safer option and worked with XML. Your notebook was a great first contact for me on how to work with CoNLL. I did not know everything was tab-separated, and seeing you figure out everything on the “foo” mini subset of the data was great. Also, I was unaware that Spacy had a CoNLL parser, which is good to know, as we’ve seen this is a very common format. 