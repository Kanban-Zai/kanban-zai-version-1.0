# INTRODUCTION

The Kanban-Zai code is a process framework designed to make teams work better and go faster.

# DESCRIPTION

Kanban-Zai core is a container framework.
 
It's purpose is to wrap another process ensure that the rules, procedures and boundaries of that process are 
followed and provides mechanisms to document deviations from that child process.

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

The simplest way is to specify the url of the extension module you are implementing in the EXTENSION property of your 
kanbanzai.yaml file 

norms, settings and values are inherited from the extension file.

You may further customize your implmentation by describing your own norms, values and settings.  This is done in the 
same way by using a key value pair.  In this case the property is the name you are introducing and the value is a url to 
the full description of the customisation located somewhere on the web.

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

### PROTEST

It is important to note a audit is not a punishment and no action other than a audit should be taken.  A protest
may also be raised by the person being audited.  Again this is just a record of an event happening and not a signal
to take remedial action in the traditional sense.

What is protestable?

* any circumstance where an audit should have happened but did not.
* any circumstance where an audit did not have happened but should have.
* a pull request may be added to the official kanban-zai.yaml file and a protest raised there if absolutley necessary. 
* any individual may maintain their own kanban-zai yaml file and audit or protest there.

Who can protest on a team?

* any rostered team member

Who can protest through official channels

* any team member past or present

### DEVIATE

A deviation is a formal method of changing settings.  Don't do it at any other time.  Keep it short and involve 
everybody.  

A deviation is not a retrospective in the agile sense, for example, a deviation allows you to introduce ( or remove ) 
a Team-Norm.  

You don't have to change settings in a deviation but it provides a regular opportunity for anyone to do so. However 
it is MANDATORY that only members of the team may change team settings and norms.

IMPORTANT NOTE: A deviation must be run regularly with the maximum time allowed between deviations being 3 monthly.  You
                must run a deviation a minimum of 4 times per year to keep your Kanban-Zai status active.
