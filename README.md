# Permanence
Forcefully permanent objects for fabric

# What
The goal of the api is to create a new 'world object type' in minecraft, so far we have\
**Items** - can be stored in inventories, or can exist in the world as ...\
**Entities** - Entities are not bounded by the block grid unlike ...\
**Blocks** - Grid-bounded objects that make up the majority of the minecraft world\

Permanence introduces the **Permanent** world object type, this is a new type that (ideally) cannot be destroyed, and only converted.
The api itself should be designed such that it is impossible to delete Permenents, so no trash cans, no void tanks, no cheating.

# Why
Pollution, and Magic Flux are examples of Permanent types. A real life example would be Energy, energy cannot be destroyed, however unlike energy, Permanents can be created.\
I do intent on adding destructable Permanents if for example you want to be able to scrub or delete it, but personally I find it more fun if instead you're forced to contain or isolate your creations.
