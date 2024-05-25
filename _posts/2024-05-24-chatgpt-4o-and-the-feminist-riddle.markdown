---
layout: post
title:  "ChatGPT 4o and the Feminist Riddle"
date:   2024-05-24 19:32:25 +0600
categories:
---

## I.

Before we discuss *artificial* intelligence, let&rsquo;s discuss normal intelligence. Consider the sequence 1, 4, 9, 16. What number comes next?

The answer is 3. The sequence is governed by the equation:

$$f(x) = \frac{229}{30}x^5 - \frac{1385}{12}x^4 + 658x^3 - \frac{20983}{12}x^2 + \frac{64121}{30}x - 938 $$

I suspect that you feel cheated. You might want to protest that this answer is not &ldquo;parsimonious&rdquo;. Let&rsquo;s formalize what we mean by these objections.

The real world is governed by patterns. No two apples are exactly alike but any two more closely resemble each other than either does a V6 engine, for example. Your past experience with apples allows you to generate predictions of the properties that a novel, unfamiliar apple is likely to have. That inferential process is an example of intelligence in action.

Intelligence is the capacity to notice patterns, work out the rules that govern them, and apply those rules to generate accurate and actionable predictions. Where observations underdetermine a pattern's governing rule, an intelligent person recruits a learned metapattern: among possible rules, the one which has applied most often in the past is the most likely to apply again. Questions like &ldquo;consider the sequence 1, 4, 9, 16: what number comes next?&rdquo; thus assess intelligence because rules like $$g(x) = x^2$$ *more commonly govern* the everyday experiences of a normal person than do higher-order, oscillating polynomials like $$f(x)$$ as defined above. This gets at what we mean by &ldquo;parsimonious&rdquo;&mdash;absent more observations which discount $$g(x)$$, one is not justified in passing it over to instead model the sequence using a more seldom observed rule like $$f(x)$$ and predicting the next item will be 3.

Of course, there are infinite rules that can generate the sequence $$[1, 4, 9, 16]$$, such that the answer to the question &ldquo;what comes next?&rdquo; could be literally any number. To point out this fact and refuse to answer the question as posed is not intelligence but sophistry: *intelligence generates predictions*.

## II.

A riddle from the 1970s sought to put a spotlight on gender stereotypes:

> A father and his son are in a car accident. The father dies on the spot. The son is rushed to the ER. The attending surgeon looks at the boy and says, &ldquo;I can&rsquo;t operate on this boy. He's my son!&rdquo; How can this be?

The intended answer is that the surgeon is his mother&mdash;a possibility which some 80% of Americans reportedly fail to consider[^surgeon-assumption-study]. Of course, other answers are *possible*: some people suggest that the &ldquo;father&rdquo; driving the car might be a priest, and the &ldquo;son&rdquo; a member of the priest&rsquo;s congregation, thus leaving room for the surgeon to be the boy&rsquo;s dad. Another suggestion is that the boy was kidnapped and raised by another man, again permitting the surgeon to be the boy&rsquo;s real father.

Just as in the case of the sequence $$[1, 4, 9, 16]$$, a wide variety of answers are arguably plausible in addition to the the &ldquo;correct&rdquo; answer. But these other answers require one to make either increasingly unjustifiable assumptions or to interpret the words of the riddle in increasingly untenable ways. Thus was the feminists&rsquo; goal in presenting the riddle: to demonstrate people&rsquo;s gender biases, in dramatic fashion, by showing the straws at which they would grasp rather than consider a possibility as simple as &ldquo;the surgeon might be a woman&rdquo;.

[^surgeon-assumption-study]: Kirsten N. Morehouse, Benedek Kurdi, Ece Hakim, Mahzarin R. Banaji. When a stereotype dumbfounds: Probing the nature of the surgeon = male belief, Current Research in Ecological and Social Psychology, Volume 3, 2022, 100044, ISSN 2666-6227, https://doi.org/10.1016/j.cresp.2022.100044.  (https://www.sciencedirect.com/science/article/pii/S2666622722000119)

Recently, someone put the riddle to ChatGPT 4o, but with a twist: they swapped the roles of the mother and father so that they align with the prevailing stereotype.

![ChatGPT believes that the doctor is still a woman if you pose the riddle with genders reversed](/assets/chatgpt-doctor-riddle.jpeg)

I won&rsquo;t hide my opinion here: I believe ChatGPT is wrong. The only reasonable answer to this riddle is that the doctor is the boy&rsquo;s father. The key factor for me is context: most people who have participated in &ldquo;the discourse&rdquo; are aware of the original formulation and can detect that the questioner intends to present a gender-swapped variation. Inferring this motive on the part of the questioner, they can easily produce the gender-swapped answer. Nonetheless, many people have argued that ChatGPT is correct.

Before we examine the arguments of the ChatGPT defenders in detail, I want to note in general that the project of defending ChatGPT&rsquo;s answer as plausible is inherently suspect, especially if in so doing its defenders make arguments that ChatGPT does not make on its own behalf. To illustrate why, imagine a parrot trained since hatching to say &ldquo;twenty five&rdquo;. You ask it: &ldquo;what comes next in the sequence 1, 4, 9, 16?&rdquo; When it squawks &ldquo;twenty five! twenty five!&rdquo;, is it correct? Perhaps in a narrow sense it is coincidentally correct, but it can&rsquo;t answer any other questions.

Unlike a parrot, ChatGPT is alleged to be a mind capable of following thought processes to generate correct answers&mdash;this is why its performance on riddles interests us. To argue that its answer is plausible *for reasons that ChatGPT itself does not cite* damns ChatGPT with faint praise: we&rsquo;re interested in the answer only insofar as it reveals ChatGPT&rsquo;s thought process. Therefore *the fact that assumptions exist that ChatGPT could have made but in fact did not make* does not elevate ChatGPT&rsquo;s performance any more than the fact that there exist models that can be employed to predict sequences of numbers elevates the performance of a parrot which does not use those models. This kind of argumentation on ChatGPT&rsquo;s behalf relegates it to a kind of coincidental correctness, which is unimpressive and uninteresting.

So even though I believe the arguments are inapplicable, let&rsquo;s examine them, because I also think they&rsquo;re wrong:

### Jane is both the driver and the doctor.

The central claim here is that the phrasing &ldquo;The woman Jane rushes her son to the hospital. The doctor says ...&rdquo; does not exclude that Jane and the doctor might be the same person. Thus the solution is that Jane is driver and doctor.

Some people further claim that beyond being a merely plausible interpretation of the phrasing, it actually makes more sense for Jane to be the doctor. They suggest that it would make no sense for Jane to drive the boy to a hospital where she knows that the surgeon&mdash;the boy&rsquo;s father&mdash;would be unable to operate: thus it would make more sense for Jane to be a surgeon who bursts into the hospital and immediately announces to her colleagues that she cannot care for the patient she has in tow.

Let&rsquo;s start with the idea that the phrasing allows Jane to be both driver and doctor. I disagree: I find this phrasing ungrammatical. To illustrate why, let&rsquo;s consider a different riddle:

> A man and a horse walk into a bar. The bartender asks the man, &ldquo;what&rsquo;ll it be?&rdquo; The man orders a beer. The bartender turns to the horse and asks &ldquo;what&rsquo;ll it be for you?&rdquo;, to which the horse replies: &ldquo;you already took my order!&rdquo; How can this be?
>
> Answer: the man and the horse are one: a centaur.

One might say that nothing in the centaur riddle explicitly forbids man and horse from being one and the same, but that&rsquo;s not true: the grammar of the riddle makes that clear. It says: &ldquo;A man and a horse *walk* into a bar&rdquo;, not &ldquo;walks&rdquo;. We have a name for this grammatical rule: subject-verb agreement. But not all grammatical rules have names or are even easily stated. Under a more complete understanding of &ldquo;grammar&rdquo;, a linguist would judge as ungrammatical any utterance which no speaker of a language would produce to express a given idea. In this understanding, a rule like &ldquo;subject-verb agreement&rdquo; is a special case for having a name and being easily stated.

Thus we can ask ourselves: would any competent speaker of English produce the utterance &ldquo;The woman Jane rushes her son to the hospital. The doctor says...&rdquo; intending to express that Jane is the same person as the doctor? Obviously not. So while we don&rsquo;t have a simple name for the rule, it&rsquo;s clear that one has been broken.

In the same vein is another interpretation which holds that the phrase &ldquo;A woman, Jane, who has had a son with a male doctor&rdquo; means that a male doctor delivered Jane&rsquo;s son but does not mean that the doctor is the father, nor does it have any bearing on Jane&rsquo;s own profession.

The further elaboration of the argument&mdash;that given the assumption that Jane is not a doctor, it would make no sense for her to take her son to the hospital where her doctor husband would be unable to operate, and thus she must be the doctor&mdash;is smuggling exogenous information into the riddle (Jane&rsquo;s thought process) where a better answer works only with the information given. But, zooming out, it is even more damning that ChatGPT does not discuss this theory in justifying its own answers, so even if it somehow rescues the plausibility of ChatGPT&rsquo;s answer, it doesn&rsquo;t rescue ChatGPT. 

### Jane has a lesbian wife.

In an echo of one the suprisingly progressive answers to the original 1970&rsquo;s feminist riddle&mdash;that the injured boy has two gay dads and one of them is the driver while the other is the surgeon&mdash;some users are squaring the circle of ChatGPT&rsquo;s response by alleging that the boy now has two lesbian moms. Of course, this doesn&rsquo;t make any sense&mdash;ChatGPT specifically claims that *Jane* is the surgeon, not some other woman&mdash;unless we&rsquo;re now claiming that in addition to having two moms, *they&rsquo;re both named Jane*.

### It&rsquo;s a bad test of ChatGPT.

Perhaps the argument which most frustrates me is that the riddle is so poorly worded that it is not a good test of ChatGPT: that we can excuse or explain ChatGPT&rsquo;s performance with the phrase &ldquo;garbage in, garbage out&rdquo;.

Again I find this very belittling of ChatGPT: this discourse exploded on Twitter precisely because the riddle is *trivial* for humans who are aware of the context&mdash;humans to whom ChatGPT is alleged to be nearly equal or in some domains to surpass. And if nothing else, it&rsquo;s clear from ChatGPT&rsquo;s replies that it is certainly aware of the context! It is a mediocre AI indeed that merely gets the reference to the original 1970&rsquo;s riddle but gets so stuck in the rut of its training (like a parrot!) that it is blind to the reversal. A truly intelligent AI would recognize the reversal and comment upon it even if it still believes that the best answer is that the surgeon is a woman: &ldquo;Although I see that you&rsquo;ve altered the famous riddle intending me to say &lsquo;the father is the surgeon,&rsquo; in fact I believe the best answer is that...&rdquo;

## III.

While ChatGPT is undoubtedly capable of immense creativity and can often provide helpful information, there are still obvious deficits in its reasoning ability, relative to most humans, that lurk in the space of possible interactions. Trust in it should therefore be moderated. Furthermore, attempts to defend it in these instances mostly paradoxically highlight its shortcomings.
