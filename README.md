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
* ```$calm``` - calm
* ```$niceass``` - See a nice ass!
* ```$shinyass``` - See a shiny ass!
* ```$bitch``` - Tell a bitch you love them!
* ```$rage``` - Rage rage fucking rage!
* ```$eatadick``` - Tell someone to eat a dick!
* ```$fuckyou``` - Say fuck you!
* ```$excite``` - Be very excite!\
* ```$conversions``` - A list of useful conversions!

## Utility Commands
* ```$ping``` - Get the bot's ping! (has a slash variation)
* ```$documentation`````` or ```$docs``` - Get the link to the bot's documentation!
* ```$oc``` or ```$OC``` - Request for the Senate to complete your OC! (has a slash variation)
* ```$vault <amount>``` - Request money from the faction vault, please use commas! (has a slash variation)
   
   Example. ```$vault 100,000```
* ```$xan [amount]``` or ```$xanax [amount]``` - Request xanax for chains! [amount defaults to 1 if left empty] (has a slash variation)
   
   Example. ```$xan 2```
* ```$armory <item/items requested>``` - Request an item/items from the armory!

   Example. ```$armory combat gear```

## Slash Commands (Utility)
* ```/ping``` - Get the bot's ping! 
* ```/documentation``` - Get the link for the bot's documentation!
* ```/feedback bot <feedback_type: Dropdown menu of applicabe feedback types> <message: whatever you feedback message is> [anonymous: whether you want it anonymous or not]``` - Send feeback about the bot that will remain private!
* ```/ticket <issue: describe the bug or issue> <message: Do you want messaged to discuss further?>``` - Submit a ticket about the bot!

## Slash Commands (Request)
###All of the Slash commands are now part of the /request command to further streamline requests and to use less of the slash command limits!
* ```/request oc [message: add an optional message]``` - Request for the Senate to complete your OC! 
* ```/request vault <amount: amount of money, number only> [message: add an optional message]``` - Request money from the faction vault! 
* ```/request xanax <amount: amount of xanax> [message: add an optional message]``` - Request xanax for chain!
* ```/request armory <items: any item/items you wish to request from the armory> [message: add an optional message]``` - Request an item/items from the armory!
* ```/request cancel [message: add an optional message]``` - Request for your most recent request to be cancelled!

## Slash Commands (Announce)
### All of these slash commands are part of the /announce command. For a guide to embeds see the bottom of this documentation!
* ```/announce museum``` - Don't need to list the options for this, it's for me only but still wanted to list it!
* ```/announce basic_embed <title: The embed title> <main_text: the main text block of the embed> [embed_color: optional color for the embed block, needs to be hexadecimal (see guide] [footer_text: optional footer text for the embed]``` - Send a basic embed message!
* ```/announce advanced_embed <embed_title: The embed title> [main_text: the optional main text block of the embed] [embed_color: optional color for the embed block, needs to be hexadecimal (see guide] [field#_name: Enter the name for this # field] [field#_value: Enter the text for this # field, keep in mind if you use a field#_name you need a field#_value] x5 [footer_text: optional footer text for the embed]``` - Send an advanced embed message!

## Slash Commands (Links)
* ```/invite``` - Get the discord invite!
* ```/factionlink``` - Get the faction link!
* ```/statbook``` - Get the statbook link!
* ```/tornstats``` - Get the tornstats links!
* ```/factioncompanies``` - Gives links to all the faction companies!
* ```/beyondthetabletops``` - Get info about the tabletop server!
* ```/wiki <page: to select a page of the wiki>``` - Get the torn wiki!

## Moderation (Senate) Commands
### These commands will only function when used by Senate (or other applicable roles) and will merely throw an error at others. 
* ```/division <member: Dropdown of members to assign> <division: dropdown of division names>``` - Assign a member to a division!
* ```/request deny <member: member who placed the request> <request_type: type of request> <reason: reason for denying request> [channel: channel to send deny to if the member has DMs blocked]``` = Deny requests for any necessary reasons!
* ```/log pastmember <name: torn name> <id: torn id> <type: Kicked or Left> <reason: Reason/Notes>``` - To log past members!
* ```/announce senate_embed <embed_title: The embed title> <channel: select the channel to send to> [mention: Select a role to mention!] [main_text: the optional main text block of the embed] [embed_color: optional color for the embed block, needs to be hexadecimal (see guide] [field#_name: Enter the name for this # field] [field#_value: Enter the text for this # field, keep in mind if you use a field#_name you need a field#_value] x5 [footer_text: optional footer text for the embed]``` - Send an advanced embed message to any channel! (Senate only)
* ```/announce dm <member: member to DM> <message: message to send>``` - Send a DM to a user with the bot! (Senate only)


# A Quick and Dirty Guide to Embeds
## The Key Parts of an Embed - See image at the bottom for reference where each thing (except color) is labeled with (). 
* Title - This appears at the top of the embed in large letters
* Description/Main Text - Makes up the core chunk of text of the embed. 
* Color - The color is represented on the left hand side of the embed and needs to be in hexadecimal form, I like to use the [google color picker](https://www.google.com/search?q=color+picker&oq=color+picker&aqs=chrome.0.69i59j0i20i263i512j0i433i512j0i131i433i512j0i512j0i433i512l3j0i131i433i512.2226j0j9&sourceid=chrome&ie=UTF-8). You want to use thr HEX option, without the #. So in the image below it would be ```fcba03```.
![image](https://user-images.githubusercontent.com/70727679/196340449-77fc5d4b-e22f-4656-bd9b-840c82c829c8.png)
* Fields - Fields have a name and a value. The advanced embed command allows for up to 5 fields total, keep in mind if you us a field name, that name needs to have a value as well. And you can't have a value without a name. So for example if you write in something for field1_name you also need to write something for field1_value. 
* Footer - The tiny text at the bottom of the embed message
![image](https://user-images.githubusercontent.com/70727679/196341467-434dff5f-36b5-4b9c-ae12-4b1b3b26651f.png)

