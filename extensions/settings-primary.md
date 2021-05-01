# version:

    This is the version of Kanban-Zai the business has commited to up holding.

# Consenus

    This setting is used to break and impasse in the team consenus voting
    system. It determines the bias of unsure votes.
    
    * positive  - if yes and nos are even the consensus is yes
    * negative  - if yes and nos are even the consensus is no
    
# quroum

    What is the minimum number of votes required to achieve a consenus.  If at least this number of eligble voters
    are present a vote MUST note be taken.  The result of the vote is an interim measure to avoid stalling the team.
    And a date must be choosen for a full consenus vote including all team members.
    
    If a quorum cannot be achieved then no vote should be take and no decision made.  
    
    If a decision is made without the minimum of a quorum then a audit must be raised.

    If a full consenus vote is not chosen a audit must be raised.
  


# deviation-frequency: 1 month
    
    A deviation meeting must be run at this frequency giving everyone the  chance to have a voice about the team 
    settings
    
## sprint-length: 5 days ( READ ONLY )

    This setting is an unchangable Kanban-Zai only setting. You may not change it.  It lends some interesting properties
    to the other settings.  Primarily it limits the amount of time tht any one card can be worked on.  if a card goes
    over this setting you MUST split the card.
   
   ## speed-limit: 2
   
       The amount of cards the team can work on at once.  This is  strict limit that must be adhered to.
       
   
## definition-of-done: strict
   
    When do you finish?