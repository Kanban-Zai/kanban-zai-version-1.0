#  KANBAN-ZAI CORE - WHAT IS IT?

Kanban-Zai is about bringing objectivity to a development team by inspiring tolerance and trust.

### Beliefs, Behaviours and constraints

Kanban-Zai is a belief system that leverages behaviors and constraints to define a framework in which people can work
objectively.  It is a way for humans to collaborate and co-opts many different ideas about project
management to build heuristics that help teams be better.  It is important to recognise that it is not dogma. 

### The Trust Equation

Managing and designing for trust is crucial to thrive in the digital age.  The trust equation allows the ability 
to think objectively about trust and how it works.

    Trust = ( Vibability + Credibility + Reliability ) / Self Orientation (Selfishness)
    
The trust equation tells us how trust is hard to build and easy to destroy.

### Reputation and the Referral Chain

Kanban-Zai is a graph.  It provides transparency about teams and individuals not possible previously.
[core-jml](core-jml.md) 

---

# DESCRIBING THE RATIONAL TRUST MODEL (kanban-zai.yml)

The rational trust model that is Kanban-Zai is defined in succinctly the [kanban-zai.yaml](./kanban-zai.yaml) file.  
This readme file (that you are looking at now ) and other official documentation provide depth and clarity.  Tools to 
leverage the power of the Kanban-Zai file, are planned.


### CONTEXT

Context defines which root node to find your collections of settings, method, values, norms and claims on.  The initial 
context is default.  This means these should all be found on the root node.  When context is set to anything other than
default, given that it can also not be one of the reserved words, then you use the settings on the root node named the
same as the current context.

### JOURNAL (Referral Chain)

A journal entry is a record of dissent from consensus.  For practical purposes only two types of dissent are detailed
here, but anything may be recorded.  The two types are, disagreeing with the rules and breaking the rules.  

Both must be journaled in the team or if that is not possible your own personal kanban-zai.yaml file.  Anything may be 
journaled and by anyone in their own personal kanban-zai.yaml files.

Generally speaking the team Kanban-Zai file is reserved for recording breaches of consensus from outside the team and
where Kanban-Zai rules explicity state a journal is required.  But it is not limited to this. 

See [core-jml](./core-jml.md) for more.

---
### BELIEFS

#### RATIONALITY

To be rational in Kanban-Zai is to want to play by the rules.  However, rationality is not enough: each player must also 
believe that all other players are rational. Even this is not enough: each player must believe that all other players 
believe that all other players are rational.

#### IRRATIONALITY

To be irrational in Kanban-Zai is to not share the same belief of rationality because they do not understand them, and
quite likely never will.  Irrational players do not have say in a Kanban-Zai Team.

### COMMONSENSE

Common sense works different in the digital world.  What is obvious and sensible in the real world may not be in the 
digital.  A poor choice in the digital can have outrageous time and cost penalties when compared to a similar 
circumstance in the real.  Maybe.

---

### TEAM NORMS

These are behaviours that are regularly encouraged or required of team members.  They can also be behaviours that, 
while not common or generally accepted as normal, are accepted as normal on a team.

#### DEVIATE

A deviation is not a retrospective in the agile sense.

It is a formal method of allowing settings to be changed in Kanban-Zai and must be run regularly with the maximum time 
allowed between deviations being 3 monthly.  Keep it short and involve everybody.  Change by a consensus only. 

#### MUSTER

The roster is a list of all current team members and interested parties.  New members must be added.  
Old members must be removed.  A consensus vote is required to be mustered as a team member.


#### CONSENSUS

Core consensus requires an agreement of a quorum of the mustered team members about the direction the team should be 
taking.  Negative votes, and the reasons for them must be journaled.

#### PAN

Via a quorum a rational player can be granted the privilege of pan.  Pan, has veto power over all consensus for a defined 
period of no more than 1 month maximum.  The election must be journaled as must the start and end dates.

---

### SETTINGS (constraints)
  
#### egos (READONLY)

Required Value: off

#### quorum

Possible Values: 2 | # > 2  DEFAULT: 2

The minimum amount of votes needed to reach consensus

#### cadence (class)

Possible Values: 1 week | a unit of time  DEFAULT: 1 week

The minimum tick of of the team, from which all timing is based.

#### Prime limit (cadence)

Possible Values: 2| # > 2  DEFAULT: 2

The maximum amount of work that may be pushed to a team at any one time.


---

### VALUES

This is an ordered list, from most important to least important, of values that guide team discipline.

#### objectivity (READONLY)

Objectivity is necessary to get an accurate explanation of how things work.

#### predictability (READONLY)

The fact of always behaving or occurring in the way expected.

#### tolerance (READONLY)

Tolerance is a value orientation towards difference.  Or more simply.  Difference is good.

#### trust (READONLY)

Without trust, there is no future, it is the capital and engine of progress.

---

### OUTCOMES

All work has outcomes.  In the digital world rational outcomes are required to limit the total possible scope of work.
For example. A definition of done or a supported browser matrix are great examples of rational outcomes.  Outcomes are 
everywhere.  An outcome can be measured after the first step of a process or the last or anywhere in the middle.

#### value

Value to customers and ultimately tangible quality, is a very subjective concept.  It is what your customers 
perceive it to be.  It's so subjective, that it's hard to define it. If you know what customers benchmark as value 
you can provide it.  

Ultimately the client holds the responsibility of defining what value means to them, and it depends on 3 factors
* Market Fit
* Business Fit
* Technology Fit

#### quality

Quality is value made tangible. What was asked for is delivered.  

There is hidden danger in this statement as it seems to say that value is the responsibility of the delivery team.  
It is not.  

Value is what the customer defines, quality is what is finally delivered.  Tangibility.

The more accurate the definition of value the better the tangible quality.  A poor definition of value must still result
in the exact delivery of the value described.

The caveat here is that development is not static.  The delivery team are the people best situated to give early 
feedback about the value proposition as well as cost/benefit ratios and work around's.  Therefore, value can be tweaked
as part of the delivery process.
