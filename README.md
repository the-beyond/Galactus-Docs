# Galactus Documentation
This is intended as a publicly available documentation for The Beyond's Galactus Discord Bot. 
The bot has been developed in Python using the Nextcord module which is a fork of the original discord.py module. 

This documentation has been divided into three section for now and is very likely to be changed in the future to make it look nicer!

* The Prefixes for Galactus bot are ```$```, ```g!```, ```G!```, ```?``` and ```? ```. For my examples I will always use \$, but it is interchangable with the others if you wish, and there is a large variety for people to decide what they like. 
PLEASE NOTE - Slash commands can only use the ```/``` prefix (Be sure to make sure you're using Galactus and not Testing Galactus. 
   I will likely be using primarily slash commands only beyond the core commands. 

### Key Notes
* Anything listed in \<> is a required argument for the commands and the command will not work without it, __DO NOT INCLUDE THE \<> IN THE COMMAND__.
* Anything listed in \[] is an optional argument for the commands and allows the command to use what you add, __DO NOT INCLUDE THE \[] IN THE COMMAND__.
* For slash commands I have included what each item in <> or [] represents by writing it in as ```<title: purpose>``` with the purpose being everything after the colon. 

## Fun Commands
* ```$blamejames``` - Blame James, simple as that!
* ```$tanuki``` - Sends the gif of our almighty overlord the tanuki!
* ```$broom``` - Sends a gif of a broom to turn James on!
* ```$rigged``` - Calls out Feather/Dom for rigging things!
* ```$ghosttank``` - Gather to hear the story of Ghost Tank to the tune of the Ghostbusters Theme Song!
* ```$hellothere``` - Obi-Wan has come to tell you Hello There!
* ```$tyan``` - Tell someone that they are there now!
* ```$dice <NdN> or $roll <NdN>``` - Roll the dice!
   
   Example. ```$dice 1d20```
* ```$askgalactus <Yes or No Question>``` - Ask Almighty Galactus a question! (has a slash variation)
   
   Example. ```$askgalactus Does James like brooms?```

## Utility Commands
* ```$ping``` - Get the bot's ping! (has a slash variation)
* ```$documentation`````` or ```$docs``` - Get the link to the bot's documentation!
* ```$oc``` or ```$OC``` - Request for the Senate to complete your OC! (has a slash variation)
* ```$vault <amount>``` - Request money from the faction vault, please use commas! (has a slash variation)
   
   Example. ```$vault 100,000```
* ```$xan [amount]``` or ```$xanax [amount]``` - Request xanax for chains! [amount defaults to 1 if left empty] (has a slash variation)
   
   Example. ```$xan 2```

## Slash Commands
* ```/ping``` - Get the bot's ping! 
* ```/oc``` - Request for the Senate to complete your OC! 
* ```/vault <amount: amount of money>``` - Request money from the faction vault, please use commas Ex. 1,000,000!
* ```/xanax <amount: amount of xanax>``` - Request xanax for chain!
* ```/documentation``` - Get the link for the bot's documentation!
* ```/feedback <feedback_type: Dropdown menu of applicabe feedback types> <message: whatever you feedback message is> [anonymous: whether you want it anonymous or not]``` - Send feeback about the bot that will remain private!
* ```/ticket <issue: describe the bug or issue> <message: Do you want messaged to discuss further?>``` - Submit a ticket about the bot!

## Moderation (Senate) Commands
### These commands will only function when used by Senate (or other applicable roles) and will merely throw an error at others. 
* ```/division <member: Dropdown of members to assign> <division: dropdown of division names>``` - Assign a member to a division!
