#PROCESS - This page is unfinished

Kanban-Zai is a collaboration process.  

Conceptually the larger team is separated into 3 teams.

* Vision team       - Responsible for constraining the over-arching path the team takes.
* Scheduling Team     - Responsible for maintaining the schedule of work.
* Execution Team    - Responsible for taking a backlog of work and creating a product.

## The Vision Team

The role of the vision team is to manifest the clients vision into relevance by biting off chunks of the idea and 
producing [epics](https://github.com/Kanban-Zai/kanban-zai-core/blob/main/exposition/what-are-epics.ms) 

Every client has a winning idea, and even if that was true some winning ideas win more than others.  Sometimes other
ideas that are not as good do better at market.

This is the primary question the vision team must ask.  Is the idea viable?
 
The actual answer to that question does not matter.  Because more often than not the idea itself is not even fully 
formed.  It is the job of the vision team to fully realize the idea. 
 
The time spent doing this is determined by the [PREDICTION SETTING](https://github.com/Kanban-Zai/kanban-zai-core/blob/main/extensions/setting-predictions.md) but the method is the same.

This process must consider 3 things.

1. The Technology
2. The Business Model
3. The Zeitgeist
 
### Technology
This is less actual technology and more capability. Sometimes we are talking tech, sometimes it could be a 100 monkeys
locked in a room with typewriters.  Both are a form of automation, both provide a capability, both are scalable,
both require no extrodinary special skill on the part of the business entity.  All that matters is what can be done and
what cannot be done and how that fits the business model and the market.

### The Business Model
Plain and simple. How is this idea going to be monetized.

### The Zeitgeist
Meaning the ghost of the times it is made up of things like Market Fit, Public Appitite for the idea, The Problem 
being solved and other subjective ideas.
 
## The Golden Halo

If you imagine these 3 ideas represented by a Zen Diagram.  Inside each ring of the diagram you write the pros
and cons of the idea based on the ring they are in.  Will the market accept the idea, is the market desperate for it,
where will the technology break down, will the business model constrain the technology?  All these things must be 
considered and arranged into the diagram.  Negatives push the rings apart and positives pull the rings together.  If
all 3 rings align exactly ontop of one another then you have achieved the GOLDEN HALO and you are onto a guaranteed winner.

More often than not this will not happen and you will now be considering..."The Zen Diagram of fuckedness"

        [ PICTURE OF THE ZEN DIAGRAM OF FUCKEDNESS ]
        
                      Business model --- Technology
                                  Zeitgeist

The viable part of your idea sits at the intersection of the 3 rings.  The larger the intersection the more viable the 
idea.  The goal is to make that intersection as large as possible and fit as much in there as possible THAT IS RELEVANT
to the idea at hand.  Only this way can you get a clear picture.

Of course the Z.D.O.F is a communication concept rather than a magical measuring tool.  Discovering the viability and
realizing and idea are a hard problem that generally requires multiple collaborators.  Do not minimise lightly this part
 of the process.  
 
As the saying goes.  The feet walk where the eyes lead.  It does not work that well the other way around. 

### Descoping.
At this point there will be a product starting to form.  To build an epic you must now winnow it down to just the 
important parts and remove everthing that is not important.

Budget must also be managed as part of the vision.  Epics must be assigned budgets and both aggreed with the client 
before handing off to the scheduling team.  At this point only a ballpark figure should be set on the amount of time
it will take to execute this epic.  There also should be no delivery date aggreed but a priority of 1-3 should be set.


## The Scheduling Team
Another saying goes the best laid plans of mice and men...refering to how plans can go wrong
But you actually have to have a plan first in order for it to go wrong.  That's where this team comes in.

Epics come in and listed in priority order.  They are broken down into sensible sized chunks and put into the backlog.
These chunks are listed in execution order.

### Breakdown
### storys
### prioritizing
### projection deadlines


## The Execution Team
Primarily comprised of developers, testers, dev ops, security advisors.

There is no measure of velocity in Kanban-Zai. The execution team takes work from the 
backlog in sized chunks.  

There is a measure of tense in Kanban-Zai.  Tense is used in the same way as it is 
normally used past tense, future tense.  At the start of a project the whole team will be working "Past Tense".  
The goal being to move to "Future Tense".

The ability of a team member to split and join cards as needed is a required part of the process.

### Consensus and breaking an impasse.
When the team votes there are 3 types of vote, yes, no and undecided. In a situation where the yes and no votes are even
then the undecided votes are no.

If there are no undecided votes 
* then the product owner may override prodcut decisions.
* the [consensus setting](https://github.com/Kanban-Zai/kanban-zai-core/blob/main/extensions/setting-consensus.md) decides the outcome


### Sprints
One week sprints are strictly enforced in Kanban-Zai.  This is because there is no velocity measure.  So instead we
use 1 week as a yard stick.  The idea is to take only what you can finish in one sprint.  Finish it an then move onto 
the next.  Biting of a little chunk at a time.  Of course in practice this requires skills that almost nobody has.  

Formally you do not have to finish the chunk of work you pickup in a week, but continually improve your card writing 
until you do.  The way this happens is this.  By using 1 week as a measure, when you get to the end of one week, take
what ever work you have not completed and transfer it to another card to be played next week.  Then rewrite the
current card to accuratley represent what has been done.  This is now what will be tested and delivered.  Repeat this
process every week.

Overtime the goal is to improve the individual and team ability to write execution cards.  The two primary areas to 
focus on when writing cards are, as in agile, value and comprehension.  In Kanban-Zai there is another factor to 
consider. "Value over time", this happens naturally in Kanban-Zai because of the 1 week sprint enforcement however
the time tense must eventually be changed to "Future tense".  At this point predictions can begin to be made about 
delivery times.  Tense is not a Kanban-Zai setting and the tense will be different on different parts of your project.
Tese just acknowledges where you are in your thinking and actions around a particular part of your project.  If your 
project is small you are likley to only refer the entire project tense, on a bigger project, different aspects will
have different tenses.  It is important to know tht predictions about delivery can only be made when you are working
in "Future Tense".