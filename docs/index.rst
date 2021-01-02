Nexus Quick Start
===================================

Inviting Nexus 
##############

    `Invite Nexus to your community. <https://discord.com/oauth2/authorize?client_id=761036478783422484&permissions=1342696528&scope=bot>`__

    Once Nexus is added to your server, it will immediately create a new channel called ``#nexus-updates``. This channel is used for update notifications and the ``nexus-moderator`` role for people who want to run administration commands.

Configuring Nexus
#################

Raiding
*******

    You need to setup your raid channel with ``!server raid-channel <#channel>``. The raid channel is a special channel in which all raids will be.

Cross-server raids
******************

    You need to setup the channel in which you'll receive raids from other servers with ``!server online-channel <#channel>``. You can send your raid to other servers by running ``!go-live`` inside a raid.

Setup Your Mods
***************

    Once Nexus is configured, add all your mods and admins to the ``nexus-moderators`` role.

Setup Profiles
**************

    Before a user can raid, a profile needs to be setup by running ``!set profile`` with entries that matches their Pokémon Go profile.


.. toctree::
   :maxdepth: 2
   :hidden:

   trainer
   raid
   notification
   admin