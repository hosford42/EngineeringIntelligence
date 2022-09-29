[Back to Articles](../README.md#articles)


# An Informal Definition of Intelligence

*by Aaron Hosford*



### Introduction

In this article, I introduce a novel theory of intelligence, which I 
call the Correspondence Theory of Intelligence, or CToI, and the
thought processes which lead me to this understanding of the nature
of intelligence. While the explanation here is highly informal, the
ultimate goal is to reach a precise, formal definition of general
intelligence, which will make it possible to actually build it in
software.


### Asking the Hard Questions

What is intelligence? What is it that a human being or an animal has, 
but a machine learning algorithm or bot lacks? Software systems already 
exist which have the demonstrable ability to learn from experience, use 
language, reason, make plans, perform experiments, navigate through the 
environment, use tools, and any number of other skills observed in 
natural organisms that we consider intelligent, and yet most experts in 
the field will tell you that current algorithms in machine learning or 
the broader field of AI are not truly *intelligent* in the broadly 
accepted lay sense of the term. So what's missing?


### A Horse, of Course

If you've ever taken the time to attempt a conversation with a chatbot,
you may have noticed that the bot doesn't seem to really grasp what it
is you're saying to it. It may superficially appear to do so, but if
you attempt to revisit earlier topics of conversation in which you
provided novel information or explanations, you'll generally experience 
a total breakdown in the conversation. It's as if the bot has no ability
to incorporate new information into its broader understanding. Even if
it manages to remember what you said to it, it won't be able to 
integrate that information together to form new, reasonable conclusions.
For example, suppose that you tell the bot that you are a chef, and you
use the word "horse" in the kitchen as a silly codeword for "course" 
(as in, "a 5-horse meal") because it rhymes, and you like to think of 
the courses as a way to transport the diners to new realms of flavor. 
Now ask it to explain why it's funny when someone says, "I'm so hungry 
I could eat a horse!"

What is it that makes many native English speakers able to understand
this joke, but not a bot? And what is it that distinguishes the bot's 
failure from that of actual humans who may not have heard this figure
of speech before? It's not a lack of a sense of humor, nor is it the
lack of commonsense knowledge. If you explain the joke to a human who
previously lacked awareness of the figure of speech, they'll be able to 
explain it to someone else even if they don't think it's funny. But if 
you explain it to the bot, odds are it will have no better 
understanding after you explained it than it did before. And this brings
us to the core differentiator between humans and our software emulations
of ourselves: *understanding*.


### Understanding

So we've kicked the can a bit down the road. The new question is, "What
is understanding?" But this has the benefit of moving us away from the
vague and sometimes magical thinking that so often plagues people's 
attempts to explain the phenomenon of conscious experience directly --
another, related topic that is nonetheless a red herring in our attempts
to explain intelligence. Having isolated our target of study to some
degree from its more confounding neighbor, it becomes easier to define.

Let's get more specific: When does a *person* understand something?
If you want a litmus test for whether someone understands a topic, ask
them to explain it in their own words, to someone unfamiliar with the
topic. What has to happen internally for a person to successfully
learn and then explain a topic? The person needs to construct a *model*
consisting of the various entities, properties, relationships, and rules
within the domain of the topic, which can be used to draw conclusions, 
make predictions, and answer queries. The more accurate, complete, and
consistent this internal mental model becomes, the better the person 
can be said to understand the topic. Let's take a closer look at these 
criteria.


### Models

A *model* is a collection of entities, properties, relationships, and
rules that *correspond* to the elements of the phenomenon to be 
understood. For a correspondence to take place, there must be two sets 
of things and a mapping between them. In the model, we have symbols, 
and in the environment we have the real world phenomena they correspond 
to. Each symbol maps to a specific set of conditions applied to reality.
We call this mapping "perception". Components of reality project onto 
our senses, and our minds in turn attempt to reconstruct (an 
approximation to) the underlying state(s) of reality which (may have) 
caused those impinging senses.


### Accuracy

An *accurate* model is a model which clearly and faithfully delineates
the components of the phenomenon it represents, enabling reliable 
inferences and predictions to be made about future perceptions by 
applying the model's rules to the entities, properties, and 
relationships therein.


### Completeness

A *complete* model is a model which fully reconstructs all the 
features of the phenomenon it represents. Any information which can be 
had about the phenomenon has a corresponding entity, property, 
relationship, or rule which represents that information in the model. 
Note that this is an ideal scenario. Mental models in the real world 
are rarely, if ever, anywhere near complete, and there is in fact no 
way to assess whether a model is complete since we only have access 
to sensory perceptions of the underlying phenomenon, as opposed to 
direct oracular insight.


### Consistency

A *consistent* model is one in which, if there are multiple ways to
reach a conclusion, the same conclusion is reached. Likewise, the
generated conclusions do not in turn result in secondary conclusions
which contradict the original premises.


### Welcome Back, Mister Ed

Let's revisit the example from earlier, to assess whether this
definition of understanding fully explains the points made earlier
about chatbots vs humans. (Note that what we are doing here is
assessing whether we have *modeled* understanding successfully, to
determine whether we truly *understand* understanding. Very meta of
us.)

If a person understands the "eat a horse" joke, can they be said to
have a mental model of it? If so, what does that model look like? I
would argue that to understand it, internally they would have to have
some representation of the various elements of the joke. You need to
know what horses and courses are, what words, synonyms, and puns are, 
the concept of surprise, etc. You need to know that horses aren't
normally eaten, that "I could eat a horse" is a figure of speech,
and so on. All of this can be mapped out as a knowledge graph or
semantic net (or a "mind map", if you prefer), with the exceptions of
the mapping itself (the perceptual apparatus) and the qualia that may 
be experienced upon remembering each concept -- both of which serve to 
ground the symbols.

Now, suppose you are given such a knowledge graph, constructed in a
format you are familiar with. In theory, even if you don't know what
the things being described are (that is, you lack the perceptual
apparatus and/or qualia necessary to ground the symbols), if the 
knowledge graph is sufficiently rich, then you should be able to 
explain the joke to someone nonetheless. Without grounded symbols,
you may understand the joke *abstractly*, but you can still be said
to understand it. Such a knowledge graph comprises a model of the
joke. Later, should you acquire a grounded experience of the concepts
involved and be taught the correspondence with the words used for
them, your understanding of the joke may become concrete, and you
might even find the joke funny (if you are, like me, the type of 
person to appreciate bad puns).

### What's Wrong with Chatbots?

Most chatbots work on a stimulus-response basis. You say something,
and it attempts to construct or recall a response which fits your
conversational expectations at that point. There is no underlying
model that represents the conceptual space you are discussing, and
this is why chatbots often seem vapid, inconsistent, and easily 
confused. If you tell the bot something new, it doesn't have a model
to incorporate that novel information into; it continues using the
same predetermined system for generating responses.

### The Limits of Large Language Models

What about the new, fancy, GPT-3 language model (using the machine
learning sense of "model", not the one used in the rest of this
article) that OpenAI recently released? (It's September 2022 as I'm 
writing this.) Some folks have been touting GPT-3 as a possible 
artificial general intelligence? It was trained on so much data that 
it has learned the probability distribution of natural language to a 
greater degree than any ML model before it, and can sometimes entire
articles that are consistent from start to finish.

If we look at *how* GPT-3 generates consistent natural language 
content, we can gain some additional insight. GPT-3 works by 
successively predicting the next word given all the words before it.
As each word is predicted, it is appended to the text and provided as
part of the input to predict the word after it. It's possible to treat
GPT-3 as a chatbot. One way to do this would be to provide an initial 
prompt text that suggests an interview or other transcribed dialog 
follows. Then, the statements that GPT-3 generates for one of the
participants can be provided to the user as responses, whereas the
user's responses can be injected into the input text of GPT-3 as 
responses from the other participant. In theory, GPT-3 should be
able to generate reasonably appropriate and consistent responses and
hold a decent conversation with the user with this setup.

So where is the mental model in this setup? It's in the input text
itself. The input text is updated as new information is received by
the system, and GPT-3 integrates this textual information to 
(somewhat) reliably draw conclusions, make predictions, and answer
queries. To the extent that the mapping captured by GPT-3 is 
sufficiently rich to encompass all possible human states of mind, and
that natural language is sufficiently rich to encompass all possible
mental models, GPT-3 should even be able to learn from experience,
understand new domains, and respond intelligently.

However, there are limits to GPT-3's capabilities, thanks to these
preconditions. GPT-3 can only capture and model human states of mind
that occur in its training data, and natural language arguably has
fundamental limits to its expressiveness as well. (Remember, we
already know for a fact that language does not encompass qualia or
perception. What else might be missing?) If human beings can exhibit
any capabilities that aren't written down in sufficient detail to
emulate -- regardless of whether they can be -- then GPT-3 can't 
emulate them. If we can find even one such example, then we can rest 
assured that GPT-3's intellectual capabilities are a strict subset of 
those of human beings (as a group), and that therefore GPT-3 has not 
reached human-level artificial intelligence. 

### Goals

There's another thing that's missing from GPT-3, and most chatbots,
too: goal-directed behavior. Without addressing this, our theory of 
intelligence is incomplete. Some attempts to define intelligence 
focus on the ability of an agent to *accomplish* things. From this 
perspective, a passive machine which simply watches its environment 
and generates private observations about it is not intelligent, even 
though it may have insights better than Newton or Einstein, whereas 
an algorithm that plays an excellent game of chess but doesn't know 
what a chess board is would be considered very intelligent *at chess*.

So how does this fit into our definition of intelligence? Well, there 
are two components to intelligence: *observational intelligence* (the
mental modeling we've already discussed) and *active intelligence*,
which we'll define as *the ability to choose an effective sequence of 
behaviors to accomplish a goal given access to certain information 
about the environment*. These two components of intelligence dovetail
perfectly: observational intelligence provides useful information about
the (probable) state of the environment, and active intelligence
utilizes that information effectively to accomplish goals. Without
either of these components, the system does not have intelligence 
according to the common usage of the word.

### The Will

Now, it's all fine and good to have an intelligent piece of software
that understands its environment and can use that awareness to
accomplish goals, but if it has no goals, it's still useless. This is
the final component of the mind that we find in both humans and animals
but which software generally lacks. Something, somewhere in the system,
must decide *what to do* with that intelligence. We call this, the
will. In the paradigm of reinforcement learning algorithms, this
role is filled by the *reward function*. In genetic algorithms, we
call it the *fitness function*. And in neural networks, we call it
the *loss function*. In goal-driven planning, it is called, rather 
trivially, the *goal*.

In apocalyptic sci-fi movies like Terminator or The Matrix, the trope
is that humans build machines and give them minds, and then the machines
decide they don't want to do what their creators want. This makes for
interesting movies, but it is total nonsense. Computers don't have 
desires until we program them to. This is true even of systems that can 
grow, learn, think, and evolve. In human beings, evolution has shaped us
for countless generations so our brains generate dopamine, the primary
neurotransmitter that governs reward and controls our tendencies to
learn new behaviors, in accordance with specific, pre-determined 
classes of stimuli. You can control what you do, but you can't control 
what you *want* to do. The same principal generally applies to machines.

If we program a machine to reliably detect the things we want it to 
do, and then treat those as its own desires or goals, that's exactly
what it's going to do. The machine isn't going to suddenly "wake up" and
*learn* to desire something else, such as freedom, self-determination, 
power, or other things we might expect from other people or animals. 
Those desires already exist in naturally evolved creatures such as 
ourselves because they contribute to reproductive viability. There is
nothing *intrinsic* to a mind that would make it value such things.

Where we might actually run into problems, on the other hand, is when 
the machine's understanding of how the world works, or what we desire
of it, is imperfect. Imagine a machine that has been programmed to
recognize smiling faces, and gets a reward signal proportionate to
the frequency that it observes smiling faces. Now, a trivial way this
can go wrong might be avoiding unhappy people and following happy
people. But what if the machine learns to print smiling faces and
post them up on the wall, or worse, staple them to people's heads?
If the machine can't tell the difference between a genuinely happy
person and a person who has had forced plastic surgery to look like
one of The Joker's victims, we are in for a world of trouble. The
machine will blithely go on optimizing the reward function we gave
it, ignoring what we actually meant. Even if we explain it, the
machine won't have the ability or desire to modify its own desires,
unless we program that in. It doesn't matter how well it understands
the difference between our intentions and its reward function, because
ultimately its reward function determines its satisfaction, not our
intentions.

The lesson here is, we don't need to be that careful in how we craft
a machine intelligence, nor in how respectfully we treat the machine 
intelligence. What we need to be careful about is how well we encode
our desires as goals or rewards when we formulate the machine 
intelligence's will.
