# Disclaimer
I did not make this script; I just updated it to make it work so no one else will have errors.

**Mythic Hospital**

This is a lightweight hospital & limb damage resource. This was largely done as an experiment, so some of it is rough around the edges.

**Dependencies:**

- [Pillbox Interior](https://forum.fivem.net/t/release-pillbox-hospital-by-jobscraft/209288)

NOTE: While I have removed my framework base as a dependency, there are some aspects of this that do not work because of that. As such, it will be up to you to implement them. You'll need to add things like billing to take money from the player, syncing injuries in the database so they're persistent, adding usable items for the various effects, etc.

EXTRA NOTE: This has functions for using /bed for RP purposes, but it does require you to add your own command for it (since I'm using my chat resource). Just simply register a command that has TriggerClientEvent('mythic_hospital:client:RPCheckPos', source)

Discord Invite
https://discord.gg/gN2F8VpyNY
