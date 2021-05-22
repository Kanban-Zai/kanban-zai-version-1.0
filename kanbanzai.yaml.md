
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