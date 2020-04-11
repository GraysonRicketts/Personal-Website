---
title: "Personal Metrics"
date: 2020-04-05T19:15:48-05:00
draft: false
---

Is there something you can do that will make you twice as good at your job? What about more than twice as good? What about just better? There is an innate part of us that strives to improve. This is my story of trying to use metrics to improve. 

The ultimate goal was to find some combination of behaviors that made a day the best day it could be (or made a bad day bad). For example, did I need at least 9 hours of sleep to be happy or did I need between 100 - 150mg of caffeine a day to get the most done? 

First, I needed to figure out what specifically I was going to improve and how I was going to measure it. I’m a software engineer and I knew others in my field had tried to measure improvement through lines of code, PRs submitted, tickets completed, features released, code churn ratio, or other empirical measures. I looked at these measurements and could see they were too granular and could easily not capture improvement -- life and work were more complex than one or two of those measurements. Instead of a bad empirical measure I used my subjective gut feeling to measure. I asked myself certain questions (Was I productive? How was my mood? Was I motivated? etc.) and answered very bad, bad, okay, good, or very good then used those answers as my “empiric” guide to answer the question, “was I improving?”

Next I needed a behavior that would change so I could see if my productivity or some other measure changed when the behavior changed. The easiest behaviors to measure were caffeine, sleep, diet, number of meetings but I tried a couple of others too. Twice everyday I'd enter all the different pieces of data into a spreadsheet. 

There are some cool trends and interesting numbers, but ultimately this is what I found: no behavior I measured significantly impacted my performance, and the subjective measurements for what makes a day “good” swung up-and-down together.

## Data and analysis
### "Factors": Progress, quality, mood, motivation
I started off this whole thing with a statement: I want to be very productive 80% of work days. Some people set a goal of running a 4 minute-mile or squatting 500lbs. I wanted to be productive. 

Let's start looking at the numbers! Note it was a 1-5 scale where 1 = very bad, 3 = okay, 5 = very good.

>    progress: 3.62 / 5 (150 days tracked)
>
>    quality: 3.79 / 5 (167 days tracked)
>
>    mood: 3.63 / 5 (147 days tracked)
>
>    stress: 3.96 / 5 (137 days tracked)
>
>    motivation: 3.45 / 5 (128 days tracked)
>
>    focus: 3.51 / 5 (113 days tracked)

Respectable numbers but not top-notch stuff. However averages always hide things.

![progress distribution](/progress-dist.png)
Here and in the other metric graphs there is a left tail, which is nice to see; means some bad days but higher density on the right so the average is skewed. Also, all the distributions and over-time graphs for these measures all look the same. Which seems to indicate a possible correlation...

![correlation plot](/correlation-plot.png)
The filet mignon of this project. What is correlated with each other?! And now we get back to one of the biggest findings I had. **Most likely, what made a good day wasn't related to any measurable behavior but was simply about how I felt (e.g. motivated, happy, stressed).** Here are the corrleations that were >= 0.75.

> progress-mood (0.88)
>
> mood-stress (0.8)
>
> mood-motivation (0.75)
>
> stress-motivation (0.82)
>
> motivation-focus (0.81)


### Caffeine
I was at about five cups of coffee a day, then quit caffeine for a while, then went to only tea. It was an interesting Goldilocks experience: I had too much, then too little, then found the sweet spot. A cool little visualization of a personal experiment I ran. Also, interesting because it had no large correlation with anything. Closest it came to correlating with anything was 0.47, so maybe there is something there but nothing definitive.
![cafeine over time](/caffeine-over-time.png)

### The "Good day" checkbox / observer effect
Around the start of 2020 I added my favorite metric. "Good day" was a yes or no answer to “did I have a good day”? It’s my favorite metric because measuring it had an effect. A big effect! If I was having a bad day and I had the possibility of leaving that checkbox empty, I felt an intense drive to do things to make the rest of the day good. [The act of measuring changed my behavior](https://en.wikipedia.org/wiki/Hawthorne_effect). 

It changed the way I looked at things and my internal narrative -- I’d tell myself that even though I had a headache all day it wasn't so bad since blah blah happened, or I’d be stressed out so I would take a rest day watching YouTube rather than workout. I loved that checkbox because it drew my attention to if I was maybe being a little crabby or unappreciative. It made me aware I had control to shape my happiness through internal dialogue and responsive external action.

## Results
1. Software engineering "productivity" and "improvement" are not empirical quantities that are measurable.

If I was happy I was “productive”. If I was not happy I was not “productive”. What truly was productive? I don’t know but am almost certain my general mood will swing with how productive I feel.

2. Fun

Nothing tangible came out of this endeavour, but It was fun to try. From the outset I was skeptical I’d achieve anything, but thinking about new metrics to observe and behaviors I could measure then tweak was fun! Analyzing the results and seeing cool trends was fun! Seeing how my behavior changed when I was truly aware of a specific feeling was fun! 

3. One less

I was watching *National Treasure* with some friends when a section of dialogue caught my attention (and not because of Nicholas Cage’s fantastic acting).

>   Ben: You know, Thomas Edison tried and failed nearly 2,000 times to develop the carbonized cotton-thread filament for the incandescent light bulb.
>
>   Riley: Edison?
>
>   Ben: And when asked about it, he said "I didn't fail; I found out 2,000 ways how not to make a light bulb," but he only needed one way to make it work.

Silly movie; oddly wise quote. A bit of wisdom that can be applied to this project. 

Someone could look at this project as a failure; I did not find any ways to improve and I came out more uncertain about the prospects of scientifically determining a way to improve in my career. However, I do not see it as a failure. Now I know one more way I'm not going to improve. 


##### Reference
* [You can see all of my investigation, analysis, notes, and the data on my GitHub](https://github.com/GraysonRicketts/Personal-Metrics)