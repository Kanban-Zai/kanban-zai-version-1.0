# INTRODUCTION

Kanban-Zai is about constraint and discipline.  An explanation, is required.

Where is no process involved, a human being will strive to achieve an endeavour with all the knowledge, skill and experience at
thier disposal.

The problem comes when two human beings are trying to do it together.

Many collaboration methodologies exist.  Many work.  Many end up stemming (most times crushing) the creative spirit they intended
to nourish.

Kanban-Zai Core takes a different approach and places constraints only on what you can not do.

Leaving open, possibilty for the creative spirit.

# DESCRIPTION

Kanban-Zai core is a codeless microservices architecture container framework.
 
It's purpose is to wrap another process ensuring that the rules, procedures and boundaries of that process are 
followed and provides mechanisms to document deviations from that process.

The core must be used by ALL (100%) Kanban-Zai implementations

Once the core is installed you can create and extend it with any process you like by following the principles laid 
out in the core but the meaning and intent of the core module may not be modified by any extension


...


The centerpiece of Kanban-Zai is the Kanban-Zai.yaml configuration file.
 
This file documents the settings, values and behaviours the process defines and the team works within, must be held in a 
public repo and should be kept up to date to keep those settings, values and behaviours current and reflective of the
current time. All changes to this file must be tracked.


...


To use Kanban-Zai you must extend the core.  

To do this.  Create your own kanban-zai.yaml file and add your settings and norms to it.  

You can also choose to implement modules.  Modules are pre-defined sets of constraints and team norms, with an accompanying explanation of how to use 
them. You can add a module to your Kanban-Zai file with the "implements" property.

You must also add the "extend" property pointed to the extension you are extending from.  Most times this will
be the Kanban-Zai core.

IMPORTANT NOTE:  

* All properties of an extension or module must be inherited, including any properties that they extend from.
* You may not remove any properties of an extension or module.
* You may not modify read only properties of an extension or module.
* You may only change the properties of an extension or module to the values specified in such extension or module.
* If there is a property that does not work for you then do not use that extension or module.  Create your own.
* Your customisations must not contradict any aspect of the Kanban-Zai core or any extension or module you use.

SANITY CHECK:

You should probably not create your own extension or module unless you have some experience in Kanban-Zai.  Additionally
you should not nest to deep and you should probably just extend the core in most cases.

# REQUIRED TEAM NORMS

These must be adopted by all Kanban-Zai teams and may not be overridden or changed.

### AUDIT 

An audit is simple a record noted in your kanban-zai.yaml of an auditable event.  It is not a negative or a positive, it
just a record of some aspect on or opinion about, the team.

What events are auditable?

* any outside influence that is exerted on the team in any fashion.
* any action by any team member is in opposition to the settings or team norms.
* any consensus choice that was in opposition to the settings or team norms.
* any change to the Kanban-Zai.yaml file other than an audit.

Who can raise audits in the teams Kanban-Zai file?

* any current team member.  All current team members MUST have access to this file.

Who can raise an audit about the team?

Anyone.  But it must be done in a personal Kanban-Zai file.  This can be done by providing a link to the Kanban-Zai file
that represents the team being audited, within the audit message text.

What must an audit contain?

* A link to the Kanban-Zai file you are auditing, if relevant.
* The consensus vote numbers if any.
* A human readable explanation of the audit.

### DEVIATE

A deviation is a formal method of changing settings.  Don't do it at any other time.  Keep it short and involve 
everybody.  

A deviation is not a retrospective in the agile sense, for example, a deviation allows you to introduce ( or remove ) 
a Team-Norm, change a constraint, implement a module or change the origin point of your extension.

You don't have to change settings in a deviation but it provides a regular opportunity for anyone to do so. However 
it is MANDATORY that only current members of the team may change team settings and norms.

IMPORTANT NOTE: A deviation must be run regularly with the maximum time allowed between deviations being 3 monthly.  You
                must run a deviation a minimum of 4 times per year to keep your Kanban-Zai status active.

### CONSENSUS

To move forward, on anything, a consensus must be achieved.  Effectively this means at least quorum of people.   If a 
quorum cannot be achieved by the presence of enough voting members a vote MUST not be taken. 

This is not to say action cannot be taken if a vote cannot be taken.  But an audit of that action must be recorded as
it is a deviation from consensus.

### BACKPORTING

Back porting is the practice of modifying and splitting cards to represent work, that was, done on a card rather than 
what the card asked for.  It should be obvious, but may not be, that work done on a card must be at least a subset of
what was asked for that was sensible to achieve within the constraints encountered during the execution of that card.

### INDIVIDUALISIM

A team is made up of individuals.  They all bring their own uniqueness to the team. Each person should be treated as an
individual.  In light of this everyone on the team must have a voice and a vote at the table. 
If they choose not to use their voice or vote then their vote should default to the harmony setting. 

Votes cannot not be proxied.

### VIGILANCE

Sometimes covens form.  

A coven is a group of people within the team that share a commonality.  This commonality is good
and can lead to a better consensus.  

When it becomes a clique it is the worst type of bad for a team and will destroy it.

The difference between a coven and a clique is that a coven is INCLUSIVE and anyone can join a clique is EXCLUSIVE
only some certain people are accepted in.

All team members must maintain constant vigilance against cliques forming and must call them out, in addition to it 
being an auditable event.

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


### GUESTS

From time to time the team may require specialized knowledge or experience.  In this case an individual maybe invited 
onto the team for a time by a team member only, but without a consensus vote.  Guests have a special status on the team.
They sit as part of the team. They do not have to be mustered, they may not vote, and their appearance on the team and
subsequent departure from the team must be audited.

Upon arrival the audit must include the length of the guests expected stay.  If that stay is extended the new expected
length of stay must be audited.

### PAN

Sometimes depending on the situation of the team, by consensus, any person can be designated as "PAN".  

Pan is a temporary designation allowing that individual veto power over a consensus for a defined period.  

This maybe done without running a deviation and with only a quorum. It carries with it a maximum allowed 
time of 1 month.  At which time the team can again choose to re-designate the person as "PAN" again.

Any person may be designated as pan including guests.

* Panning is an auditable event.  
* Re-Panning is also auditable.

# REQUIRED SETTINGS

### harmony

Possible Values: positive | negative  DEFAULT: positive

A team reaching consensus can solve many  of the problems that arise but sometimes it is hard to reach consensus.  
The sole purpose of this setting is tie breaking.  It is a pre-determined agreement to gain consensus if there is a tie
in the voting.  If someone chooses to abstain, this becomes their vote.  Please note, this means that there is no way in 
Kanban-Zai to abstain.

### quorum

Possible Values: any number value smaller than your team size, but greater than 1.  DEFAULT: 2

Determines if a vote can be held or not.  You must have at least a quorum to hold a vote.

### deviation

Possible Values: any time value with max 3 months.  DEFAULT: 1 month

### sprint

Possible Values: 1 working week.  (Readonly may not be modified.)

This value is the yard stick by which you measure your ability as a team.  It is the length of one execution of work.
All work taken into a sprint MUST be finished OR the work left over split into another card and put into the next 
sprint.

Please note that this is the ONLY performance metric Kanban-Zai enforces.  The reasoning behind this is as follows...

If a team is planning 1 sprints worth of work and completing that weeks worth of work each week then that is the measure
of a team that is functioning well.  Backporting is included as normal in this metric as backporting has an explanation
and a solution attached.  

From here we can infer 3 things.

1. If cards are being planned and completed by sprint end.  The project timeline can be predicted with deterministic variance.
2. If backporting is happening there is a problem with the product model.
3. If cards are not being completed and not being backported there is a fundamental problem with the team.

Product model problems include
- functional granularity issues. ( to much or not enough )
- business rule conflicts
- market fit/business rule/technology conflicts


The fundamental problems are 
 - Prioritization Failures
 - Under resourcing
 - covens


    
### optimize

Possible Values: time-to-market | performance | maintainability DEFAULT: time-to-market
   
time-to-market: Optimises for speed to market.   Technical debt is amortized and Test Driven Development is recommended.  Codebase is required
                to be maintainable to the degree that the chosen framework enables.  If no framework is chosen then the definition of maintainablity
is should be defined by test suites.  It Test driven development is of then maintainablity has no definition in this context.

performance: Requires code to perform to minimum performance requirements, Tech debt is prevented and test driven development is compulsory.

maintainability: Requires code to be maintained and a formal definition provided in kanban-zai.yaml using the top level key maintainability.
   
### tdd

Possible Values: true | false DEFAULT: false
  
Test Driven Development is turned off by default as it has benefits and detriments.

### tech-debt

Possible Values: amortize | reduce | prevent DEFAULT: amortize

amortize: record all technical-debt.  Reduce that debt when practical.  Otherwise leave it until you are bored and have nothing else to do.

reduce: record all tech debt and schedule in to sprints.

prevent: when technical debt occurs resolve it there and then.  This could make very long running cards, but cards should be backported per sprint.

