# Admin Guide

> The following commands can only be preformed by users with the `nexus-moderators` role.

## Command Reference

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``!create <setting>``, "Use this to access create options. See `Create Settings`_."
   ``!delete <setting>``, "Use this to access delete options. See `Delete Settings`_."
   ``!poke-rr <setting>``, "Use this to access Pokémon reaction roles. See `Poke RR Settings`_."
   ``!punish <@user>``, "Use this to deduct 10 points from a user."
   ``![raid-bosses|current-rotation|active-rotation|active-bosses]``, "Use this to get the list of the active bosses."
   ``!raw-raid-bosses``, "Use this to get the raw list of the active bosses."
   ``!reset-points <@user>``, "Use this to reset the amount of points from a user."
   ``!rr <setting>``, "Use this to access reaction roles. See `RR Settings`_."
   ``!server <setting>``, "Use this to access server settings. See `Server Settings`_."

```

### Create Settings

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``!create emoji <pokemon> <verbose=True>``, "This will create an emoji from the pokémon you input. It has a cooldown of 60 seconds."
   ``!create role <arg> <verbose=True>``, "Use this to create a role."
   ``!create team-roles``, "Use this to create the mystic, valor and instinct roles."

```

### Delete Settings

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``!delete all-poke-roles``, "Use this to delete all the poke roles in your server."
   ``!delete emoji <pokemon> <verbose=True>``, "This will delete an emoji from the pokémon you input. It has a cooldown of 60 seconds."
   ``!delete not-global-poke-roles``, "Use this to delete all the poke roles from pokémon that are currently not active in raids."
   ``!delete poke-roles <pokemon...>``, "Use this to delete the roles of the pokémon you input, as well as the weather boosted roles."
   ``!delete role <arg> <verbose=True>``, "Use this to delete a role."

```

### Poke RR Settings

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``!poke-rr create <channel> <pokemon...>``, "Use this to create a reaction role of the pokémon you input. This will create both a normal reaction role and a weather boosted reaction role, along with all roles."
   ``!poke-rr global <channel> <tier=all>``, "Use this to create a reaction role of the pokémon currently in raids. Tiers: ``<mega|5|3|1>``"
   ``!poke-rr preview <pokemon...>``, "Use this to preview the reaction role for the pokémon you input."

```

### RR Settings

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``!rr create <message_id> <channel> <emoji> <role>``, "Generic reaction role implementation."
   ``!rr delete <message_id> <channel_id>``, "Use this to delete a reaction role from your server. You can also manually delete the message."
   ``!rr view``, "Use this to view all your reaction roles. There's a limit fo 50 per server."

```

### Server Settings

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``!server change-prefix <prefix>``, "Use this to change the prefix on your server."
   ``!server online-channel <channel>``, "Use this to set the channel in which you'll receive raids from other servers."
   ``!server raid-channel <channel>``, "Use this to set the channel in which raids will be posted. All other messages will be removed from this channel."
   ``!server setup-channel <channel>``, "Use this to set the channel in which Nexus will mention players when they try to create or join raids and they don't have permission to do so."
   ``!server toggle <setting>``, "Use this to access toggle configuration. See `Server Toggle Settings`_."
   
```

#### Server Toggle Settings

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``!server toggle public-raids``, "Use this to toggle off/on public raids in your server. Anyone can interact with the raids if turned on."
   ``!server toggle unfriend``, "Use this to toggle off/on the unfriend the host message when a raid ends. This doesn't apply to raids from other servers."
   
```
