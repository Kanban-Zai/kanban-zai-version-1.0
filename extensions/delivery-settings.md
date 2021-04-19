# Predictions

    Determines wether or not the team will target deadlines strictly or loosley.
    
    * LOOSE - Prioritizes larger chunks of the idea for consideration and more time in the ideation phase leading to 
              clearer goals in  the execution phase.
    * STRICT - Prioritizes smaller chunks of the idea for consideration and less time in the ideation phase but 
              potentially longer time in the execution phase.
              
# cards

    how much time should you deliberate about cards?
    
    Types of card in Kanban-Zai
    
    * Bugs
    * Stories
    * Spikes
    * Technical Debt
    
    Values:
    1. default    - only product development work, bugs, tech debt & spikes will be handled as part of
                    the card 
    2. bugs       - Track bugs seperatley
    3. Tech Debt  - Track Tech debt and bugs seperatley
    4. spike      - Track Tech debt, bugs and spikes seperatley
    
    
# Backlog Length

Is a constraint that forces the team to maintain a backlog no longer that 
the backlog-length setting which defaults to 12 weeks.

## card-scope: card-only

    Card-only | 
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
     
## payback-tech-debt: never
   
       How much effort should be put into paying back technical debt as part of a cad this sprint?  Never in this context 
       means a card should be written about it and it should be handed off to the scheduling team.
       
       never | BAU only | Project only | Always

 
## Definition of done.

It is hard to quanify a good definition of done.  It will vary from team to team.  Kanban-Zai enforces these settings 
payback-tech-debt, card-sizing, card-scope, sprint-length to help put a tangible boundry in place.  These alone allow
you an oobjective measure of when it is time to stop working on a card.

Additionally you may add other measures.  Some good ones are...

* Acceptance Criteria
* Unit Tests
* End to End Tests
* Smoke tests
  
      