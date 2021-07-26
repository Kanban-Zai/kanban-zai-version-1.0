#  KANBAN-ZAI CORE - WHAT IS IT?

Kanban-Zai is an interpretation and implementation of [collaborative game theory](https://en.wikipedia.org/wiki/Cooperative_game_theory), [constraint theory](https://en.wikipedia.org/wiki/Theory_of_constraints), [consensus theory](https://en.wikipedia.org/wiki/Consensus_theory) and [swift trust theory](https://en.wikipedia.org/wiki/Swift_trust_theory).  When you implement Kanban-Zai you are making a conscious choice to VALUE objectivity, predictability and trust.

The core implementation comprises 4 elements and all can be extended.
* Rational Trust Model
* Rational Player Models
* Rational Outcome Models
* Referral Chain.

At the end of the day Kanban-Zai is an idea.  A way for humans to collaborate.  It should be viewed as a heuristic 
to help teams be better and not dogma. 

### The Trust Equation

Managing and designing for trust is crucial to thrive in the digital age.  The trust equation allows the ability 
to think objectively about trust and how it works.

    Trust = ( Vibability + Credibility + Reliability ) / Self Orientation (Selfishness)
    
The trust equation tells us how trust is hard to build and easy to destroy.

### Reputation and the Referral Chain

Kanban-Zai is a graph.  It provides transparency about teams and individuals not possible previously.

### HOW TO PLAY!

Players clarify the goal and follow the Kanban-Zai process until their achieve the goal.  Documenting deviations from 
process along the way.

### CONTEXT

This is a special setting.  it can be set to anything.  Its default is "none".  Context enables a shift in the 
interpretation of Kanban-Zai.  Settings and norms may have context specific definitions based on this setting.
To use context, define its values relative to your implementation and define those in the setting or norm description.
If a setting or norm has no related context it is valid in all contexts.

### CLAIMS

Claims are something that an individual or team claim to be true about themselves.  In version 2.0 of the core, the only
claims in Kanban-Zai are Rational Player Models and Rational Outcome Models.

### JOURNAL (Referral Chain)

All deviations from Rational Player Models, Rational Outcome Models or The Rational Trust Model must be journaled in 
the team kanban-zai.yaml file, but ony when explicitly stated by the kanban-zai implementation.

However, anything may be journaled and by anyone in their own personal kanban-zai.yaml files.  

See core-jml.md for more.

### TEAM NORMS

These are behaviours that are regularly encouraged or required of team members.  They can also be behaviours that, 
while not common or generally accepted as normal, are accepted as normal on a team.

### DEVIATE

A deviation is not a retrospective in the agile sense.

It is a formal method of allowing settings to be changed in Kanban-Zai and must be run regularly with the maximum time 
allowed between deviations being 3 monthly.  Keep it short and involve everybody.  Change by a consensus only. 

### MUSTER

The roster is a list of all current team members and interested parties.  New members must be added.  
Old members must be removed.  A consensus vote is required to be mustered as a team member.

### BACK PORTING

Back porting is a strategy of Kanban-Zai that allows cards to be split or combined rationally to manage scope creep, 
unknown unknowns and early thinking.  This allows justifiable explanations for the delivery runway length.

Unfinished work on a card in a sprint should be split out to one or more cards and those cards prioritized.

### CONSENSUS

Core consensus requires an agreement of a quorum the mustered team members about the direction the team should be 
taking. 

## SETTINGS

### egos

Required Value: off (READONLY)

### quorum

Possible Values: 2 | # > 2  DEFAULT: 2

### deadlines

Required Value: not-allowed

## VALUES

### objectivity 

Objectivity is necessary to get an accurate explanation of how things work.

### predictability

The fact of always behaving or occurring in the way expected.

### trust

Without trust, there is no future, it is the capital and engine of progress.

# METHOD

The default Kanban-Zai delivery method is a prioritised-backlog.  This is simply maintaining a list of ordered cards.  
These cards can be in one of 4 states.

* Idea.         cards remain in this state until they break the product rom constraint.
* staged.       cards remain in this state until they break the value rom constraint.
* In Progress.  cards remain in this state until they break the quality rom constraint.
* Done.         cards are removed from the backlog.
