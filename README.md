# Kanban-Zai.  Revision 2.  The serenity update.

## The elevator pitch

Kanban-Zai (KBZ) R2 is a way for new software development teams start smoother.

## Why would anybody do this?

Software development is complex.  There are many hidden pitfalls.  Kanban-Zai is a tool to keep your compass pointing
in the direction you want to travel.

## How does it work?

Kanban-Zai introduces 3 new concepts.

1. Soft consensus

    Each team member has 1 vote.  This includes the client representitive who woks daily with the team.  If you 
    do not work daily with the team you should not consider yourself part of soft consensus.
    
    Occasions will occur when a dilemma is encountered, a decision affecting the team or outcome must be made.  In such
    a case a vote should be taken and the result respected amongst the team.
    
    Soft consensus accounts for the fact that not all people on the team will have as much experience as some others
    and may not full understand the consequences of decision they are making and therefore must be guided.  Not directed.
    
    Soft consensus should be made in good faith with the future of the team in mind and therefore the future of the
    team output.

    note: Undue Influencers.  This can happen in a soft consensus situation.  It could be a stakeholder, tech lead,
          senior dev, more experienced person.  Undue influencers should be resisted by the team, for the overall good
          of the team.

2.  Team norms

    Sometimes the way forward is unclear because many people have good ideas, many people have bad ideas or many people
    have no ideas.  Team norms gives you the chance to make a choice (good, bad or ugly) and move forward without
    to much overhead.
    
    A team norm is a behaviour that the team, through consensus, decides is the correct way "FOR NOW" to handle any
    given situation.  It should be printed on paper and plastered all over the walls.  It should be repeated amongst the
    team continuously like a mantra.  When a team member does not follow a norm it should be pointed out to them.
    
    Team norms should be tried for a period of time and reviewed.
    
3.  Extensions

    Because the core can never be modified by your team, extensions give your team a way to add their own flavour to 
    Kanban-Zai.

## Can anybody use Kanban-Zai?

It's open source.  So yes.

## Are there any limitations of its use.

These are specified in the license.

The rationale behind Kanban-Zai formed from more than 20 years of experience in the trenches of waterfall and agile 
and can be reduced to 3 observations.

* Software Development is a creative process.
* People can operate optimally in creative mode or survival mode, but not both.
* The best creative work comes when you empower everyone.  

However, for this explanation to make sense you must accept that current methods of working can be improved upon.  A 
fuller explanation can be found in [The Kanban-Zai Core](./core.md)

## IMPLEMENT

To implement Kanban-Zai in your project all you need to do is formally adopt the core by creating your own 
kanban-zai.yaml file in a public code repository of your choice.  This is a living document that file formalizes the 
ethical behaviours and boundries of your team.

THE RULES:
* It must be held in a public repo.
* All changes to this file must be tracked.
* It must be kept current and reflective of the present.
* May only be modified by rostered team members.



## EXTEND

Next specify which core extension you are extending from.  All kbz implementations must extend from the core, 
ultimately.  This means you can extend from another extension that ultimately extends from the core. 

Not specifying an extension implies you are extending from the latest core module, but the preference is that an origin 
should be explicitly stated.

From this point you add your own claims, settings, modules and norms to that kanban-zai file and you are running a 
Kanban-Zai team.

Rejoice!

### What is an extension?

An extension defines a delivery process.  The method your team is going to use, to get from idea stage to product and 
how it is going to keep doing that or when it is going to stop.  

In other words in defines the objective behaviours, processes, values and goals for yout team.

The rules of extension:

* The core must be used by ALL (100%) Kanban-Zai implementations
* Once installed you can extend it with any process you like by following the principles laid out in the core.
* You may add a module to your Kanban-Zai file with the "implements" property.
* The meaning and intent of the core module may not be modified by any extension, module or customisation.
* All properties of an extension or module must be inherited, including other upstreams that they extend from.
* You may not remove any properties of an extension or module.
* You may not modify read only properties of an extension or module.
* You may only change the properties of an extension or module to the values, if specified, of the extension or module.
* If there is a property that does not work for you then do not use that extension or module.  Create your own.
* Your customisations must not contradict any aspect of the Kanban-Zai core or any extension or module you use.

### What is a module?

Modules a pre-packaged collections of Kanban-Zai concepts and ideas that you might want to include in your process.

SANITY CHECK:

* You should probably not create your own extension or module unless you have some experience in Kanban-Zai.  
* Additionally, you should not nest your implementation to deeply.
* You should probably just extend from the core in most cases.

## CONTRIBUTE OR JOIN!

[Join the slack channel](https://join.slack.com/t/kanban-zai/shared_invite/zt-tdcgnpbm-xUoEytz6XbV16cmyPGPUSQ)

If you have something to add please submit a pull request. If you would like to help curate and guide Kanban-Zai then
 request to join the crew through the [github team](https://github.com/Kanban-Zai).

## COMMITMENT

Kanban-Zai core will be continuously improved, however no minor version will ever change the meaning of the major 
version.  If there is a significant deviation in meaning the minor version will then become the next major version.

Any changes to any version of the core will be done conservatively and as a result of robust debate.

 
#### PERSONAL RECOMMENDATIONS

It’s mentally tough trying to explain simplicity to people. 
They all want it to be difficult, I think. It isn’t really.

##### Edward (name and company withheld)


## CREDITS

    These people had a direct hand in the development of Kanban-Zai whether they knew it or not.
    
    Max Aston https://www.linkedin.com/in/maxashton/
    Zsolt Varszegi https://www.linkedin.com/in/zsolt-varszegi-70bb94195/
    Sunil Patel https://www.linkedin.com/in/sunilpatelqa/
    Suki Bains https://www.linkedin.com/in/suki-bains-0745473/
    Paul Sanderson https://www.linkedin.com/in/paul-sanderson-27a6731a5/
    William Tonkin-Howe https://www.linkedin.com/in/william-tonkin-howe-1b57843/
    Andy Hoyle https://www.linkedin.com/in/andyhoyle/
    
    These people, over the years, provided some of the inspiration behind the creation of Kanban-Zai,
    and they probably have no idea about that fact.
    
    Zak Holdsworth https://www.linkedin.com/in/zakholdsworth/    <-- this guy
    Howard Van Rooijen https://www.linkedin.com/in/howardvanrooijen/
    Edward scotcher https://www.linkedin.com/in/edwardscotcher/
    Raf Rasile https://www.linkedin.com/in/rafrasile/
    Cyrus Richardson https://www.linkedin.com/in/richardson/
    Sarah Yock https://www.linkedin.com/in/sarah-yock-689ba6b/
