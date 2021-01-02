# Raid Guide

## Joining Raids

> In the "raid-channel" setup for the community, Trainers can join raids by clicking the "raid pass", and Nexus will prompt the Trainer to join the raid lobby.
>
> <img src="_static/img/join.png?update">



## Hosting Raids

### Raid Command

> The `!raid` command in Nexus is the primary method for Host to create raids and can be used in any channel. It can be used simply as `!r` or as a full meal deal. All command `<inputs>` are optional but must be used in order otherwise Nexus will give an error. 

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``![raid|r] <1> <2> <3> <4> <5> <6> <7>``, "Use this to create a raid. No input is required, you can just run ``!raid``."

```

#### Raid Command Inputs

```eval_rst
.. csv-table::
   :header: "#", "Input", "Description"
   :widths: 2, 5, 18

   ``<1>``, ``<pokemon>``, "Use this to set the Raid Boss."
   ``<2>``, ``<time_left=45>``, "Use this to set the time left in raid (1-45)."
   ``<3>``, ``<weather_boosted=no>``, "Use this to indicate the raid is weather boosted (yes/no)."
   ``<4>``, ``<invites_limit=5>``, "Use this to set the invite limit (1-20)."
   ``<5>``, ``<only_hosting=no>``, "Use this to set only hosting (yes/no)."
   ``<6>``, ``<min_level=1>``, "Use this to set minimum Trainer level (1-50)."
   ``<7>``, ``<rehost=no>``, "Use this to indicate the raid is a rehost (yes/no)."

```

### Screenshots

> In the "raid-channel" setup for the community, Trainers can simply upload a screenshot of the Raid Boss to create a raid, and Nexus will walk through the steps necessary to start the raid.
> Please note Nexus has a 20 screenshot limit per month among all servers. If you would like to increase that limit please see <a href="/donation">Donations</a> to learn more.
>
> <img src="_static/img/charizard-mega-x.png">

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
   ``!report <@user>``, "Use this to report behaviour of users on a raid. This will deduct 1 point from the user. See `Point System`_"

```

## Other Commands

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``![raid-bosses|current-rotation|active-rotation|active-bosses]``, "Use this to get the list of the active bosses."
   ``!raw-raid-bosses``, "Use this to get the raw list of the active bosses."

```

```eval_rst
.. _point-system:

```

## Point System

> Nexus uses a point system to reward active Trainers on a per server basis. Use `!leaderboard` or `!profile <@user>` to view point totals.

```eval_rst
.. csv-table::
   :header: "Point", "Description"
   :widths: 2, 23

   "+1", "Join a raid."
   "-1", "Leave raid within the first 60 seconds."
   "+1", "Host a raid."
   "-2", "End raid within the first 60 seconds."
   "+1", "Host use ``!go`` with invites."
   "+1", "Host use ``!go-live`` after 60 seconds."
   "+1", "Thank a Trainer inside the raid with ``@user <thank_you_message>`` (once per raid)."
   "-1", "Use ``!report <@user>`` to notify ``nexus-moderators`` of a issue with a Trainer (once per raid)."
   
```

> The following command can only be preformed by users with the `nexus-moderators` role.

```eval_rst
.. csv-table::
   :header: "Point", "Description"
   :widths: 2, 23

   "-10", "Use ``!punish <@user>`` deduct points from Trainers."
   
```
