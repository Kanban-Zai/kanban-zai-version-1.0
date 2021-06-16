# INTRODUCTION

Kanban-Zai is about constraint and discipline.  An explanation, is required.

When there is no process involved in an endeavour humans go about their business doing what they do best, whatever 
that is.  We all have different and varied skills.  The problem is trying to fit that together to form a cohesive
result.

Methodologies exist to fix this problem by directing and guiding behaviour and in doing so sometimes end up stemming 
the creative behaviour they intended to nourish.

Kanban-Zai Core takes a different approach and places constraints on what you can't do or rather what can't be done.
Leaving space for humans to do what they do best.

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

IMPORTANT NOTE:  your customisations must not contradict or countermand any aspect of the Kanban-Zai core module but
                 MAY override that of an extension but must not change the meaning of that extension.


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
If they choose not to use their voice or vote then their vote should default to the harmony setting.  Votes may not be proxied.

### MUSTER

Team members must appear on the roster.  New team members must be added.  Old team members must be removed.  This means
the roster must be current.  Only people who work with the team as direct collaborators may be mustered.  Everyone else 
must be prioritised.  Failure to maintain a current roster or inclusion of people on the roster who do not fit the 
definition of working within the team is an auditable event.

### VIGILANCE

Sometimes covens form.  A coven is a group of people within the team that share a commonality.  This commonality is good
and can lead to a better consensus.  When it becomes a clique it is the worst type of bad for a team and will destroy it.
All team members must maintain constant vigilance against cliques forming and must call them out, in addition to it 
being an auditable event.

### PAN

Sometimes depending on the situation of the team, a person expert in a specialized field, or even a mentor, by consensus
can be designated as "PAN".  Pan is a temporary designation allowing that individual veto power over a consensus for a
defined period of time.  This maybe done without running a deviation and maybe done with only a quorum. It carries with
it a maximum allowed time of 1 month.  At which time the team can again choose to redesignate the person as "PAN" again.

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

1. If cards are being planned and completed by sprint end.  All is on track.
2. If backporting is happening there is a problem with the product model.
3. If cards are not being completed and not being backported there is a fundamental problem with the team.

The fundamental problems are 
 - Prioritization Failures
 - Under resourcing
 - covens



