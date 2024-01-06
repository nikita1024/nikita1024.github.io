# What is this page about?
This page describes an idea for a collective decision-making mechanism.

We already have different mechansims:
- **Direct democracy** - when everyone votes on issues directly
- **Representative democracy** - when voters elect representatives, and the representatives then vote on issues
- **Liquid democracy** - when voters can either vote on an issue directly or delegate their vote to someone else (presumably better equipped to make the right choice in your best interest)

# Do we need yet another one?

Each of the existing mechanisms have significant drawbacks:
- **Direct democracy** requires every member of the group to spend much effort to understand the issue, carefully consider pros and cons of the proposed solution, and predict how the different outcomes will play out. Few have time for this. This does not scale beyond small group sizes and a low volume of simple decisions.
- **Representative democracy** forces group members to trust someone to represent their interests for a significant time-period based on very limited information (ie, based on the candidate's election promises). There are few incentives to keep those promises.
- **Liquid democracy** requires you to find someone who would best represent your interests - this discovery process is a problem. We are still faced with making decisions with limited information.

Ok, it's easy to criticize. How do we fix it?

# How does Fluid democracy work?

Like this:
- Like in direct democracy you can vote on any issue directly.
- Unlike direct democracy, if you don't vote directly then your vote is not wasted. Instead, it is delegated to other voter**s** who have voted in your best interest in the past.

You tell the system which of the past decisions you liked and didn't like. For example, if you liked decision A, then the system will delegate your future vote among people who voted for decision A. If you didn't like decision B, then the system will also delegate your future vote to those who voted against decision B in the past. People whose past votes you liked the most will get a bigger fraction of your delegated vote.

There could be hundreds or thousands of people your vote is delegated to (unlike liquid democracy, where you delegate your vote to a single person). Your delegated vote is calculated to be the consensus of people your vote got delegated to. The consensus process is impacted by how big of a share of your vote every person has.

For example, consider that your vote is delegated to Alice, Bob and Carol in fractions of 0.6, 0.3 and 0.1, respectively. If Alice votes in favor of proposal P and Bob and Carol vote against it, then your vote will counted as "for" because 0.6 > 0.3 + 0.1.

You can change your ratings of past decisions at any time as you learn more about the past decisions and how well they panned out. This process of rating past decisions is much easier than voting on those past decisions at the time because you have the benefit of the hindsight.

The benefit of this system is that it solves the problem of discovering trustworthy people to delegate your vote to. Those people don't need to advertise or publicly promote themselves. Let their past actions speak for them.

This system incentivizes knowledgeble people to vote for what is best in the long run because that's how they earn voting influence. Unworkable but sounding good proposals will be punished.

Journalists would be rewarded with attention when they cover the outcomes of past decisions.

# What about my secret ballot?
To calculate who to delegate your vote to, the system needs to know who voted which way. But in many voting settings, we expect a secret ballot where no one can link a casted vote to the voter. *"This forestalls attempts to influence the voter by intimidation, blackmailing, and potential vote buying"*.

One way to allow a secret ballot is to separate the roles of voters:
 - private voters - are individuals that only vote for themselves. The history of their votes can remain private - known only to the individuals.
 - public voters - those who seek to earn delegation power. They make their history of past votes public.






  
