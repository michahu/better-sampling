# Project Proposal Brainstorming

Claim: Language models learn an average distribution, which is to say that they learn an aggregate of voices.

Maximization methods make no sense, because you are taking the most likely thing that a lot of people will say. But inherently, storytelling is not done in the aggregate.

Top k looks good because randomization samples a single voice at each timestep. Its degeneracy occurs because there does not exist continuity. Basically, you have a bunch of dudes reading what the last dude wrote on a chalkboard. Current dude then write a word for the next dude.

To fix this, we need a theory of mind. Have some continuous form of context, and deform the average to look more like a personal distribution.

Prove this with Shakespeare. Train model on the bard. Sample FROM OLD using new method. Show that recovered distribution looks like the bard.


