# Raid Guide

## Joining Raids

## Hosting Raids

### Raid Command

> The `!raid` command in Nexus is the primary method for Host to create raids and can be used in any channel. It can be used simply as `!r` or as a full meal deal. All command `<inputs>` are optional but must be used in order otherwise Nexus will give an error. 

> `![raid|r] <pokemon> <time_left=45> <weather_boosted=no> <invites_limit=5> <only_hosting=no> <min_level=1> <rehost=no>`

### Screenshots

> In the "raid-channel" setup for the community, Trainers can simply upload a screenshot of the Raid Boss to create a raid, and Nexus will walk through the steps necessary to start the raid.
>
> Example: <img src="_static/img/charizard-mega-x.png">

### Raid Boss Name

> In the "raid-channel" setup for the community, Trainers can simply use a Raid Boss name to create a raid, and Nexus will walk through the steps necessary to start the raid.
>
> Example: `charizard-mega-x`

### Raid Lobby Commands

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``!add``, "Use this to add someone to a raid, even if that person is not in the discord server."
   ``!bye``, "Use this to leave a raid. If you are the Host the raid will end."
   ``!close <verbose=True>``, "Use this in a raid to close it, no one else can join the raid."
   ``!end``, "Use this to end a raid."
   ``![go|start]``, "Use this to start your raid. Your raid will be closed, and all members will be pinged to let them know you've entered the lobby. You'll also be given a search string of trainers you need to invite."
   ``![go-live|nexus]``, "Use this to get your raid live in other servers where Nexus is in."
   ``!invites``, "This will give you a search string of the trainers you need to invite to a raid. ``!go`` will give you this list as well."
   ``![invites-limit|limit] <amount=5>``, "Use this in a raid to limit the amount of players you are inviting. You can reset the limit by running the command with no argument."
   ``!kick <@user|trainer>``, "Use this to kick someone from a raid."
   ``!kick-all``, "Use this to kick everyone from a raid."
   ``!members``, "Use this to get a list of the members in a raid that has more information about them."
   ``!mention <message>``, "Use this to mention the trainers on your raid."
   ``!open <verbose=True>``, "Use this in a raid to open it."
   ``!rehost``, "Use this to rehost your raid. It will be posted again and won't let people that were in your previous raid join again."
   ``!report <@user>``, "Use this to report behaviour of users on a raid. This will deduct 1 point from the user."

```

## Other Commands

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``![raid-bosses|current-rotation|active-rotation|active-bosses]``, "Use this to get the list of the active bosses."
   ``!raw-raid-bosses``, "Use this to get the raw list of the active bosses."

```
