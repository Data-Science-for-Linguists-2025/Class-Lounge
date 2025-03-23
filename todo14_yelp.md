# To-do 13: Poking at Big Data (Yelp)

## Na-Rae the fake student:
- My 5-year-old ThinkPad laptop did ok! It has ... RAM, which worked ok with this much data, etc. Grepping through the whole of xxx json file took...

## Ashley's report
I'm working on a Windows PC with 24GB of RAM (video games are very demanding). It was built in 2018 but has had upgrades since then.
process_reviews.py worked pretty easily on up to 100,000 reviews. Memory usage barely increased and results took only seconds to print.
The results looked a lot like what we've come to expect, lots of function words. I noted punctuation was not tokenized. 
There was a noticeable slowing down at 200,000 reviews and even more at 500,000.
a million reviews moved my memory usade to 19+GB and I stopped there

wc on yelp_academic_dataset_reviews took 20-25 seconds to process and print. 
Using grep piped to wc -l on the full reviews dataset took 5-10 seconds only and CPU usage didn't increase too much
