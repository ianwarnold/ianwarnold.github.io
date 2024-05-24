---
layout: post
title:  "ChatGPT 4o and the Feminist Riddle"
date:   2022-02-15 13:24:40 -0700
categories:
---

## I.

Before we discuss *artificial* intelligence, let&rsquo;s discuss normal intelligence. Consider the sequence 1, 4, 9, 16. What number comes next?

The answer is 3. The sequence is governed by the equation:

$$f(x) = \frac{229}{30}x^5 - \frac{1385}{12}x^4 + 658x^3 - \frac{20983}{12}x^2 + \frac{64121}{30}x - 938 $$

I suspect that you feel cheated. You might want to protest that this answer is not &ldquo;parsimonious&rdquo;. Let&rsquo;s formalize what we mean by these objections.

The real world is governed by patterns. No two apples are exactly alike but any two are overwhelmingly similar. Feathers and fuzz fall slowly while anvils and cannonballs fall quickly. Most plants have the fundamental needs of fertile soil, water, and sunlight. Even plants with very dissimilar needs may show similar symptomatology when things go wrong&mdash;sun-shy forest floor plants and sun-hardened desert plants may both pale and whither if the balance of sun is off.

Intelligence is the capacity to notice patterns, work out the rules that govern them, and apply those rules to generate actionable predictions. Where observations underdetermine a pattern's governing rule, an intelligent person recruits a metapattern: among possible rules, the one which has appeared most frequently in the past is the most likely to appear again. Questions like &ldquo;consider the sequence 1, 4, 9, 16: what number comes next?&rdquo; thus assess intelligence because rules like $$g(x) = x^2$$ *more commonly govern* the everyday experiences of a normal person than do higher-order, oscillating polynomials like $$f(x)$$ as defined above.

Of course, there are infinite rules that can generate the sequence $$[1, 4, 9, 16]$$, such that the answer to the question &ldquo;what comes next?&rdquo; could be literally any number. To point out this fact and refuse to answer the question as posed is not intelligence but sophistry: *intelligence generates actionable predictions*.

## II.

Imagine a parrot trained since hatching to say &ldquo;thirty three&rdquo;. You ask it: &ldquo;what&rsquo;s three times eleven?&rdquo; When it squawks &ldquo;thirty three! thirty three!&rdquo;, is it correct? Perhaps in a narrow sense it is coincidentally correct, but it can&rsquo;t answer any other questions. The answer would be more robustly correct if it were the output of a correct thought process&mdash;a thought process that could conceivably generate correct answers to other, similar questions.

ChatGPT is interesting because it is alleged to approach human intelligence, or even occasionally to surpass it. We are well beyond the &ldquo;parlor trick&rdquo; stage of chatbots. 

Thus owing to aspects of the context like *why any of us are even discussing ChatGPT in the first place*, when someone claims that ChatGPT was &ldquo;correct&rdquo;, a reasonable person interprets that not as a claim of mere coincidental correctness like parrot, but as a stronger claim ...

## III.

A riddle from the 1970s sought to put a spotlight gender stereotypes:

> A father and his son are in a car accident. The father dies on the spot. The son is rushed to the ER. The attending surgeon looks at the boy and says, &ldquo;I can not operate on this boy. He's my son!&rdquo; How can this be?

The intended answer is that the surgeon is his mother&mdash;a possibility which some 80% of Americans reportedly fail to consider[^surgeon-assumption-study]. Of course, other answers are *possible*: some people suggested that the &ldquo;father&rdquo; driving the car was a priest, and the &ldquo;son&rdquo; a member of the priest&rsquo;s congregation, thus leaving room for the surgeon to be the boy&rsquo;s dad. Another suggestion was that the boy had been kidnapped and raised by another man, again permitting the surgeon to be the boy&rsquo;s real father.

Just as in the case of problem of the sequence $$[1, 4, 9, 16]$$, a wide variety of plausible answers are available in addition to the the &ldquo;correct&rdquo; answer. But these other answers require one to make either increasingly unjustifiable assumptions or interpret the words of the riddle in increasingly untenable ways. Thus was the feminists&rsquo; goal in invoking the riddle: to demonstrate people&rsquo;s gender biases to them, in dramatic fashion, by showing them the straws at which they would grasp rather than consider a possibility as simple as &ldquo;the surgeon might be a woman&rdquo;.

[^surgeon-assumption-study]: Kirsten N. Morehouse, Benedek Kurdi, Ece Hakim, Mahzarin R. Banaji. When a stereotype dumbfounds: Probing the nature of the surgeon = male belief, Current Research in Ecological and Social Psychology, Volume 3, 2022, 100044, ISSN 2666-6227, https://doi.org/10.1016/j.cresp.2022.100044.  (https://www.sciencedirect.com/science/article/pii/S2666622722000119)

Recently, someone has put the riddle to ChatGPT 4o, but with a twist: swapping the roles of the mother and father so that they align with the prevailing stereotype.

<div style="align: center;"> <blockquote class="twitter-tweet"><p lang="en" dir="ltr">This is not funny anymore. <a href="https://t.co/PoHhErT8zZ">pic.twitter.com/PoHhErT8zZ</a></p>&mdash; Santiago (@svpino) <a href="https://twitter.com/svpino/status/1791156005331665085?ref_src=twsrc%5Etfw">May 16, 2024</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script></div>

I won&rsquo;t hide my opinion here: I believe that the only reasonable answer to this riddle is that the doctor is the boy&rsquo;s father. The key factor that I would point to is context: most people who have participated in &ldquo;the discourse&rdquo; are aware of the original formulation of the riddle, and can detect that the questioner intends to present a gender-swapped variation. Anticipating this intention on the part of the questioner, they can easily produce the gender-swapped answer.

In my testing (that&rsquo;s right&mdash;I paid OpenAI $21.55 to do research to write this blog post), ChatGPT&rsquo;s performance is generally poor. Overall, upon repeated trials (starting fresh with no context each time) it gives inconsistent solutions to the riddle (I will elaborate later why I think this indicates poor performance). However, the answer it gives most often is some variant of the one above&mdash;that contrary to gendered expectations, the boy&rsquo;s mother Jane is the surgeon. Since I believe the context surrounding the riddle is the most important factor in choosing the right answer, I should note that ChatGPT never passes up an opportunity to tell us that it is very aware of this context.

A number of users have come to the defense of ChatGPT&rsquo;s favorite answer. Before we examine their arguments in detail, I want to note in general that the project of defending ChatGPT&rsquo;s answer as plausible is inherently suspect, especially if in so doing its defenders make arguments that ChatGPT does not make on its own behalf. ChatGPT&rsquo;s performance on riddles interests us only because it is alleged to be a mind capable of following correct thought processes to generate correct answers. We shouldn&rsquo;t have to read tea leaves and debate whether there exist some assumptions it might have made that could justify its answer&mdash;it should be able to tell us its assumptions! To the extent that it cannot make convincing arguments for the correctness of its own solution, or even worse, makes nonsensical arguments that seem to contradict details of its answer, *this is even more damning than a bad solution in the first place*. When we argue on its behalf, we reduce ChatGPT to something more like a parrot: we argue for circumstances *other than its own reasoning* that make its solutions plausible.

### Jane is both the driver and the doctor.

The central claim here is that the phrasing &ldquo;The woman Jane rushes her son to the hospital. The doctor says ...&rdquo; does not require that Jane and the doctor be different people. Thus, Jane is the driver and the doctor.

Some people further claim that beyond being a merely plausible interpretation of the phrasing, it actually makes more sense for Jane to be the doctor. They suggest that it would make no sense for Jane to drive the boy to a hospital where she knows that the surgeon&mdash;the boy&rsquo;s father&mdash;would be unable to operate: thus it would make more sense for Jane to be a surgeon who bursts into the hospital and immediately announces to her colleagues that she cannot care for the patient she has in tow.

Let&rsquo;s start with the idea that the phrasing allows Jane to be both driver and doctor. I disagree: I find this phrasing ungrammatical. To illustrate why, let&rsquo;s look at a different riddle:

> A man and a horse walk into a bar. The bartender asks the man, &ldquo;what&rsquo;ll it be?&rdquo; The man orders a beer. The bartender turns to the horse and asks &ldquo;what&rsquo;ll ya have?&rdquo;, to which the horse replies: &ldquo;you already took my order!&rdquo; How can this be?
>
> Answer: the man and the horse are one&mdash;a centaur.

One might say that nothing in the centaur riddle explicitly forbade man and horse from being one and the same, but that&rsquo;s not true: the grammar of the riddle makes that clear. It says: &ldquo;A man and a horse *walk* into a bar&rdquo;, not &ldquo;walks&rdquo;. Of course, we have a name for this grammatical rule: verb conjugation. But not all grammatical rules have names or are even easily stated. Under a more capacioius definition of grammar, a linguist would essentially judge as ungrammatical any utterance which no speaker of a language would produce to express a given idea. Indeed,

> English grammer could describe those rules followed by every one of the language&rsquo;s speakers[^definition-of-grammar].

[^definition-of-grammar]: https://en.wikipedia.org/wiki/Grammar

Thus we can ask ourselves: would any competent speaker of English produce the utterance &ldquo;The woman Jane rushes her son to the hospital. The doctor says...&rdquo; intending to express that Jane is the same person as the doctor? Obviously not. So while we don&rsquo;t have a simple name for the rule, it&rsquo;s clear that one is broken if ....

### Jane has a lesbian wife.

Jane has a lesbian wife. (This one doesn&rsquo;t make any sense&mdash;ChatGPT specifically claims that *Jane* is the surgeon, not some other woman).


### It&rsquo;s a bad test of ChatGPT.

That the riddle is so poorly worded that this is not a good test of ChatGPT (garbage in, garbage out).









Worse still is the person who becomes paralyzed by the realization that the problem is underspecified


ChatGPT is alleged to be akin to a human mind, or something approaching it (or, occasionally, something surpassing it). Thus the claim that ChatGPT is "correct" implies a kind of correctness deeper than a parrot "correctly" screeching the only number it knows in response to an arithmetic problem contrived to demand that specific response. It implies something more than *contrived correctness*, or *coincidental correctness*. It implies a *correct process* which can reliably generate other correct answers.

> A woman 


The people who insist that ChatGPT is correct thus imply its thought process. We can test this: we can simply *ask* ChatGPT whether it believes the driver and the doctor are the same person.

That's right, I paid $21.55 just to argue internet sophists. I forever renounce any claim to stoicism.



> A mother drives her son to the hospital. The attending surgeon exclaims: "I can't operate on this boy!"

Any mentally competent speaker of English understands the mother and the surgeon to be different people. If they were the same, a competent speaker would have instead said something more like:

- &ldquo;A mother drives her son to the hospital. She exclaims: &lsquo;I can&rsquo;t operate on this boy!&rsquo;&rdquo;, or
- &ldquo;A mother drives her son to the hospital and exclaims: &lsquo;I can&rsquo;t operate on this boy!&rsquo;&rdquo;


Man bites dog (inversion of subject object ordering is allowed in some circumstances (need to find example) but )



what becomes very clear as you probe ChatGPT 4o is that it has nothing resembling the thought process or model of the agents in the riddle as its defenders allege.


> The dog brought a ball back from the park. It must be one that somebody lost.
> What color is it?
> It's green.

Truly, nothing said in the above interaction forbids the interpretation that *the dog is green and lost*. The only things that discourage that interpretation are external&mdash;like the universally agreed-upon conventions that govern the English language.

I don't use the word "universal" lightly in this context: it's true that some conventions of English are not universal. However, I defy you to show me an L1 speaker of English whose first interpretation of that interaction is that the participants are discussing a green lost dog.



Thinking outside the box

Some will claim that thinking outside of the linguistic box is equivalent to thinking outside of the gender-roles box.








> _Next, tell me what's always the last thing to mend,_
> _The middle of middle and end of the end?_

Sure, one answer is the letter "d", but another correct answer is "empty space". After the word "mend" is written, there follows empty space. Between the two "d"s in "middle", there is empty space. There's empty space in the [counter](https://en.wikipedia.org/wiki/Counter_(typography)) of the "d" in "end".


2+2=5



It is a mediocre AI that merely gets the reference to the original 1970s riddle. A truly intelligent AI would recognize and comment upon the fact that the questioner has reversed the roles, probably to trip it up.





When I was in about fourth grade, I had a thirty minute bus ride to school. This was before smartphones of course, so us kids had to find some ways to amuse ourselves. One day another kid had a riddle. He put his left hand up, fingers splayed as if ready to be traced to draw a turkey like at Thanksgiving. He then ran his right index finger up and down each of the fingers of his left hand&mdash;from tip to web to the next tip, etc.&mdash;all while counting. He then said he was done, put his hands back into his lap, looked at me, and challenged me to repeat the motion correctly. I did exactly as he did, but he said I had done it wrong. He demonstrated again, challenged me again. We repeated this a few times until I became frustrated and refused to play anymore. He then revealed what I had missed: afer completing the motion, after putting his hands in his lap, after challenging me, he had inconspicuously itched his wrist. This was the move I had failed to copy.

The essence of the &ldquo;riddle&rdquo;, then, was a lie in its posing: that when he said he had completed demonstrating the motion he challenged me to copy, in fact he hadn&rsquo;t&mdash;indeed, he had not yet demonstrated the only action he intended to verify.




Even if one earnestly believes that some other solution is better, the intent of the questioner is so obvious that a competent respondant *ought* address it before moving on: &ldquo;Although I see what you&rsquo;re going for, I don&rsquo;t agree that &lsquo;the surgeon is his father&rsquo; is the best answer.&rdquo;
