# When are you done?

The definition of done is about how much technical debt is ok.

# weak

Do not address technical debt.  Document it only.

# progressive

Address technical debt that work on this card produces.

# Aggressive

Address all technical debt you find within the scope of the card.  Bigger problems
should be documented but not modified unless Carte Blanche scope is granted.

Warning: under this setting cards should have long completion times.

# Scope

Scope Badges set the boundries of the work that can be done on any given card.  Another way to 
say this is how many other systems are you allowed to touch.  The word system is dependent on context.
If you are working at the function level then other functions are the system. At machine level other machines
are the system.

## limited

The work assigned to a card should be tightly constrained and the work to complete the card
 should be considered only do what is necessary and do no work that is not documented on the card.

Ostensibly this simplest thing to achieve the goal that makes a test pass.  This is stating explicitly that
only Test Driven Development projects should run with this setting.

Consider that developer scope is limited.  It this case the simplest thing is quite synonymous with 
"The least work right now", regardless of the technical debt this would undoubtedly create.

## constrained 

Work assigned to this type of card may address a larger scope than the previous setting.  Primarily this is where this 
card touches other parts of the system.  The team must define how far this is.

## Carte Blanche

The amount of work assigned to a Carte Blanche card should be similar to the previous setting but the 
developer has the permission to follow as many threads as needed to address the bigger picture.


# Card sizing

Sizing is different on every team and changes over time.  Kanban-Zai recognises this
and does not impose a particular method of sizing work.  Choose the one the best suits.

However you must choose one of the following settings.

# Time

Generally cards will be broken down into small chunks and pointed in time

# Story Points

Fibbonaci sequence pointing

# Tee-Shirt Sizing

 This setting enforces the t-shirt sizing of cards - xs, s, m, l, xl


