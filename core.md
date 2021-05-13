# INTRODUCTION

The Kanban-Zai code is a process framework designed to make teams work better and go faster.

# DESCRIPTION

Kanban-Zai core is a container framework.
 
It's purpose is to wrap another process ensure that the rules, procedures and boundaries of the wrapped process are 
adhered to and provides mechanisms to document deviations from that child process.

The core must be used by ALL (100%) Kanban-Zai implementations

Once the core is installed you can create and extend it with any process you like by following the principles laid 
out in the core but the meaning and intent of the core module may not be modified by any extension


...


At it's heart Kanban-Zai is a microservice and the centerpiece is the Kanban-Zai.yaml configuration file.
 
This file documents the settings, values and behaviours the process defines and the team works within, must be held in a 
public repo and should be kept up to date to keep those settings, values and behaviours current and reflective of the
current time. All changes to this file must be tracked.


...


To use Kanban-Zai you must extend the core.  

The simplest way is to import the modules from "kanban-zai-process-101".  The modules all import settings, values and
behaviors into the Kanban-Zai.yaml file.  You now have all you need to get a team running.

You can also create your own extension by using the "kanban-zai-process-101" as a template for definine your own 
extension.

norms, settings, values must have a link on the web to describe it

IMPORTANT NOTE:  your custom module must not contradict or countermand any aspect of the Kanban-Zai core module.



# Overview of the KANBAN-ZAI.YAML file.

## VALUES
The default working mindset of any Kanban-Zai team is encapsulated in the principles of :-
 
### AUTOMATION
What this means is that constant discipline is to automate as much as possible.  Anything that can be automated, must be.

### EVIDENCE
Evidence must be continually collected and evaluated but acted upon only when its provenance is assured.  

### INTUITION
Where automation and evidence will not provide outcomes the teams ability to use their collective intuition must be 
relied on. 

### DISCIPLINE
Disciplined application of these values will build trust, efficiency and scalability.

## SETTINGS
Settings constrain behaviours.  These constraints serve to minimise ambiguity on the team.  Ambiguity is one of the
primary causes of destructiveness in teams and does not need to happen.
 
 * version: 2 (readonly may not be modified)
 * harmony: positive
 * quorum: 2
 * deviation: monthly
 * sprint: 5 days (readonly may not be modified)
 * roster: [array of names]
 * core: https//github.com/Kanban-Zai/kanban-zai-core/blob/main/modules/culture.md
 * culture: link to culture module
 * continuity: link to continuity module
 * vision: link to vision module
 * scheduling: link to scheduling module
 * delivery: link to delivery module
 * custom: link to your custom module outlining settings and norms unique to your team
 
### harmony

Possible Values: positive | negative  DEFAULT: positive

A team reaching consensus can solve many  of the problems that arise but sometimes it is hard to reach consensus.  The sole purpose of this setting is tie breaking.  It is a pre-determined agreement to gain consensus if there is a tie
in the voting.

### quorum

Possible Values: any number value smaller than your team size.  DEFAULT: 2

determines if a vote may be held or not.  You must have at least a quorum to hold a vote.

### deviation

Possible Values: any time value with max 3 months.  DEFAULT: 1 month

### sprint

This value is the yard stick by which you measure your ability as a team.  It is the length of one execution of work.
All work taken into a sprint MUST be finished OR the work left over split into another card and put into the next sprint.

Possible Values: Readonly may not be modified.

### roster

current members of the team.  Must sit with the team, attend team meetings and generally be involved in the team and sit
inside the team process.

## TEAM NORMS

### FOLLOW

Follow The Process.

The Kanban-Zai process can be thought of as a cybernetic algorithm.  It is a process that lets computers do the things 
they are good at and humans do the things that they are good at.  One should not mess with the other.  

THIS NORM ABOUT FOLLOW PROCESS AT ALL COSTS NEEDS TO BE WRITTEN BETTER


### AUDIT 

An audit is simple a record in kanban-zai.yaml of an auditable event.

What events are auditable?

* any outside influence is exerted on the team in any fashion.
* any action by any team member is in opposition to the settings or team norms.
* any consensus choice that was in opposition to the settings or team norms.

Who can audit?

* any rostered team member

### PROTEST

It is important to note a audit is not a punishment and no action other than a audit should be taken.  A protest
may also be raised by the person being audited.  Again this is just a record of an event happening and not a signal
to take remedial action in the traditional sense.

What is protestable?

* any circumstance where an audit should have happened but did not.
* any circumstance where an audit did not have happened but should have.
* a pull request may be added to the official kanban-zai.yaml file and a protest raised there if absolutley necessary. 
* any individual may maintain their own kanban-zai yaml file and audit or protest there.

Who can protest?

* any rostered team member

Who can protest through official channels

* any team member pas or present

### DEVIATE

A deviation is a formal method of changing settings.  Don't do it at any other time.  Keep it short and involve 
everybody.  

A deviation is not a retrospective in the agile sense, for example, a deviation allows you to introduce ( or remove ) 
a Team-Norm.  

You don't have to change settings in a deviation but it provides a regular opportunity for anyone to do so. However 
it is MANDATORY that only members of the team may change team settings and norms.

IMPORTANT NOTE: A deviation must be run regularly with the maximum time allowed between deviations being 3 monthly.  You
                must run a deviation a minimum of 4 times per year to keep your Kanban-Zai status active.
