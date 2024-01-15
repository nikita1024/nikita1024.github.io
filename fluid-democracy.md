# What is Fluid Democracy?
Fluid Democracy (FD) is a collective decision-making mechanism.

We already have different mechanisms:
- **Direct democracy** - when everyone votes on issues directly
- **Representative democracy** - when voters elect representatives, and the representatives then vote on issues
- **Liquid democracy** - when voters can either vote on an issue directly or delegate their vote to someone else (presumably better equipped to make the right choice in your best interest)

# Do we need yet another one?

Each of the existing mechanisms has significant drawbacks:
- **Direct democracy** requires every member of the group to spend much effort to understand the issue, carefully consider pros and cons of the proposed solution, and predict how the different outcomes will play out. Few have time for this. This does not scale beyond small group sizes and a low volume of simple decisions.
- **Representative democracy** forces group members to trust someone to represent their interests for a significant time-period based on very limited information (i.e., based on the candidate's election promises). There are few incentives to keep those promises.
- **Liquid democracy** requires you to find someone who would best represent your interests - this discovery process is a problem. We are still faced with making decisions with limited information.

# How does Fluid Democracy work?

- Like in direct democracy, you can vote on any issue directly.
- Unlike direct democracy, if you don't vote directly then your vote is not wasted. Instead, it is delegated to other voter**s** who have voted in your best interest in the past.

You tell the system which of the past decisions you liked and didn't like. For example, if you liked decision A, then the system will delegate your future vote among people who voted for decision A. If you didn't like decision B, then the system will also delegate your future vote to those who voted against decision B in the past. People whose past votes you liked the most will get a bigger fraction of your delegated vote.

There could be hundreds or thousands of people your vote is delegated to. Your delegated vote is calculated to be the consensus of people your vote got delegated to. The consensus process is impacted by how big of a share of your vote every person has.

For example, consider that your vote is delegated to Alice, Bob and Carol in fractions of 0.6, 0.3 and 0.1, respectively. If Alice votes in favor of proposal *P* and Bob and Carol vote against it, then your vote will be counted as "for" because 0.6 > 0.3 + 0.1.

You can change your ratings of past decisions at any time as you learn more about the past decisions and how well they panned out. The benefit of the hindsight makes it much easier to rate a past decision than to vote on it at the time.

FD solves the problem of Liquid Democracy of discovering trustworthy people to delegate your vote to. The trustworty delegates don't need to advertise or publicly promote themselves. Let their past voting actions speak for them.

Another issue of Liquid Democracy is that it often results in a lot of voting power concentrated in the hands of a few delegates ([link](https://dl.acm.org/doi/10.1145/3485012#:~:text=However%2C%20these%20real%2Dworld%20implementations%20also%20exposed%20a%20weakness%20in%20the%20liquid%20democracy%20approach%3A%20Certain%20individuals%2C%20the%20so%2Dcalled%20super%2Dvoters%2C%20seem%20to%20amass%20enormous%20weight%2C%20whereas%20most%20agents%20do%20not%20receive%20any%20delegations), [link](https://en.wikipedia.org/wiki/Liquid_democracy#Criticism_of_liquid_democracy:~:text=Furthermore%2C-,liquid%20democracy%20as%20a%20democratic%20form%20is%20susceptible%20to%20oligarchic%20tendencies,-.%5B5%5D)). Concentration of power can lead to abuse. FD prevents this by distributing the delegation power more broadly.

FD incentivizes knowledgeble people to vote for what is best in the long run because that's how they earn voting influence. Unworkable but sounding good proposals will be punished.

Journalists would be rewarded with attention when they cover the outcomes of past decisions.

# What about my secret ballot?
To calculate who to delegate your vote to, the system needs to know who voted which way. But in many voting settings, we expect a secret ballot where no one can link a cast vote to the voter. *"This forestalls attempts to influence the voter by intimidation, blackmailing, and potential vote buying"*([link](https://en.wikipedia.org/wiki/Secret_ballot#:~:text=This%20forestalls%20attempts%20to%20influence%20the%20voter%20by%20intimidation%2C%20blackmailing%2C%20and%20potential%20vote%20buying)).

One way to allow a secret ballot is to separate the roles of voters:
 - Private voters - are individuals that only vote for themselves. The history of their votes can remain private - known only to the individuals.
 - Public voters - those who seek to earn delegation power. They make their history of past votes public.

# Wearing multiple hats
Suppose you are an expert in "public transportation" and you have earned voting influence from voting for the right decisions in your area of expertise. What about other issues where you have less expertise like "healthcare" or "education"? By voting for issues in those areas you are risking losing your voting influence on "public transportation". In that situation you may want not to vote on these issues. This self-censorship is not desirable. Everyone should be able to express their preferences.

To solve this issue FD allows you to assign your votes into groups. For example, you can assign your votes on public transportation related issues into the "transport" group. And all other votes can go into "everything else" group. FD treats each of the groups as a separate delegate when it comes to assigning delegation power.

When you vote on an issue you also choose which group this vote will be part of. For example, when you vote on a public transportation related issue you would assign that vote to the "transport" group. Then this vote will carry the delegation influence you earned by your other votes in the "transport" group.

Then you don't have to worry about voting on any other issue. You just assign those votes to the "everything else" group. If anyone dislikes your votes that you put into the "everything else" group, the influence of your "transport" group won't be affected.

# Why is it called "Fluid Democracy"?
*Fluid* is a synonym for *liquid* and it could be confusing. Still I think there is a lot in common between FD and liquid democracy that this similarity is warranted. I think of FD as an improvement over liquid democracy. The way FD distributes the delegation power is more liquid than liquid democracy itself. In liquid democracy you have to delegate your vote to a single person which feels very discrete.
