#  KANBAN-ZAI CORE - WHAT IS IT?

Kanban-Zai is an interpretation and implementation of [collaborative game theory](https://en.wikipedia.org/wiki/Cooperative_game_theory), [constraint theory](https://en.wikipedia.org/wiki/Theory_of_constraints), [consensus theory](https://en.wikipedia.org/wiki/Consensus_theory) and [swift trust theory](https://en.wikipedia.org/wiki/Swift_trust_theory) amongst others.  When you implement Kanban-Zai you are making a conscious choice to VALUE objectivity, predictability and trust.

At the end of the day Kanban-Zai is an idea, if you are really into theories you can think of it as a symmetric, 
non-zero, cooperative, sequential game in game theory, but really it is just a way for humans to collaborate and 
uses multiple ideas to build heuristics to help teams be better.  It is not dogma. 

### The Trust Equation

Managing and designing for trust is crucial to thrive in the digital age.  The trust equation allows the ability 
to think objectively about trust and how it works.

    Trust = ( Vibability + Credibility + Reliability ) / Self Orientation (Selfishness)
    
The trust equation tells us how trust is hard to build and easy to destroy.

### Reputation and the Referral Chain

Kanban-Zai is a graph.  It provides transparency about teams and individuals not possible previously.
[core-jml](core-jml.md) 
---

# THE RATIONAL TRUST MODEL

### CONTEXT

Context defines which root node to find your collections of settings, method, values, norms and claims on.  The initial 
context is default.  This means these should all be found on the root node.  When context is set to anything other than
default, given that it can also not be one of the reserved words, then you use the settings on the root node named the
same as the current context.

### CLAIMS

Claims are something that an individual or team claim to be true about themselves.

Claims are listed in the kanban-zai.yaml file.  If a claim does not have a uri attached then the claim is defined as
the claim of the same name defined in the core.  If the name does not exist in the core it is considered invalid.  If
the content at the resolution of an uri does not describe a Kanban-Zai claim it is invalid.

### JOURNAL (Referral Chain)

All deviations from Rational Player Models, Rational Outcome Models or The Rational Trust Model must be journaled in 
the team kanban-zai.yaml file, but ony when explicitly stated by the kanban-zai implementation.

However, anything may be journaled and by anyone in their own personal kanban-zai.yaml files.  

See [core-jml](./core-jml.md) for more.

### TEAM NORMS

These are behaviours that are regularly encouraged or required of team members.  They can also be behaviours that, 
while not common or generally accepted as normal, are accepted as normal on a team.

#### NORM:DEVIATE

A deviation is not a retrospective in the agile sense.

It is a formal method of allowing settings to be changed in Kanban-Zai and must be run regularly with the maximum time 
allowed between deviations being 3 monthly.  Keep it short and involve everybody.  Change by a consensus only. 

#### NORM:MUSTER

The roster is a list of all current team members and interested parties.  New members must be added.  
Old members must be removed.  A consensus vote is required to be mustered as a team member.


#### NORM:CONSENSUS

Core consensus requires an agreement of a quorum of the mustered team members about the direction the team should be 
taking.  Negative votes, and the reasons for them must be journaled.



### SETTINGS
  
#### egos (READONLY)

Required Value: off

#### quorum

Possible Values: 2 | # > 2  DEFAULT: 2


### VALUES

#### objectivity (READONLY)

Objectivity is necessary to get an accurate explanation of how things work.

#### predictability (READONLY)

The fact of always behaving or occurring in the way expected.

#### trust (READONLY)

Without trust, there is no future, it is the capital and engine of progress.


