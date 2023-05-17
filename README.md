# Diclamer
I did not make this script I just updated it to make it work so no one else will have errors.

# Mythic Hostpial
This is a lightweight hosptial & limb damage resource. This was largely done as an experiment so some of it is rough around the edges.

Dependencies :
- [Pillbox Interior](https://forum.fivem.net/t/release-pillbox-hospital-by-jobscraft/209288)


> NOTE: While I have removed my framework base as a dependency, there are some aspects of this that due not work because of that. As such it'd be on you to implement. Need to add things like billing taking money from the player, syncing injuries in database to they're persistent, adding usable items for the various effects, etc.

> EXTRA NOTE: This has functions for using /bed for RP purposes, but does require you to add your own command for it (As I'm using my chat resource). Just simply register a command that has TriggerClientEvent('mythic_hospital:client:RPCheckPos', source)
