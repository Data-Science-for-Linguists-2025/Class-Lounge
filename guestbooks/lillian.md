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

From Lillian: Thank you very much for all your input and feeback! In terms of 'formality', German does have a formaily distinction with the 2sg (du- you-2sg-informal versus Sie-you-2sg-formal), but the formality distinctions are make within the data depedning on where the data was collected. For example, the police reports would be formal while the messages between friends would be informal. This was not a classification/distinction I created myself but more information can be found [here](https://www.linguistik.hu-berlin.de/en/institut-en/professuren-en/rueg/rueg-corpus) under the 'Survey methods' subsections :)

Additionally, the ML audio data is still something I'm working on, and the total number could be identified with the speaker ID, you are correct.

Comments from Jana:
1. The “what to be included in the data frame” section is very clear and helpful. It helped me understand what you will be focusing on and laid out your goals and notebook content really well. Also, on the same line, the subsection “Exploring what kind of data we have and what it consists of”  was a great way to get a sense of what the data you’re working on is like and a very useful and informative summary as a reader of the notebook.  
2. In the jupyter notebook loading the RUEG corpus,  I would probably avoid flushing so much data, as it makes it harder to navigate it.  I also like to look at the data when working with it. Still, I think that, for example, when printing the lemmas out, with only part of the lines, the readers of the notebook can already get the idea of what you were working on and what you did without having such a long output. It just requires a lot of scrolling and might make it harder for us to get the ideas or steps, which are incredibly relevant and so much work on your part. I think it would make it stand out even more. 
3. A dataset I’m working with had both XML and CoNLL formats. I went with the safer option and worked with XML. Your notebook was a great first contact for me on how to work with CoNLL. I did not know everything was tab-separated, and seeing you figure out everything on the “foo” mini subset of the data was great. Also, I was unaware that Spacy had a CoNLL parser, which is good to know, as we’ve seen this is a very common format. 

From Lillian: Thank you very much for visiting my project and I really appreciate your feedback! Thank you for letting me know how the notebook looks on your end, as on my end it doesn't look like I'm flashing a lot but I must have different settings than what is seen on viewers' ends!

Ashley:
This is a very cool idea! I'm super interested in seeing how it pans out. I think your project plan & main question are well-defined (something I had a heck of a time with)
and your progress report file is detailed. I know what you mean about feeling like you didn't have much to show for the second report because it was all behind the scenes, mine was too. 

Your notebooks are gorgeous! Super organized and super informative, good comments. I did a bunch of headers in mine but not a linked table of contents at the top, so I'm stealing that from you.

Looks like you really had your work cut out for you when it came to parsing and getting your data to a point you can work with, but you did a good job!
Really interested in seeing what results come out of your work :)
