# To-do 13: Poking at Big Data (Yelp)

## Na-Rae the fake student:
- My 5-year-old ThinkPad laptop did ok! It has ... RAM, which worked ok with this much data, etc. Grepping through the whole of xxx json file took...

## Qidu:
My 3-year-old MacBook Air (M1, 2020) did well! It has 8GB of RAM and 55GB of free disk space, 
which handled the processing of smaller datasets efficiently. However, when grepping 
a larger dataset with over 1 million rows, I started to notice spikes in CPU usage, 
memory pressure, and the disk.
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

## Jana's Report
I'm working on a 2020 MacBook with 8GB of RAM, which worked nicely until I tried working with 1,000,000 reviews. That's when it first started taking longer. Using the time keyword to look at the total time from start to finish of the call (enter-command completion), it printed that for 1,000 and 10,000 reviews, it took under 0.6 seconds. When I increased the reviews to a hundred thousand, it increased to 3 seconds, which is not terrible. However, when I tried with the million reviews, it went up to 50s, so it was already practically a minute. After that, I went up to 10,000,000, but it could not handle it. I attempted to go back to 1,050,000 reviews, which took 56s, and then 1,500,000, which took 3 minutes and 21 seconds. That is the largest I decided to go as the memory usage was up to 7.0_ (from the total of 8GB) for most of the whole 3 minutes, reaching up to 7.11GB.\
**Sidenote/Question:** The time command also provides an n% CPU. However, to my surprise, the more data, the lower the percentage. In the beginning, with only 100 reviews, it was 473%. By 1,500,000, it had dropped to 50%. I looked this up, but I didn't understand what this percentage stands for. I'm very curious about it; please let me know if anyone knows!

## Claire's Report
I am currently working on a close to brand new 2024 MacBook Air (M3) with 8 GB of memory. I was able to successfully process the file in increments of 1,000 lines, 10,000 lines, 100,000 lines, and 1,000,000 lines. The only time that my system appeared to struggle with the large size of the file was with the 1,000,000 line file, which took about 20 seconds to process (the other ones sizes processed almost immediately). I kept a close eye on the Activity Monitor, which obviously spiked higher when Terminal was processing the larger versions of the file. I didn't want to try to process anything larger than 1,000,000 lines.
One strategy that I believe might help my computer process a file larger than 1,000,000 lines would be to entirely close out of all other applications, including ones that use a lot of system memory like Safari, Chrome, Spotify, and Microsoft Office applications.
In terms of the Unix tools alone, wc took the longest I believe. I did not have any major issues with any of the Unix tools and was able to achieve all of the tasks outlined in Todo 14 successfully!

## Jenna's Report
I have a Microsoft Surface w/ 15.8 GB usable RAM (16GB installed). I forget when I got it, but it says the Windows Specifications was downloaded 2024-12-03...? but it's definitely older than that because I'm on my second stylus for it and I know I got those as Christmas presents.  
My computer's memory with the current applications open & running hovers around 40%.  
When I was processing 1000000 lines, it hovered at around 90% for most of the time and 70% towards the end. 15% of the CPU was used (14% from bash & file folder, 1% from Task Manager itself, the rest negligible). disk varied from 1-50%. this took **38.255 seconds**.  
... I tried processing 10 mil lines. BAD idea. my memory & disk were at 99% practically the whole time (CPU 35-50%) and then there was a memory error so after waiting like 10 mins I got NOTHING :(  
    OKAY I DID FIVE MIL LET'S GO
    real    24m59.448s
    user    0m0.140s
    sys     0m0.125s
