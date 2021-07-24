# How to use kanban-zai.yaml

##settings

A setting must be inherited from an extension or module.
You may also create your own as long as they don't exist in a parent.
if they do exist you may still place them in your yaml file but only as explicit notice that you use that setting
you may change the value of that setting on 2 conditions

1.  if there is a constraint in-place you must respect it.  This means the only values you may choose are specified
in the first parameter of the setting.

2. If it is read only you may only use the default value specified by the parent yaml file.

when you create your own setting you may constrain it as you like using the following format

number|MAX:10|MIN:3|READONLY|DEFAULT:some number
string|READONLY
list|READONLY|MAX:number|MIN:number|READONLY|DEFAULT:some number or string - in this case if there is not default 
specified the first item in the list is the default.
boolean|READONLY|DEFAULT:boolean
the type of the setting must never change.  It must remain the same type everywhere.

##norms

a norm consists of a name string and associated documentation in the module or extensions the norm originates from
additionally a norm may have a uri address that leads to a public declaration of that norm.

## Labels

    Form like label: ( <text><colon> )
  
used to seperate contexts in norms and settings

## Claims

claims must extend from the parent claim if the parent claim exists.
