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

## Sara's report
I'm using an HP laptop with a 12th Gen Intel Core processor, 16GB RAM. It came with 1TB of storage and currently has 676 GB free. I bought this in 2023 when my previous laptop up and died on me (RIP). 
Doing wc -l piped through the full dataset took a minute or so, but it was fine. 
The script worked pretty fast up through 100,000 reviews. I went straight up to 1,000,000 reviews and that took a minute, with my memory going up to 96% usage. I went back to 500,000 reviews, which also took a minute. My memory only went up to 75% usage though. I feel like pushing it beyond 1,000,000 might be stretching it, this is technically an ultrabook. I feel like this computer did well! I don't do a ton of computationally intensive things on it, I play large games on a separate gaming laptop, so I don't tend to monitor the memory much. 
Processing the full dataset would probably take more RAM, maybe a gaming laptop could do it. Doing machine learning on a dataset this large would probably require a desktop computer or remote computing space. 

## Lillian's Report
I'm on a 2023 MacBook with a that has 8BG of RAM (very puny I know :/ ). I have about 6-7 GB used passively (no it's not a virus, Apple is just greedy and uses most of my memory for it's own system and I hate it)
I was able to handle using process_reviews.py with up to 1,000,000 reviews and that certainly took a minute or two and my memory usage skyrocketed up to use most of my memory. I tried 10,000,000 for laughs and it absolutely could not handle it and it even took a while to force quit. I didn't try any more than that because my computer was already having a rough time. 
It would take a lot more memory than I currently have (although that doesn't say a whole lot). And if you wanted it done in a reasonable time, I could imagine it taking porbably 32GB+. It would require even more than that if you wanted to do anything more intense (I'm shivering thinking about building some sort of SVC model with this dataset).
It also did not take long to download at all. It only took about 2 minutes, but I'm also at my boyfriend's apartment and he has much better wifi than I do at my dorm.