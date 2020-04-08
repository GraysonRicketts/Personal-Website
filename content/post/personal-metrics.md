---
title: "Personal Metrics"
date: 2020-04-05T19:15:48-05:00
draft: true
---

Is there something that will make you twice as good as a software engineer? What about more than twice as good? What about just better? There is an inate part of us that strives to improve. Can we improve parts of our life by using numbers like an athlete or weightlifter do? I tried to.

Everday I'd enter different pieces of data (e.g. was I productive? how much caffeine did I drink? how much did I sleep? how many meetings did I have? etc.). There are some charts and numbers below that go through all the data I collected. There are some cool trends and interesting numbers, but ultimately this is what I found: I didn't know what "improve" means and most of "doing well" was likely mood.

## "Factors": Progress, quality, mood, motivation
I started off this whole thing with a statement: I want to be very productive 80% of work days. Some people set a goal of 4 minute mile or to squat 500lbs. I wanted to be productive. Turns out software productivity is not a weight or time! It's harder to measure, there are conflating factors, what's productive to me isn't productive to you. Many people have stumbled upon this and too had to fail to find out my career (luckily) is not as easily measurable as an assembly line workers. Still, let's look at the numbers -- in the end there's an intersting finding.

> Daily averages
>	progress: 3.62 / 5 (150 days tracked)
>	quality: 3.79 / 5 (167 days tracked)
>	mood: 3.63 / 5 (147 days tracked)
>	stress: 3.96 / 5 (137 days tracked)
>	motivation: 3.45 / 5 (128 days tracked)
>	focus: 3.51 / 5 (113 days tracked)
In this 1 was "very bad" and 5 was "very good". Respectable numbers but not top-notch stuff. However averages always hide things.

![progress distribution](/static/progress-dist.png)
Left tail which is nice to see. Means some bad days but higher density on the right so the average is squeawed.

1[correlation plot](/static/correlation-plot.png)
Oh boy! The filet mignon of this project. what is correlated with each other?! And now we get back to one of the biggest findings I had. Most likely what made a "productive" day wasn't what I got done but how I felt (e.g. motivated, happy, stressed).

> Correlations > 0.75
> -------------------
> progress-mood (0.88)
> mood-stress (0.8)
> mood-motivation (0.75)
> stress-motivation (0.82)
> motivation-focus (0.81)


## Time spent working
I like working. I get bored and feel more like a person of action than reflection. How does that feeling match reality? My average hours worked (during a typical work-week) was 41.25. Not crazy. Not lazy. But there's more to it.

![hours worked over time](/static/hw-over-time.png)
Notice peaks followed by throughs and the pre-Christmas slump.

![hours distribution](/static/hs-count.png)
More interesting! I tended to work more over 8 hours a day, but when I didn't work a full day I really didn't work a full day.

I also worked some weekends (not just work, mostly side-projects). Honestly I was surprised the numbers weren't higher. Maybe they seemed like more since it felt odd to work not Mon-Fri.
> Percent of weekend days worked: 37.7%
![weekend hours distribution](/static/weekend-hours.png)

## Caffeine
I was at about five cups of coffee a day, then quit cafeine for a while, then went to only tea. Was an interesting Goldilock's experience: I had too much, then tore away, then found the sweet spot. A cool little visualization of a ![personal experiment](/post/experiments.html) I ran.
![cafeine over time](/static/cafeine-over-time.png)

## the "Good day" checkbox
Around the start of 2020 I added a simple binary field to my spreadsheet. "Good day" was a yes or no, did I have a good day? This was most surprising by the _effect_ not the measure it had. Somedays I found I MADE myself have a good day. It changed the way I looked at things: that meeting wasn't so bad, I had a nice walk back from work after a stressful day, workout sucked but told some funny jokes before a meeting. I loved that checkbox not becuase of what it measure but because it drew my attention to if I was maybe being a little crabby or un-apprectiative.

# Conclusion
1. "Productivity" and "improvement" are not empirical quantities that are measurable. 

Even if you find something that is measurable (e.g. caffeine, calories, weight, hours worked, sleep a night) determing if it made a difference is hard because the effect is often unmeasurable.

2. It was fun

Self explanatory. It was fun to try. From the outset I was skeptical and it just built and built as things went along. But it was fun. When it stopped being fun I stopped, wrote this up, and have an interesting perspective.

Before writing this I watched *National Treasure* with some friends. As awful as that movie is there was this bit of dialogue that struck me.

>   Ben: You know, Thomas Edison tried and failed nearly 2,000 times to develop the carbonized cotton-thread filament for the incandescent light bulb.
>   Riley: Edison?
>   Ben: And when asked about it, he said "I didn't fail; I found out 2,000 ways how not to make a light bulb," but he only needed one way to make it work. [sets down a book in front of Riley] The Preservation Room. Enjoy. Go ahead. Do you know what the preservation room is for?

Silly movie; oddly wise quote. This project could be looked at as a failure. I did not find any ways to improve and came out more uncertain about the prospects of scientifically determining a way to improve in my career. However, I don't look at it that way.

Now I know I can't measure my way to improvement, but I know there is still a lot I can do to improve. Now I know one way I'm not going to try again in the future.