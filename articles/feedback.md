
## Effective Feedback

What is effective feedback? How do I get it and more importantly how do I measure it?

This is a blog post about my experiment to answer these questions and the outcomes from it

## Objectives

As a consultant here at [Readify](https://readify.net "readify web site"), personally my tendency on client gigs is to focus on the job at hand, this is beneficial to the them however a lot of the time, from a professional development point of view, a lot of information on my personal performance is lost, unless I'm proactive about it

Unfortunately there's no tried and tested approach to successfully getting feedback, unless we ask :)

Following a recent set of retros I a friend recommended the book ["Measure what matters"](https://www.whatmatters.com/book "Measure what matters book site"), it 

Using this to establish my own personal set of [OKRs](https://en.wikipedia.org/wiki/OKR "Wikipedia OKR article"), I wanted to measure myself against objectives which had come out of prior retro feedback, these were:

* _Influence_
* _Amplifying the team_
* _Servant Leadership_
* _Higher Level Conversations_
* _Confidence_
* _Public Speaking_

and secondly; I wanted to find out the most effective _format_ of obtaining this feedback and being able to benefit from it

<hr/>


## Approach

I wanted to take a two pronged approach, one which had had some real use in the field, which I took inspiration from some previously used methods used internally within [Readify](https://readify.net "readify web site"), the company at which I work. 

The other would be a an exercise called a [Johari window](https://en.wikipedia.org/wiki/Johari_window" Wikipedia Johari window article")

The first consisted of an publicly accessible anonymous office 365 form with seven questions, only two of which were required

The other is a custom developed implementation of the Johari window exercise which I developed during my [professional development perk here at Readify](https://stackoverflow.com/jobs/companies/readify "Readify's Stackoverflow page").

This hadn't had a lot of testing so was more experimental


I wanted to maximise the response of both of these exercises, but prioritise the feedback form as I assumed it had less chance of bugs / failure

During the final week, I compiled an email internally, this was to make sure that there would be no issue with my feedback form going into spam folders, I then forwarded this email to my work email for following up later

I kept the email light and provided a link to the Microsoft Form highlighting the fact that it was anonymous


I then provided a quick explanation that I was also doing a Johari window exercise and would appreciate this being completed too

My expectation was that I wouldn't get a high rate of response the first time round and would need an follow up email

<hr/>

# So ...

I sent the email to fifteen people on the client site, these varied between product owners, UX, testers and developers.

I received ten responses to the Microsoft Form, by default the information it provides is just average time to complete the form, however you can export the responses to Excel which contains timestamps on their completion.

My Johari Window app, posts the response to Amazons S3 service, which also stores a timestamp when the S3 object is stored.

Using these two series of time I was able to compile a line chart using [Googles fantastic chart offering](https://developers.google.com/chart/interactive/docs/gallery/linechart "Google's line chart")

The result gives us an idea of the uptake of the two forms of feedback, from it we can see that if we hadn't sent a follow up email we would have missed out on around sixty percent of the feedback

![alt text](https://s3-ap-southeast-1.amazonaws.com/jamesgoldswain/images/ResponseGraph.png "Responses")

<a href="https://jsfiddle.net/jgoldswain/f2szgxun/13/" target="_blank">JS Fiddle for line chart</a>

In terms of the Johari Window exercise, we can use the results to form a word tree chart, which basically weights the adjectives people identify us with to give us a high level overview

![alt text](https://s3-ap-southeast-1.amazonaws.com/jamesgoldswain/images/WordTree.png "Word Tree")

<a href="https://jsfiddle.net/t2y9guqv" target="_blank">JS Fiddle for word tree</a>

<hr/>

# Outcomes 

### Key results for objectives

Now back to my key objectives;

Some great feedback came out of the forms application, I was able to see that I had met my objectives using evidence of key results from the feedback provided:

### Influence

> he stepped up to influence issues more and showed greater leadership with his peers and the company. This is something that he became much more comfortable with which is great


> James was always willing to help me out or work with me to address issues where we had code conflicts and had to resolve them. He did this even when he could have just pushed his changes and made it my issue instead of our issue or his. This was a good example of his inclusive attitude.


### Higher Level Conversations

>Broaden his profile with a wider range of people and squads. I understand that James is a consultant, however to influence a more broader range of people with his skills would be beneficial.

### Amplifying the team & Servant Leadership

> James would leave his emotions at the door and focus on the problem being discussed, letting logic and his experience do the talking. He allowed space for others to contribute their views and remained respectful.

> He had a steadying influence on the teams he worked in and was happy to help out.

### Confidence

> Earlier on in my time working with him, he seemed happy to keep focused on his work and stay out of the "noise" surrounding the team. However, later on in the engagement, he stepped up to influence issues more and showed greater leadership with his peers and the company. This is something that he became much more comfortable with which is great.

Interestingly, although the Johari window did contain some adjectives such as _confident_ its wasn't surfaced in the responses submitted, by default the exercise uses a standard set of words and it will be worthwhile revisiting this exercise after applying some lessons learnt to it

I feel like for a first run of this experiment I definitely had a huge amount of learnings out of it, I enjoyed pulling the various instruments of feedback and how to measure results and am confident that it will be beneficial going forward 

# Next >>
## Lessons Learnt

### Office form question styles

### Johari

word choices
Additional options

