# Raids

## add      

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!add``, "Use this to add someone to a raid, even if that person is not in the discord server."

```
       
## advance  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!advance``, "Use this in a raid train to advance to the next raid. This will decrease the amount of raids by 1."

```
       
## backout 

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!backout``, "Use this to notify trainers to back out of the lobby"

```
        
## boss   

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![boss|b] <pokemon>``, "Use this in a raid to change the raid boss you are hosting."

```
         
## bye   

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![bye|leave]``, "Use this to leave a raid. If you are the Host the raid will end."

```
          
## close  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!close``, "Use this in a raid to close it, no one else can join the raid."

```
         
## counters   

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!counters <boss>``, "Use this to get the top 6 counters against a raid boss. If you use this inside a raid, you don't need to include the pokémon in the command."

```
     
## end  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!end``, "Use this to end a raid."

```
           
## go       

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![go|start]``, "Use this to start your raid. Your raid will be closed, and all members will be pinged to let them know you've entered the lobby. You'll also be given a search string of trainers you need to invite."

```
       
## go-live    

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![go-live|nexus]``, "Use this to get your raid live in other servers where Nexus is in."

```
     
## host     

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!host``, "Use this in a raid to get information from the host."

```
       
## invites  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!invites``, "This will give you a search string of the trainers you need to invite to a raid."

```
       
## invites-limit  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![invites-limit|limit|il] <amount=5>``, "Use this in a raid to limit the amount of players you are inviting. You can reset the limit by running the command with no argument."

```
 
## kick      

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!kick <trainer>``, "Use this to kick someone from a raid."

```
      
## kick-all   

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!kick-all``, "Use this to kick everyone from a raid."

```
     
## member  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!member <trainer>``, "Use this in a raid to get information from the user you input."

```
        
## members    

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![members|m]``, "Use this to get a list of the members in a raid that has more information about them."

```
     
## mention    

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!mention <message>``, "Use this to mention the trainers on your raid."

```
     
## min-level    

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![min-level|minimum-level|ml] <level>``, "Use this in a raid to change the minimum level required to enter the raid."

```
   
## only-hosting   

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![only-hosting|oh] <yes/no>``, "Use this in a raid to change if you are only hosting the raid and not joining, or if you are joining with the invitees."

```
 
## open  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!open``, "Use this in a raid to open it."

```
          
## raid    

```eval_rst

.. csv-table::
   :header: "Command", "Options/Flags"
   :widths: 20, 80

   ``![raid|r]``, "``<1> <2> <flags>``"

``` 

**Raid Command Options/Flags:**

```eval_rst

.. csv-table::
   :header: "#", "Input", "Description"
   :widths: 5, 5, 90

   ``<1>``, ``<pokemon>``, "Use this to set the Raid Boss."
   ``<2>``, ``<time_left=45>``, "Use this to set the time left in raid (1-45)."

.. csv-table::
   :header: "Flag", "Possible Values", "Description"
   :widths: 5, 5, 90

   ``weather-boosted``, ``true/false``, "Use this to indicate the raid is weather boosted"
   ``invites-limit``, ``0-10``, "Use this to set the invite limit"
   ``only-hosting``, ``true/false``, "Use this to set only hosting"
   ``min_level``, ``1-50``, "Use this to set minimum Trainer level."
   ``train``, ``1+``, "Use this to set how many times the raid will advance."
   ``rehost``, ``true/false``, "Use this to indicate the raid is a rehost."
   
.. Note:: You can input the name of the flag followed by its value (flag:value), you can either separate flags with a space or with quotes ("flag: value" flag:value), and for flags that are either true or false, by just mentioning the flag the true value will be assumed ("weather-boosted" instead of "weather-boosted:true").

   All flags have its corresponding command, and aliases can be used as well. You'll also skip the raid setup if you input at least one flag.

   You can input all the flags you want, but you can also just input the values in the following order (you don't need to input all of them): [weather-boosted] [invites-limit] [only-hosting] [minimum-level] [train] [rehost]

```
        
## raid-bosses   

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![raid-bosses|current-rotation|active-rotation|active-bosses] <option=embed>``, "Use this to get the list of the active bosses. Options: ``<embed|raw>``"

```
  
## ready  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!ready``, "Use this to mark yourself as ready inside a raid."

```
         
## rehost  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!rehost``, "Use this to rehost your raid. It will be posted again and won't let people that were in your previous raid join again."

```
        
## report  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!report <user>``, "Use this to report behaviour of users on a raid. This will deduct 1 point from the user. :doc:`Point System<../point-system>`"

```
        
## reset-ready  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!reset-ready``, "Use this in a raid to reset the ready status from everyone."

```

## thanks 

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!thanks``, "Use this in a raid to give an extra point to the host once the raid has started."

```
   
## time-left   

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![time-left|time|tl] <minutes>``, "Use this in a raid to see how much time is left on the raid. If you are the host, you can give this command the amount of minutes that are left on your raid to update it."

```
    
## train  

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!train <amount>``, "Use this in a raid to update the amount of bosses you are raiding. Normal raids are trains of one raid."

```
         
## unready 

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``!unready``, "Use this to mark yourself as unready inside a raid."

```
        
## weather-boosted 

```eval_rst

.. csv-table::
   :header: "Command", "Description"
   :widths: 20, 80

   ``![weather-boosted|wb] <yes/no>``, "Use this in a raid to change if the raid is weather boosted or not."

```
