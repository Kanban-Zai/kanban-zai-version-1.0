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
 
It's purpose is to wrap another process ensure that the rules, procedures and boundaries of that process are 
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

To do this.  Create your own kanban-zai.yaml file and add your settings and norms to it.  You can also choose to implement
modules.  Modules are pre-defined sets of constraints and team norms, with an accompanying explanation of how to use 
them.  You should also add the "extend" property pointed to the extension you are extending from.  Most times this will
be the Kanban-Zai core.

IMPORTANT NOTE:  your customisations must not contradict or countermand any aspect of the Kanban-Zai core module but
                 MAY override that of an extension but must not change the meaning of that extension.


# REQUIRED TEAM NORMS

These must be adopted by all Kanban-Zai teams and may not be overridden or changed.

### AUDIT 

An audit is simple a record noted in your kanban-zai.yaml of an auditable event.

What events are auditable?

* any outside influence is exerted on the team in any fashion.
* any action by any team member is in opposition to the settings or team norms.
* any consensus choice that was in opposition to the settings or team norms.
* any change to the Kanban-Zai.yaml file

Who can audit?

* any rostered team member


### DEVIATE

A deviation is a formal method of changing settings.  Don't do it at any other time.  Keep it short and involve 
everybody.  

A deviation is not a retrospective in the agile sense, for example, a deviation allows you to introduce ( or remove ) 
a Team-Norm.  

You don't have to change settings in a deviation but it provides a regular opportunity for anyone to do so. However 
it is MANDATORY that only members of the team may change team settings and norms.

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

### VOICE

Everyone on the team must have a voice at the table. if they choose not to use thier voice then their vote should default
to the harmony setting.

### MUSTER

Team members must appear on the roster.  New team members must be added.  Old team members may be removed or left in the
roster.

# REQUIRED SETTINGS

### harmony

Possible Values: positive | negative  DEFAULT: positive

A team reaching consensus can solve many  of the problems that arise but sometimes it is hard to reach consensus.  
The sole purpose of this setting is tie breaking.  It is a pre-determined agreement to gain consensus if there is a tie
in the voting.  If someone chooses not to abstain this becomes their vote.  Please note, this means there is no way in 
Kanban-Zai to abstain.

### quorum

Possible Values: any number value smaller than your team size, but greater than 1.  DEFAULT: 2

Determines if a vote can be held or not.  You must have at least a quorum to hold a vote.

### deviation

Possible Values: any time value with max 3 months.  DEFAULT: 1 month

### sprint

Possible Values: 1 working week.  (Readonly may not be modified.)

This value is the yard stick by which you measure your ability as a team.  It is the length of one execution of work.
All work taken into a sprint MUST be finished OR the work left over split into another card and put into the next sprint.


