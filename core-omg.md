# Objectively Model Gates

OMG's are an ordered collection of criteria that determine the state of a work item.  All criteria must acquire for
a gate to pass and higher numbered gates cannot acquire before lower gates.

Promoting a work item through a gate without the gate first acquiring is a journalable action.  As is regressing.

 
# 1: IDEA
* an idea must be agreed by a quorum

# 2: READY
* Has acceptance criteria

# 3: WIP
* all acceptance criteria have been fulfilled

# 4: COMPLETED
* has been merged into master
