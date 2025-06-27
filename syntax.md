```python
func <name>() {
    ...
}



@s - an object of the current entity executing this function
@n - an object of the nearest entity
@p - an object of the nearest player
@a - an array of all players
@e - an array of all entities



<object>.<property> - used for finding the property of an object
<array>[<filter>].<property> - used for finding the property of specific objects in an array
#[directive] - compiler directives

i.e.

@s.name - the name of the entity executing the function

@a[tag=hello].name - the names of every player tagged 'hello'

#namespace 'Beans' - all custom functions placed under this


sayf(<text>, <format>); - says the formatted string 

tellraw(<json>); - says the 'text' attribute, with some modifiers allowed

on(); - runs the following code on an event

at(); - runs the following code on an object(s)


```