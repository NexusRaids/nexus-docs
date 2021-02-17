# Hosting Raids

### Raid Command

> The `!raid` command in Nexus is the primary method for Host to create raids and can be used in any channel. It can be used simply as `!r` or as a full meal deal. All command `<inputs>` are optional but must be used in order otherwise Nexus will give an error. 

```eval_rst

.. csv-table::
   :header: "Command", "Options / Flags"
   :widths: 5, 20

   ``![raid|r]``, "``<1> <2> <flags>``"

```

#### Raid Command Inputs/Flags

```eval_rst

.. csv-table::
   :header: "#", "Input", "Description"
   :widths: 2, 5, 18

   ``<1>``, ``<pokemon>``, "Use this to set the Raid Boss."
   ``<2>``, ``<time_left=45>``, "Use this to set the time left in raid (1-45)."

.. csv-table::
   :header: "Flag", "Possible Values", "Description"
   :widths: 2, 5, 18

   ``weather-boosted``, ``true/false``, "Use this to indicate the raid is weather boosted"
   ``invites-limit``, ``0-10``, "Use this to set the invite limit"
   ``only-hosting``, ``true/false``, "Use this to set only hosting"
   ``min_level``, ``1-50``, "Use this to set minimum Trainer level."
   ``train``, ``1+``, "Use this to set how many times the raid will advance. See `Raid Train`_."
   ``rehost``, ``true/false``, "Use this to indicate the raid is a rehost."
   
.. Note:: You can input the name of the flag followed by its value (flag:value), you can either separate flags with a space or with quotes ("flag: value" flag:value), and for flags that are either true or false, by just mentioning the flag the true value will be assumed ("weather-boosted" instead of "weather-boosted:true").

   All flags have its corresponding command, and aliases can be used as well. You'll also skip the raid setup if you input at least one flag.

   You can input all the flags you want, but you can also just input the values in the following order (you don't need to input all of them): [weather-boosted] [invites-limit] [only-hosting] [minimum-level] [train] [rehost]

```

### Screenshots

> In the "raid-channel" setup for the community, Trainers can simply upload a screenshot of the Raid Boss to create a raid, and Nexus will walk through the steps necessary to start the raid.

```eval_rst

.. Note:: Nexus has a 20 screenshot limit per month among all servers. Screenshots that are not able to be recognized do not count towards this limit. You will always be able to initiate a raid via the ``!raid`` command, even if you exceed the screenshot limit. Nexus will mention you in the "setup channel" if you run out of screenshots and react with a 🛑. If you would like to increase that limit please see :doc:`Donations<../donation>` to learn more.

```

> <img src="../_static/img/charizard-mega-x.png">

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
   ``!backout``, "Use this to notify trainers to back out of the lobby"
   ``!boss <pokemon>``, "Use this in a raid to change the raid boss you are hosting."
   ``!bye``, "Use this to leave a raid. If you are the Host the raid will end."
   ``!close <verbose=True>``, "Use this in a raid to close it, no one else can join the raid."
   ``!end``, "Use this to end a raid."
   ``![go|start]``, "Use this to start your raid. Your raid will be closed, and all members will be pinged to let them know you've entered the lobby. You'll also be given a search string of trainers you need to invite."
   ``![go-live|nexus]``, "Use this to get your raid live in other servers where Nexus is in."
   ``!invites``, "This will give you a search string of the trainers you need to invite to a raid."
   ``![invites-limit|limit] <amount=5>``, "Use this in a raid to limit the amount of players you are inviting. You can reset the limit by running the command with no argument."
   ``!kick <@user|trainer>``, "Use this to kick someone from a raid."
   ``!kick-all``, "Use this to kick everyone from a raid."
   ``!member <@user|trainer>``, "Use this in a raid to get information from the user you input."
   ``!members``, "Use this to get a list of the members in a raid that has more information about them."
   ``!mention <message>``, "Use this to mention the trainers on your raid."
   ``!min-level <level>``, "Use this in a raid to change the minimum level required to enter the raid."
   ``!only-hosting <yes/no>``, "Use this in a raid to change if you are only hosting the raid and not joining, or if you are joining with the invitees."
   ``!open <verbose=True>``, "Use this in a raid to open it."
   ``!rehost``, "Use this to rehost your raid. It will be posted again and won't let people that were in your previous raid join again."
   ``!report <@user>``, "Use this to report behaviour of users on a raid. This will deduct 1 point from the user. :doc:`Point System<points>`"
   ``!reset-ready``, "Use this in a raid to reset the ready status from everyone."
   ``!time-left <minutes>``, "Use this in a raid to see how much time is left on the raid. If you are the host, you can give this command the amount of minutes that are left on your raid to update it."
   ``!weather-boosted <yes/no>``, "Use this in a raid to change if the raid is weather boosted or not."

```

### Raid Train

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``!advance``, "Use this in a raid train to advance to the next raid. This will decrease the amount of raids by 1."
   ``!train <amount>``, "Use this in a raid to update the amount of bosses you are raiding. Normal raids are trains of one raid."

```