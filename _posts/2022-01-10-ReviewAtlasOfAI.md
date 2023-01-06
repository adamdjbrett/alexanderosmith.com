---
layout: post
title:  "Atlas of AI"
date:   2022-01-10 05:00:00 +0000
image: "theplayground2.jpg"
categories: Review
tags:
  - Blog
  - Book Review
---

## Book Review: *Atlas of AI* by Kate Crawford

I really had high hopes for this book considering the reviews and awards, but even the way the book is framed is a red flag. 

A brief abstract of my complaints are as follows:
- The book's critique of AI is fundamentally the same as any technology defining industrial society.
- Its ethnographic method is disengenious and is misconstrued with tangential factoids about technology.
- It is more a book about convincing us that *computation* (rather than AI) is not "post-industrial," and that book has already been written multiple times over.
- It is theoretically misdirecting and often self-contradicting if not self-refuting.

I will walk through this book linearly:

### Introduction:

Let's define the entirety of AI as stupid, dumb, and mean calculations.

Not only does Crawford never attempt to give a sufficient definition of what an Artificial Intelligence is, she mostly just calls it names. Granted, she loosely ties it to common usages and popular interpretations of how AI has been used, but she never gives it a clear definition or explain broadly how it is different from other kinds of computation. She only uses these straw-person positions of what AI are in order to say we don't need one. This is intentional. It enables a particular perspective of AI that does not have to be very nuanced, and it allows her to make all sorts of arguments without justification. It essentially makes it really easy to read this book and think you learned something about AI when really what you are about to learn is the history of basically every technology invented since the 1800s. This book was praised as being the book of the moment and an instant classic. This book might as well be about the printing press. The arguments of its devastation to society would hold just the same at the time of its industrialization.

### Chapter 1 Earth: 

Mining is bad. Computers use parts that are mined.

Yes, Crawford initiates with an ethnographic style that she had a paid field trip to visit a mining site, yet she never seems to use any ethical ethnographic practices. "I'm here to learn what AI is made from." Okay, but she doesn't use any of the information she got there that she couldn't have gotten from a Google map search and literal hundreds of years of news reports about the hazards and labor issues in mining. As best as I can tell, she doesn't quote a single person from the site, she doesn't help anybody there, and most of her arguments aren't about AI specifically but are about computers we all use everyday. It's almost like this chapter intends to say AI did this when literally the entire world of computing plays a part. Your smartphone is a part of this; heck, ordinary linear regreesion is a part of this. 

The entire chapter (and the book as a whole) is riddled with narrative holes such as connecting all of statistics with eugenics without further explanation or motivation for reason in a chapter about mineral mines. Am I to believe that anyone who computes a t-statistic is connected to a goal of eugenics oriented computation? The author is not clear on this but she certainly wants the reader to uncritically follow that narrative.

### Chapter 2 Labor: 

There's a history of labor exploitation in computation.

Yes. There's a history of labor exploitation. Is this unique to AI? No, it isn't. Why is this a book about AI again? Why are we ignoring more than 200 years of labor literature on this exact subject? However, at least this chapter does give a half-hearted attempt to describe the invisible labor behind so-called "automated" algorithmic work.

### Chapter 3 Data: 

Models often use data abstracted from their origins which carry information we should address.

This is likely the best chapter in the book. For the first time, the author addresses something interesting about machine learning and AI. The authors argument that we use data that are deeply personal to some people (specifically in the use of mug shots used for crime prediction or facial recognition), because it strips those people of their humanity through abstraction and sets a norm of being able to use people's image data without asking them. 

While this argument is obvious, the way in which she makes it doesn't address data itself as the chapter proclaims. Initially it addresses computational models. Otherwise, why not critique the Census while we're at it? Is that not basically the same? No, because according to the author it's not about the data itself (except that the image data make her feel more strongly about this particular case) but it's about dehumanizing modeling techniques. But later, it's not about modeling techniques because it's about the fact that these data contain histories of which models don't account. 

This story is not well unpacked. She cannot argue both models and data are steps after each other in dehumanizing people simultaneously. This argument has two left feet. Crawford's refusal to directly explain how AI is defined and works mechanistically hurts her the most here. Without nuance distinguising how AI is different from other kinds of computation, it's not clear where the problem is. Thus, for the remainder of the book, we talk about government programs without clarity of what was built at a datafied level or at a modelled level, and so a casual reader would have to already know how AI works to actually learn the ethics here. 

This book does not provide the mechanisms for a genuine reflection of our relationship to computation. What practical ethical consideration should I take away from this? Despite critiquing induction/deduction in computation, the implication is to induct that all things about social data trace back to unnecessary and dehumanizing abstractions. Is not this precisely what is being argued against? Automating arguments within an assumed logic and model to the determined ends of that model? Was this book written by an AI?

Jokes aside, all a data scientist can do is say, "Yes, this case is sad," and be educated enough to know that this history isn't determinantly true. But Crawford implies again and again that this determinantly the history of AI and datafication.

### Chapter 4 Classification: 

Ontologies have implications.

Now Crawford turns on the laborer she earlier claimed was exploited, saying that when we use cheap labor to classify stuff, we produce racist outcomes and the degradation of linguistic principles. The author remains conservative to following an epistemology that she doesn't explain about language and classification. This is nothing but an elitist trope that classification experts should do classification since data scientists aren't willing to ethically clean their own datasets. 

While there are good points here about the harms of classification, just read Bowker and Star instead. In direct opposition to Crawford's interpretation, it seems more reasonable to argue,

1. Inductions without critical reflection tend to be problematic;
2. Some people are overtly problematic in their classification;
3. Classification itself is necessarily problematic when dealing with pragmatics organization (See Bowker & Star);
4. There isn't enough labor and financial ability for scientists on minimal budgets to do this work.

Instead, Crawford's policy here is to oppose letting pedestrian people datafy things because they will muddy up your data. This feels elitist about interpreting how MTurkers work, and unfair to researchers who cannot meet publication requirements on their own. It also doesn't account for the argument that researchers muddy their own data all the time, computational data or not. "Expert" checking doesn't solve this on its own. 

That is, Crawford rejects her own labor chapter. Researchers can't work in isolation for most of academia in order to answer the questions posed to them, and the use of crowdsourced data (while problematic and should be addressed more by the standards of the Labor chapter) is not necessarily lesser quality data just because they are unaware of the academic training. If anything, an oppositional reading of this section teaches us that researchers can get better at cleaning crowdsourced data with experience of what to look for or can use that same data for a different purpose related to the biases it contains. Unfortunately, instead of actively looking for ways to continue valuing the labor of our peers, she suggests we induct that all datafication processes using classification are problematic necessities of AI because nobody is looking at datasets they use, which is laughable. While its been described this way, clearly somebody eventually looked at all the datasets Crawford claims weren't looked at because it's those researchers trying to correct these problems that gave her the historical data to write the chapter.

### Chapter 5 Affect: 

Reading people's emotions from their faces is not a science.

While the simple argument here is true: we can't look at a person's face and know their feelings, this chapter badly butchers its theory. Firstly, while her main antagonist, Elkman, actually did attempt to do this and its still used in computational research, the way she frames Tomkins is horrendous. He argues that every body has an affective interpretation, not necessarily that all bodies essentially are the same in how we interpret their affects. Secondly, Tomkins does not fixate on singular human affects as the only individuals of interest. Tomkins is a post-human psychologist. Crawford reduces Affect theory to simple emotions of individuals (as do most communication scholars actually; it's kind of a meme at this point.) In total, this is probably one of the worst readings of Tomkins I've ever seen. There's no "affect theory" here in this interpretation. This is just badly interpreted psychology theory. For anyone who wants to check this out, look up Eve Sedgewick's Tomkins reader _Shame and its Sisters_. For affect theory more broadly, Spinoza's _Ethics_ and Deleuze's work developing Spinoza's affect theory make great starting points also. Even a brief overview from experts in affect should convince you of how badly Crawford misunderstands affect theory.

This chapter should have stopped after describing Elkman's empirical failure to model emotion, and then written a different chapter which had nothing to do with affect theory. This could have been a literature review about the failure to computationally see emotion, and that would have made a significantly better than pretending to understand affect theory. This chapter actively hurts other areas of academia that have almost nothing to do with the computational arguments here, and those areas, contrary to this argument, are way more thoughtful about computation than this. In fact, consider reading Elizabeth Wilson's _Affect and Artificial Intelligence_ instead of this book. It both critiques computational models as they exist today, and attempts to re-read vitalism into early discussions of AI which would improve most of our understanding of what computation can and cannot do. While it might not be quite as accessible as this book, at least it doesn't overtly misuse theory to fear monger. Wilson provides a more ethical and considerate academic work on the subject of affect than this chapter.

### Chapter 6 State: 

Lots of computational tools used to police and track people online are AI tools that create logics to hurt "others" as a part of datafied "precision."

Again, we knew this. She briefly discusses Benjamin Bratton's book, _The Stack_ (which this chapter is merely a summary of), but also _We Are Data_ describes this very carefully. Crawford supposedly, in hacker-like style, had access to all of Snowden's data release and still the best she could do with it was repeat the same arguments others did. Yes, AI is used to track people and occasionally decide to kill them. Yes, this is dehumanizing to reduce humans to numbers. Yes, this is what new nationalist racism looks like. But more could have been said that summarizing the work of others as a part of having pulled a couple of slides from Snowden's files and putting them in a book.

### Conclusion:

This book is simple to interpret because it's written to be devastating and have the sense of absolute completion. While I would like to say that I agree with most of it, half of the stuff that I do agree with isn't new here even though it's written stylistically to look like she's uncovering conspiracies like some Jason Borne-level academic. The other half of stuff that I agree with ties itself to framings that might be more problematic to academic standards and labor ethics. This does not even include that I think that most of this felt really disingenuous. 

The narrative turns from the ethnographic writing style to carefully selected historical tangents you can find on Wikipedia that have nothing to do with the immediate ethnographic framing give me the feeling that I'm not being told the whole truth... and I know I'm not. It's too simple. It's too easy to consume. It makes too many hidden and contradictory assumptions that can be teased out quickly if someone is looking. While I wanted to like this book, its a case of how stuff with AI in the name sells, and it cheapens a lot of the work that others have worked towards on this subject. While someone who isn't trained in this might walk away with a sense of gained knowledge, it doesn't well introduce how critical AI research is being done well. This book seems to shut down interest more than raise it and leave open questions. This is a book that only someone trained in critical communication studies could agree with in summary, but it is condescending to everyone else that it's written for.

This is a book that required a lot more nuance and should have trusted its audience to understand more than the consumable drama and oversimplifications this book narrates. While good things are here, they can only be interpreted with clarity by someone who already knew those things. This is a common problem I've seen in "accessible academia": don't trust the public with the clear and fair investigated truth-claims; trust them instead with patchworked, token truths sewn together with drama.

(NOTE: this review is an update of my Goodreads review of the book.)

[Image Attribution: Alexander O. Smith](/AboutAlexander/) 
