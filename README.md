# minerva
ConverseWithEveryone

Hello internet! I have an idea, but neither the time nor the skill to implement it. I’m a neuroscientist, and I get a lot of those. Since I’m doing real science about the brain I think about a lot of aspects of us all being human minds, and then find myself having ideas and questions that I have no time to investigate myself because I still need to keep science-ing, and are often well beyond my expertise. So, I figured I’d put this here, start a [github project here](https://github.com/MrJoleCRains/minerva/), and see if anything comes of it. I know next to nothing about coding this sort of thing, but I’d love to learn a bit and see what I can fiddle with. 

This is an idea for an experiment in human texting behavior and Artificial Intelligence.

I call it Minerva.

The idea would be to have an app on a cell phone that would act just like a typical messenger: you can contact anyone you like, group message, whatever. Ideally, you’d be able to integrate it into any messenger you’re already using, gchat, facebook, slack, possibly even Reddit, your email?  

But you can also choose to talk to a bot. Each bot is actually the address in some number of bots. Each bot is a chat bot, something simple like [CleverBot](http://www.eviebot.com/en/). 

They are talking just to each other, and treat each other just as if they were one of us. They talk at about the rate of each of us and end conversations like we do. Each bot has some memory mechanism for choosing when or how conversations are ended and who to call for their next conversation. 

We should write the code which keeps that mechanism in sych a way that anyone with a little skill will be able to write a node, as long as it is secure and protects people’s privacy. None of the bots should be able to keep enough information to reconstruct the meaning of a sentence, and none of the bots should be able to identify anything about the origin of data that would allow them to clearly identify where the data came from.

Whenever you have a conversation, a bot is born and first has the experience of your conversation, in whatever detail that we can actually secure. It can then choose to call someone, or wait. While it waits, it may get a call from a caller. It can identify each caller in its own list, but has no way to identify callers as robot or human, nor to identify anything about the source of the conversation. If it gets a call, it can decide whether to respond based on the first line. It can also ask to call a specific caller, and if it chooses to call a human the statement will be waiting of the human when they ask to speak to Minerva, but will disappear if another bot asks to speak to the human before the human picks up.  
Using it’s flexible and learned backend, it then does its best to carry on the longest conversation it can keep whatever is on the other line.

Bots are born and die by competition. The resource is the length of the conversation. They get it for sustaining longer conversations, but longer conversations with bots yields much less than longer conversations with humans, and some amount of conversing with humans is required to survive. If they get enough resource, they can pay some of it to try to get the next conversation from a particular person or bot. They will then produce offspring in a flexibly defined way, and that offspring can get that conversation.
So, all our conversations become training data for a giant AI. We can start a conversation with Minerva and it will pick a set of bots or people to call using what you said to make a conversation last with you. You will not know if it is a bot or a person. When the other breaks off the conversation, it choses another bot or person to give you until you actually leave for a period of time. You then don’t know if you’re talking to a human being or the robot, and in fact, it will probably change over the course of the conversation. In this way you can enter a much larger conversation than you ever could with twitter or reddit or facebook, with your voice blending with many others, protected by anonymity and the ability to walk away at any time, but united by saying similar things or having a similar conversation.

(Something will have to be done to prevent terrible people or terrible robots saying horrible things to children or people that don’t want to have those kinds of conversations. Not a trivial problem.)

Anyone can write a bot and drop it into the pool of bots. That bot then does the best it can against all the other bots, and if it does well, it’ll grow into more of Minerva’s pool.

So: I have some big questions that I’d like smart people to answer.
1.)	Cryptographers and Linguists: How much of the content of a sentence actually has to move on to give reasonable security? We never want a robot to accidentally say to John “Jane Doe is keeping a secret from John!” using information from a conversation with Jane. Is it possible to guarantee that information is not even there, but you still pass on the information of the sentence? Don’t forget, we still need to be able to talk about important people or celebrities with Minerva.

2.)	Psychologists: Could this be beneficial to patients? That is, can we put roles on the psychologists and their patients, again protect everybody, and then simply give someone a helpline to either a psychologist or a bot anytime?

3.)	Philosophers/Game Designers: Could we somehow make reasonable discourse a part of this? That is, let humans penalize a bot for saying things that are demonstrably untrue, with good reasons? Perhaps give rewards for arguments that end in honest agreement or at least agreement on what needs further discussion? 
