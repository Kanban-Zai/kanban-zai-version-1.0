# THE KANBAN-ZAI CORE.  VERSION 2. - This page is unfinished

The core of Kanban-Zai is the yaml configuration file.  This must be held in a public repo and must track all changes
from the day it was implemented.  Deviations from this are not allowed.

The first things you should note about the config file are the settings and team norms.  The settings seek to constrain
 behaviours and the norms seek to guide behaviours.

Any team member who feels they disaggree with the constraint or the norms and chooses not to be bound by them, even for
1 single instance, must be sanctioned.  

Sanctions should also be recorded if any outside influence is exerted on the team in any fashion.

It is important to note a sanction is not a punishment and no action other than a sanction should be taken.  A protest
may also be raised by the person being sanctioned.  Again this is just a record of an event happening and not a signal
to take remedial action in the traditional sense.

If a team refuses to rasie a sanction a pull request may be added to the official Kanban-Zai yaml file and a protest 
raised there.

Additionally, any individual may maintain their own Kanban-Zai yaml file and sanction or protest there.


## KANBAN-ZAI.YAML

This file contains all information about your project, or you as an individual.  From the perspective of a team it is
how they operate and from the perspective of an individual it is how they personally like to operate.

Kanban-Zai is a microservice at heart and this file may be aggregated by anyone

## SETTINGS

Settings constrain behaviours.  These constraints serve to minimise ambiguity on the team.  Ambiguity is one of the
primary causes of destructiveness in teams and just does not need to happen.  A team reaching consensus can solve many 
of the problems that arise but sometimes it is hard to reach consensus.  Therefore, arguably the most important
Kanban-Zai setting is the [CONSENSUS SETTING]().  The sole purpose of this setting is tie breaking.  It is a 
pre-determined agreed way to gain consensus if there is a tie in the voting.

The second most important is the [QUORUM SETTING]() which determines if a vote may be held or not.  You must have at 
least a quorum to hold a vote


## NORMS
 

## EXTEND

The formal process for extending Kanban-Zai is by running a deviation. This is the one and only meeting Kanban-Zai 
enforces.  Run it based on the setting in the Kanban-Zai file.

A deviation enables the team Norms and settings to be kept current and reasonable.  

## DEVIATIONS

A deviation is a formal method of changing settings.  Don't do it at any other time.  Keep it short and involve 
everybody.  

A deviation is not a retrospective in the agile sense, for example, a deviation allows you to introduce ( or remove ) 
a Team-Norm.  

You don't have to change settings in a deviation but it provides a regular opportunity for anyone to do so. However 
it is MANDATORY that only members of the team may change team settings and norms.
 
IMPORTANT NOTE: A deviation must be run regularly with the maximum time allowed between deviations being 3 monthly.  You
                must run a deviation a minimum of 4 times per year to keep your Kanban-Zai status active.
