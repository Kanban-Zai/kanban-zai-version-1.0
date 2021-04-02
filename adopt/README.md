To adopt Kanban-Zai create a github repo and include the kanban-zai.yaml template within
the repo.  You must have this file in your repo to say you are running a Kanban-Zai team

The YAML file must contain all top level properties.  The top level properties may not be renamed
or removed.  

Currently these properties are as follows.

* version
* settings
* sanctions
* feedback

##Creating a setting

      type: recordtype
      name: settings
      value: example
      status: default
      modifiable: false
      consensus: none
      required: true
      description: Records the current and past settings of your team.  This is your teams extension of Kanban-Zai.
      on your team.
      date: 01/01/2021
      

### Property Documentation
    type - Defines the recordtype.  Can be any of the following values [ about | setting | norm ]
    name - Setting name.  Currently one of [ card-sizing | card-scope | card-definiton-of-done ]
    value - Any text value
    status: default
    modifiable: false
    consensus: none
    required: true
    description: Records the current and past settings of your team.  This is your teams extension of Kanban-Zai.
    on your team.
    date: 01/01/2021
##Creating a setting
 