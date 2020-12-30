# Admin's Guide

## Quick Setup

1. <a href="https://discord.com/oauth2/authorize?client_id=761036478783422484&permissions=1342696528&scope=bot" target="_blank"> :guilabel:`Invite Bot` </a>


## Inviting Nexus 

To invite Nexus to your community, please visit the <a href="https://top.gg/bot/761036478783422484" target="_blank">Top.gg</a>, and click on the invite button.

Once Nexus is added to your server, it will immediately create a new channel called `#nexus-updates`. This channel is used for update notifications and the `nexus-moderator` role for people who want to run administration commands.

## Configuring Nexus

### Raiding

You need to setup your raid channel with `!server raid-channel #channel`. The raid channel is a special channel in which all raids will be.

### Cross-server raids

You need to setup the channel in which you'll receive raids from other servers with `!server online-channel #channel`. You can send your raid to other servers by running `!go-live` inside a raid.


### Setup Your Mods

Once Nexus is configured, add all your mods and admins to the `nexus-moderators` role.



## Command 

```eval_rst
.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``!create``, "Use this to access create options."
   ``!delete``, "Use this to access delete options."
   ``!poke-rr``, "Use this to access Pokémon reaction roles."
   ``!punish``, "Use this to deduct 10 points from a user."
   ``!reset-points``, "Use this to reset the amount of points from a user."
   ``!rr``, "Use this to access reaction roles."
   ``!server``, "Use this to access server settings."
   
```

### !create

### !delete

### !poke-rr

### !punish

### !reset-points

### !rr

### !server

`!server <setting>`

```eval_rst
.. csv-table::
   :header: "Setting", "Description"
   :widths: 5, 20

   ``change-prefix``, "Use this to change the prefix on your server."
   ``online-channel``, "Use this to set the channel in which you'll receive raids from other servers."
   ``raid-channel``, "Use this to set the channel in which raids will be posted. All other messages will be removed from this channel."
   ``setup-channel``, "Use this to set the channel in which Nexus will mention players when they try to create or join raids and they don't have permission to do so."
   ``toggle``, "Use this to access toggle configuration."
```