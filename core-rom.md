# Rational Outcome Models

ROMs are gateway constraints.  They can either define a minimum or maximum set of requirements to break the constraint. 
Once broken the subject of that constraint may proceed to the next stage of whatever process is guiding it.

For example.  The value model defines what must be included on a card before it can be considered for processing.  Once
the constraint is broken the card may be passed to the delivery team for completion, but until then it must remain on 
backlog.

Passing a subject through a gate without first breaking the constraint is a journalable action.  This can often happen 
because an inherited ROM might not fit your exact situation.  DON'T PANIC.  Create your own ROM.  It is not a 
requirement to extend from another ROM, just that you have them.

# product-rom

The product model represents the set of business rules of a product.  Primarily it should define what is not allowed 
in a product model rather than what is allowed.  It should also define how value cards should be derived from the
product model.  

In the un-extended core this rom is effectively an empty shell.

# value-rom

This model defines what must be specified before a card can be considered for quality delivery.

In the un-extended core this rom is effectively an empty shell.

# quality-rom

This model defines what is required to deliver quality value.

In the un-extended core this rom is effectively an empty shell.

# Anathema Model

Be all things to all people in all device on all platforms. This is considered an irrational outcome.  There is a 
scenario where this model is rational.  When you have a near infinite budget, or at least not something you ever have
to think about.
