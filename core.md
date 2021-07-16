# INTRODUCTION

Kanban-Zai is an interpretation and implementation of collaborative game theory, Specifically consensus decision theory.
 
The core can be defined as a rational trust model which provides an objective baseline from which trust can be built
according to "The Trust Equation"

    Trust = ( Credibility + Reliability + Intimacy ) / Self Orientation

Because software development is an iterative process, trust can be measured objectively, by anyone, over
time. Trust measured over time becomes reputation.  

This measure of reputation is applied to all entities, teams and clients and individuals alike, and can be 
measured from any entities' perspective.

 
Rules of implementation:

* The core must be used by ALL (100%) Kanban-Zai implementations
* Once the core is installed you can extend it with any process you like by following the principles laid 
out in the core.
* The meaning and intent of the core module may not be modified by any extension, module or customisation.

## KANBAN-ZAI.YAML

The centerpiece of Kanban-Zai is the Kanban-Zai.yaml configuration file.
 
* This file documents the behaviours, claims, constraints and values of a Kanban-Zai implementation.
* It must be held in a public repo.
* All changes to this file must be tracked.
* It must be kept current and reflective of the present.
* May only be modified by rostered team members.

## EXTEND

To use Kanban-Zai you must extend the core.  

To do this.  Create your own kanban-zai.yaml file and add your settings and norms to it.  

You can also choose to implement modules.  Modules are pre-defined sets of  behaviours, claims, constraints and values
with an accompanying explanation of how and why to use them. 

You may add a module to your Kanban-Zai file with the "implements" property.

You must also add the "extend" property pointed to the extension you are extending from.

If no extend property is sent then the default is to inherit from the latest Kanban-Zai core module.

IMPORTANT NOTES:  

* All properties of an extension or module must be inherited, including other upstreams that they extend from.
* You may not remove any properties of an extension or module.
* You may not modify read only properties of an extension or module.
* You may only change the properties of an extension or module to the values, if specified, of the extension or module.
* If there is a property that does not work for you then do not use that extension or module.  Create your own.
* Your customisations must not contradict any aspect of the Kanban-Zai core or any extension or module you use.

SANITY CHECK:

* You should probably not create your own extension or module unless you have some experience in Kanban-Zai.  
* Additionally, you should not nest to deep
* You should probably just extend the core in most cases.

# CLAIMS

Claims are something that an individual or team claim to be true about themselves, and is therefore a reference point
for analysis.

what kind of claims are there?

Currently, the only claim in Kanban-Zai are Rational Player Models.  These are the models of what it means to be
a rational player on a Kanban-Zai team.


# TEAM NORMS

These are behaviours that are reqularly encouraged or required of tam members.  They can also be behaviours that, while
not common or generally accepted as normal, are accepted as normal on this team.

## JOURNAL 

A journal is simple a record noted in your kanban-zai.yaml of an auditable event.  It is not a negative or a positive, it
just a record of some aspect on or opinion about, the team.

What events may be journaled?

* any outside influence that is exerted on the team in any fashion.
* any action by any team member is in opposition to the settings or team norms.
* any consensus choice that was in opposition to the settings or team norms.
* any change to the Kanban-Zai.yaml file other than a journal.
* where a particular module, extension, setting or norm definition specifys.

Who can raise audits in the teams Kanban-Zai file?

* any current team member.  All current team members MUST have access to this file.

Who can raise a journal about the team?

Anyone.  But it must be done in a personal Kanban-Zai file.  This can be done by providing a link to the Kanban-Zai file
that represents the team being audited, within the journal message text.

What must a journal contain?

* A link to the Kanban-Zai file you are auditing, if relevant.
* The consensus vote numbers if any.
* A human readable explanation of the journal.

### DEVIATE

A deviation is a formal method of changing settings.  Don't do it at any other time.  Keep it short and involve 
everybody.  

A deviation is not a retrospective in the agile sense, for example, a deviation allows you to introduce ( or remove ) 
a Team-Norm, change a constraint, implement a module or change the origin point of your extension.

You don't have to change settings in a deviation but it provides a regular opportunity for anyone to do so. However 
it is MANDATORY that only current members of the team may change team settings and norms.

IMPORTANT NOTE: A deviation must be run regularly with the maximum time allowed between deviations being 3 monthly.  You
                must run a deviation a minimum of 4 times per year to keep your Kanban-Zai status active.


### BACKPORTING

Back porting is the practice of modifying and splitting cards to represent work, that was, done on a card rather than 
what the card asked for.  It should be obvious, but may not be, that work done on a card must be at least a subset of
what was asked for that was sensible to achieve within the constraints encountered during the execution of that card.


### MUSTER

The roster is a list of all current team members.

* New team members must be added.  
* Old team members must be removed.  
 
How do you get on the team? You are voted on.  Therefore, Only people who work with the team as direct collaborators 
may be mustered.

Everyone else must be prioritised.  

Muster is important as only team members may vote during a consensus round.

Failure to maintain a current roster or inclusion of people on the roster without a vote is an auditable event.

NOTE: Failure to maintain the roster is likley to not be audited by the team.  This case is an example of individuals
on the team expressing thier displeasure with the team discipline in their personal Kanban-Zai.yaml files.



# REQUIRED SETTINGS

## egos

Required Value: off (READONLY)

## sprint

Possible Values: 1 working week. (READONLY)

This value is the heart beat of Kanban-Zai.

It is the yardstick, the length of one execution of work, by which your ability as a team is measured.

All work taken into a sprint MUST be finished, OR the work left over split into another card and put into the next 
sprint.

This regular practice increases your credibility and reliability score in the trust equation, and therefore your
teams reputation.


## quality

Possible Values: triumvirate | performance | resilience DEFAULT: time-to-market
   
triumvirate:    This is a Kanban-Zai module whose purpose is to define value to customer

performance:    Requires code to perform to minimum performance requirements.
                * Tech debt is prevented.
                * Test driven development is compulsory.
                * Time to market cannot be formally defined.

resilience:     Requires longer lead times for scenario testing
                * Test Driven Development must be set to true.

# REQUIRED VALUES

### Objectivity

A Kanban-Zai team must look for objective measures in everything they do.

What is objectivity?

* A lack of favoritism or personal bias toward one side or another.  
* Problems must be solved by a team and not individuals
* Measure and validate what you can.
