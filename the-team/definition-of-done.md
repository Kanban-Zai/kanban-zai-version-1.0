# D.O.D

Badges define the definition of done for a card.

There are 3 default badges available in Kanban-Zai but your team can define any badges they
want.  However you must not use the Kanban-Zai assigned names.

## Standard

All cards are standard cards unless a badge has been deliberatley included on the card.  
The default standard behaviour is to do only what is neccasary.  The simplest thing to achieve the goal usually to make 
test pass but as not all projects are TDD consider that developer scope is limited.  It this case the simplest this quite 
synonomous with "The least work right now", regardless of the technical debt this would undoubtedly create.

## Investigation Required

By choosing this badge the team expects and acknowledges this card will involve a lot of investigation and will take 
more time and may only result in a series of cards being written.  
Any solution that comes is probably going to be neccasarily more complicated but that there is limited scope for 
intervention by the developer however unexpected code changes should now be expected.

## Carte Blanche

This badge indicates that this card is most likley going to be a full rewrite of the system.  
The system will have to be investigated and a report given back to the team before an actual rewrite took place.  
The team should expect this card to extend over sprints depending on what is involved BUT regular updates must be made.
This badge gives unlimited scope to the developer and acknowledges that the team will make an assessment on a TBD time 
basis.

