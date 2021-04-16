# What are settings

## version: 1

    This is the version of Kanban-Zai the business has commited to up holding.

## cards-only

    All work must be done as a result of a card in play.  Even investigation of other cards.  Cards may
    be written and put into the backlog for later scheduling but only as a result of a card in play. Any 
    work done, not as a result of a planned card MUST be reversed out of the repo.  
    
    Types of card in Kanban-Zai
    
    * Bugs
    * Stories
    * Spikes
    * Technical Debt
    
    never | BAU only | Project only | Always
   
## boy-scouting

    Boys Scouts like to investigate.  Find problems to fix.  Because they have time on their hands.
    This can sometimes be a very helpful behaviour and sometimes it can be problematic.
    
    never | BAU only | Project only | Always
    
## tinkering: never
    
    Tinkering is the process of changing the codebase in off card fashion, usually as a result of boy scouting.  If 
    tinkering happends outside of the setting limits it must be reverted out of the codebase.

    never | BAU only | Project only | Always

## bugs: never

    If a bug is found mid sprint ( remembering a sprint is 1 week ) how should it be handled?  Never is the equivilent
    of a card being scheduled.  For bugs usually this would be the next sprint, but it would depend on scheduling.  
    Always implies it should be the next card someone picks up.

    never | BAU only | Project only | Always
    
## pairing: undefined

    Kanbanzai has no concept of pairing
    
## speed-limit: 2

    The amount of cards the team can work on at once.  This is  strict limit that must be adhered to.
    
## payback-tech-debt: never

    How much effort should be put into paying back technical debt as part of a cad this sprint?  Never in this context 
    means a card should be written about it and it should be handed off to the scheduling team.
    
    never | BAU only | Project only | Always

## card-sizing: T-Shirt

    T-Shirt Sizing | Complexity Points

## card-scope: card-only

    Card-only | 

## sprint-length: 5 days

    This setting is an unchangable Kanban-Zai only setting. You may not change it.  It lends some interesting properties
    to the other settings.  Primarily it limits the amount of time tht any one card can be worked on.  if a card goes
    over this setting you MUST split the card.
    
## quroum: 2

    What is the minimum number of votes required to achieve a consenus.  If at least this number of eligble voters
    are present a vote MUST note be taken.

## deviation-frequency: 1 month
    
    A deviation meeting must be run at this frequency giving everyone the  chance to have a voice about the team 
    settings


## Lead time: 12 weeks
    
    How far in advance should the vision team speculate?
    
    
## Definition of done.

It is hard to quanify a good definition of done.  It will vary from team to team.  Kanban-Zai enforces these settings 
payback-tech-debt, card-sizing, card-scope, sprint-length to help put a tangible boundry in place.  These alone allow
you an oobjective measure of when it is time to stop working on a card.

Additionally you may add other measures.  Some good ones are...

* Acceptance Criteria
* Unit Tests
* End to End Tests
* Smoke tests
  
      