# Administration

> The following commands can only be preformed by users with the `nexus-moderators` role.

## award

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!award badge <user> <badge_name>``, "Use this to award a badge to a user."
   ``!award upgrade``, "Use this to award an upgrade to the server in which you are running this command."

```

## create

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!create badge <emoji> <name>``, "Use this to create a custom badge on your server."
   ``!create emoji <pokemon>``, "This will create an emoji from the Pokémon you input."
   ``!create global-emoji <pokemon>``, "This will create an emoji from the Pokémon you input."
   ``!create profile-roles``, "Use this to create all the profile roles. This includes ign, tc, level, country and profile."
   ``!create role <arg>``, "Use this to create a role."
   ``!create team-roles``, "Use this to create the mystic, valor and instinct roles."

```

## delete

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!delete all-poke-roles``, "Use this to delete all the poke roles in your server."
   ``!delete badge <name>``, "Use this to delete a custom badge on your server."
   ``!delete emoji <pokemon>``, "This will delete an emoji from the Pokémon you input. It has a cooldown of 60 seconds."
   ``!delete not-global-poke-roles``, "Use this to delete all the poke roles from Pokémon that are currently not active in raids."
   ``!delete poke-roles <pokemon...>``, "Use this to delete the roles of the Pokémon you input, as well as the weather boosted roles."
   ``!delete role <arg>``, "Use this to delete a role."

```

## global-ban

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!global-ban <user>``, "Use this to completely ban someone from creating raids and joining raids in your server. This works on cross-server raids as well."

```

## global-unban

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!global-unban <user>``, "Use this to unban that has been globally banned before."

```

## leaderboard

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!leaderboard view <recent=True>``, "Use this to see the top 10 trainers who have joined and hosted raids, as well as the ones with more points. You can specify if you want to retrieve the most recent leaderboard or the all-time leaderboard."
   ``!leaderboard automatic <channel>``, "Use this to send an automatic leaderboard that will update every 24 hours."
   ``!leaderboard ban <user>``, "Use this to remove a user from appearing on the leaderboard."
   ``!leaderboard extended <recent=True>``, "Use this to view the complete leaderboard."
   ``!leaderboard unban <user>``, "Use this to make a user appear on the leaderboard again."
   ``!leaderboard reset``, "Use this to reset the leaderboard."

```

## pokebattler-raid-network

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![pokebattler-raid-network|pokebattler|prn] feed``, "Use this to create a channel with the Pokebattler Raid Network feed. Raids from other servers will appear in here and you can join them through the app or by joining the remote server."
   ``![pokebattler-raid-network|pokebattler|prn] permanent-invite <permanent_invite_url>``, "Use this to set a permanent invite for this server on the Pokebattler Raid Network."
   ``![pokebattler-raid-network|pokebattler|prn] toggle``, "Use this to turn on/off the pokebattler raid network in your discord server"

```

## poke-rr

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!poke-rr create <channel> <pokemon...>``, "Use this to create a reaction role of the pokémon you input. This will also create all the necessary roles."
   ``!poke-rr global <channel> <tier=all>``, "Use this to create a reaction role of the pokémon currently in raids. Tiers: ``<all|mega|5|3|1>``"
   ``!poke-rr mentionable``, "Use this to toggle on/off roles from pokémon reaction roles being mentionable."
   ``!poke-rr permaboosted``, "Use this to toggle on/off permaboosted showing on pokémon reaction roles."
   ``!poke-rr tier-roles``, "Use this to toggle on/off tier roles showing on pokémon reaction roles."
   ``!poke-rr weather-boosted``, "Use this to toggle on/off weather boosted pokémon reaction roles."
   
```

## punish

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!punish <user>``, "Use this to deduct 10 points from a user."

```

## reset-points

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!reset-points <user>``, "Use this to reset the amount of points from a user."

```

## revoke

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!revoke badge <user> <badge_name>``, "Use this to revoke a badge from a user."

```

## reaction-role

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![rr|reaction-role] create <message_id> <channel> <emoji> <role>``, "Generic reaction role implementation."
   ``![rr|reaction-role] delete <message_id> <channel_id>``, "Use this to delete a reaction role from your server. You can also manually delete the message."
   ``![rr|reaction-role] view``, "Use this to view all your reaction roles. There's a limit fo 50 per server."

```

## server

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!server change-moderator-role <role>``, "Use this to change the moderator role in your server."
   ``!server change-nicknames``, "Use this to change the nicknames of every member in your server to their corresponding in-game name (only if set)."
   ``!server change-prefix <prefix>``, "Use this to change the prefix on your server."
   ``!server info``, "Use this to check information about your server."
   ``!server log-channel <channel>``, "Use this to set the channel in which you'll receive logs from the raids on your server."
   ``!server main-raid-channel <channel>``, "Use this to set the channel in which all raids will be visible."
   ``!server online-channel <channel> <tier=all>``, "Use this to set the channel in which you'll receive raids from other servers. Tiers: ``<all|mega|5|3|1>``"
   ``!server raid-channel <channel>``, "Use this to set the channel in which raids will be posted. All other messages will be removed from this channel."
   ``!server setup-channel <channel>``, "Use this to set the channel in which Nexus will mention players when they try to create or join raids and they don't have permission to do so."
   ``!server toggle force-nickname``, "Use this to toggle on/off forcing nicknames of members of your server to be their respective in-game trainer names."
   ``!server toggle join-multiple-raids``, "Use this to toggle on/off allowing trainers to join more than one raid at the same time in your server."
   ``!server toggle public-raids``, "Use this to toggle off/on public raids in your server. Anyone can interact with the raids if turned on."
   ``!server toggle unfriend``, "Use this to toggle off/on the unfriend the host message when a raid ends. This doesn't apply to raids from other servers."
   
```

## update-all-members-roles

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!update-all-members-roles``, "Use this to update all roles of members on your server. This action can take up to several minutes. This will update all profile roles, if they exist (ign, tc, level, country, team, profile)"

```

## view

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!view badges``, "Use this to view all badges in your server"

```
