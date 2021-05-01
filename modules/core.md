# THE KANBAN-ZAI CORE.  VERSION 2.

All Kanban-Zai modules introduce and explain settings and team norms.  The system can be tailored to the needs of a 
team.  

* This core module introduces the base concepts of Kanban-Zai and some initial settings and team norms.
* The core module may not be modified.
* The core module must be used by ALL (100%) Kanban-Zai implementations

## KANBAN-ZAI.YAML

The core of Kanban-Zai is the yaml configuration file.  

* This must be held in a public repo.
* All changes must be tracked from the day it was implemented.

This file contains all information about your project, or you as an individual.  
From the perspective of a team it is how they operate and from the perspective of an individual it is how they 
personally like to operate.

Kanban-Zai is a microservice at heart and this file may be aggregated by anyone.

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

current members of the team.  Must sit with the team, attend team meetings and genrally be involved in the team and sit
inside the team process.

## TEAM NORMS

### audits 

An audit is simple a record in kanban-zai.yaml of an auditable event.

What events are auditable?

* any outside influence is exerted on the team in any fashion.
* any action by any team member is in opposition to the settings or team norms.
* any consensus choice that was in opposition to the settings or team norms.

Who can audit?

* any rostered team member

### protests

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

### deviations

A deviation is a formal method of changing settings.  Don't do it at any other time.  Keep it short and involve 
everybody.  

A deviation is not a retrospective in the agile sense, for example, a deviation allows you to introduce ( or remove ) 
a Team-Norm.  

You don't have to change settings in a deviation but it provides a regular opportunity for anyone to do so. However 
it is MANDATORY that only members of the team may change team settings and norms.

IMPORTANT NOTE: A deviation must be run regularly with the maximum time allowed between deviations being 3 monthly.  You
                must run a deviation a minimum of 4 times per year to keep your Kanban-Zai status active.


## EXTEND

The formal process for extending Kanban-Zai is by running a deviation. This is the one and only meeting Kanban-Zai 
enforces.  

During a deviation AND AT NO OTHER TIME, team members vote on what their specific implementation of Kanban-Zai will
look like by deciding what modules will be adopted and what modules will be shed and what values the settings of
each module should have, enabling them to be kept current and reasonable. 

Run it based on the setting in the Kanban-Zai file.
 