# Global Trading System

> Global Trading System (GTS) is a trade manager that allows Trainers to search for trades with other users within the Nexus bot network. This works by checking in a radius from the location set in your Nexus profile similar to the basic trade search on a single Discord server except it returns offers with Pokémon requested.
>

## Command Reference

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``![global-trading-system|gts] <settings>``, "Use this to access the global trading system. See `Settings`_."

```

### Settings

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 5, 20

   ``!global-trading-system accept <id>``, "You can run this command if you see a trade you are interested in, your discord tag will be given to the other user so you can coordinate. You can get the trade id by searching the trades nearby."
   ``!global-trading-system failure <id>``, "If you fail to complete the trade once someone is interested in it, you can run this command to make your trade available in the global trading system again. You can get the trade id by checking your trading offers."
   ``!global-trading-system offers``, "Use this to see all your current trading offers."
   ``!global-trading-system pending``, "You can run this command to see all trades that you have pending."
   ``!global-trading-system remove <id>``, "Use this to remove one of your trading offers. You can get the trade id by checking your trading offers."
   ``!global-trading-system search <pokemon...>``, "Use this to search a trade for a Pokémon within your range. If you give no Pokémon to this command, it will search all available trades."
   ``!global-trading-system submit <offer_pokemon> <pokemon_wanted>``, "Use this submit a trade on the global trading system. Your discord tag will will be visible to trainers that accept your trade so you can coordinate with each other."
   ``!global-trading-system success <id>``, "If you succeed in trading, you can run this command to mark your trade as done. You can get the trade id by checking your trading offers."

.. Note:: The Global Trading System gives users 1 active spot for trading. If users wish to have more trading spots please consider supporting Nexus. See :doc:`Donations<donation>` to learn more.
   
```