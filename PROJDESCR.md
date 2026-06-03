The project focuses on intergrating different programms and hardware into a Minecraft Server.\
The whole project is tracked and documented on GitHub, which is new for the course.


The MC Server is hosted on a Raspberry Pi 5, in a docker enviorment.\
The MC Server is a simple "PVP Arena Map", with multiple arenas players can fight in.

The *DigiLab* board has multiple buttons which are used to control the PVP enviorment for the arena, for example;
teleporting players, healing players, etc.

The LEDs on the *DigiLab* indicates a Players Health, with a dedicated Button to heal.

The Switches on the *DigiLab*, labeled S4 and S3, act as a Toggle, which allow the other buttons to be "remapped" into other commands and uses.

Button - No Toggle  -                         Toggle S4 -             Toggle S3 -             Toggle S4 + S3
S5 -     TP Arena 1 -                         Turns Day -             Spawn 5x Zombies -      Gives 1x Notch Apple
S6 -     TP Arena 2 -                         Turns Night -           Spawn 5x Skeletons -    Makes Players Invisble
S7 -     TP Arena 3 -                         Turns Sunset -          Spawn 3x Witches -      Heal ALL Players
S8 -     TP Arena 4 -                         Weather Rain -          Spawn 5x Spiders -      Gives a random GOOGD effect
S1 -     Clears Inventory -                   Weather Rain -          Spawn 5x CaveSpiders -  Clears ALL inventory and gives 3x Stacks Snowballs
S2 -     Get Kit -                            Weather Thunderstorm -  Spawn 3x Blaze -        TP ALL Players to Arena 5 (End Island) with active Ender Dragon


Kit - Iron Sword/bow/64xArrows/Iron Helmet/Iron Chestplate/Iron Leggings/Iron Boots/64xGold Apples/Shield/


The Screen of the *DigiLab* is used to display multiple different outputs, for example;
when teleporting into a new arena, when someone new joins, when someone is killed, when someone won a fight, etc.\

Via the integration of the discord bot and chat-server, simple commands can be triggered through text-chat.
As well as logging older messages and showing the MC server-logs, as the *DigiLab* Screen only has place for two-lines of Text.
On the server, there is also a simple chat avaiable, with the function to msg into MC and a small description of the server.
There will also be a chat avaialable with ChatGPT, to ask questions and get help about PVP in Minecraft.

The Dashboard of NodeRed is also used to display simple information of the server and most of the commands avaiable on discord, are present as a dedicated button on the Dashboard, with also a chat-box to write any MC command. The Dashboard also displays recent logs of the MC Server, and vital information of the raspberry Pi (CPU usage and Temp.)
