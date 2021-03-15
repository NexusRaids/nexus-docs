# Hosting Raids

## Raid Command

> The `!raid` command in Nexus is the primary method for Host to create raids, and can only be used the "raid-channel" setup for the community. It can be used simply as `!r` or as a full meal deal. To learn more about the raid command please see <a class="reference internal" href="../commands/raids.html#raid">Raids Commands</a>.

## Screenshots

> In the "raid-channel", Trainers can simply upload a screenshot of the Raid Boss to create a raid, and Nexus will walk through the steps necessary to start the raid.

```eval_rst

.. Note:: Nexus has a 20 screenshot limit per month among all servers. Screenshots that are not able to be recognized do not count towards this limit. You will always be able to initiate a raid via the ``!raid`` command, even if you exceed the screenshot limit. Nexus will mention you in the "setup channel" if you run out of screenshots and react with a 🛑. If you would like to increase that limit please see :doc:`Donations<../donation>` to learn more.

```

> <img src="../_static/img/charizard-mega-x.png">

## Raid Boss Name

> In the "raid-channel", Trainers can simply use a Raid Boss name to create a raid, and Nexus will walk through the steps necessary to start the raid.

> Example: `charizard-mega-x`

## Raid Lobby Commands

### Essentials

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!go``, "Pings everyone and gives you a search string of trainers, closing your lobby."
   ``!end``, "Makes you leave the raid channel, and end the raid"

```

### Getting information

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!members``, "Displays information about the members of your raid."
   ``!invites``, "Gives you a search string of the users you need to invite. !go gives you this list as well."


```

### Altering your raid

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!close``, "Closes your raid so no one can come in."
   ``!open``, "Opens your raid so people can come in again, if your raid is closed."
   ``!invites-limit <number>``, "Limits the amount of trainers you can invite."
   ``!weather-boosted <yes/no>``, "Change the weather boosted status of your raid."
   ``!only-hosting <yes/no>``, "Change your status as a host, if you are joining the raid or if you are only hosting it."
   ``!minimum-level <level>``, "Change the minimum level required to enter your raid."
   ``!time-left <minutes>``, "Change the amount of time left on the raid."
   ``!boss <pokemon>``, "Updates the raid boss of your raid."

```

### Advanced

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!mention <message>``, "You can mention everyone in a raid and broadcast a message with this command."
   ``!add <trainer>``, "This command will let you add a trainer to the raid. This will work with discord users or trainers that are not from discord."
   ``!kick <trainer>``, "This command will let you kick a member from the raid."
   ``!ban <trainer>``, "This command will let you ban a member, only from this raid."
   ``!rehost``, "This command will create a rehost of this raid. No current member will be allowed to join it."
   ``!train <amount>``, "Change your raid into a raid train. You need to input the amount of raids you are planning to do."
   ``!advance``, "Advances your raid train to the next raid."
   ``!nexus``, "This command will send your raid to other servers where Nexus is in."

```