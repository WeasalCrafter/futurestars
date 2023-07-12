  ______     _                     _____ _                 
 |  ____|   | |                   / ____| |                
 | |__ _   _| |_ _   _ _ __ ___  | (___ | |_ __ _ _ __ ___ 
 |  __| | | | __| | | | '__/ _ \  \___ \| __/ _` | '__/ __|
 | |  | |_| | |_| |_| | | |  __/  ____) | || (_| | |  \__ \
 |_|   \__,_|\__|\__,_|_|  \___| |_____/ \__\__,_|_|  |___/

+------------------IMPORTANT----------------------------------------------------+
|                                                                               |
| Read this entire file in order to completely setup your camp mincraft server. |
|                                                                               |
+-------------------------------------------------------------------------------+

-----------------------------------------------------------------------------------------------                           
This pack includes features such as:
 - An editable filter for profanities
 - Lag reduction
 - "Time Machines" to rollback any destruction
 - Preventions of camper x camper combat, explosions, and other undesirable events
-----------------------------------------------------------------------------------------------                              
Current plugins listed in this package:
 - ChatFilter
     source: https://www.spigotmc.org/resources/chatfilter-chat-signs-books-and-anvils.81652/

 - Clearlagg
     source: https://www.spigotmc.org/resources/clearlagg.68271/
     docs: https://dev.bukkit.org/projects/clearlagg/pages/config-setup

 - Coreprotect
     source: https://www.spigotmc.org/resources/coreprotect.8631/
     docs: https://docs.coreprotect.net/

 - SimpleTpa
     source: https://www.spigotmc.org/resources/simple-tpa.64270/

 - Worldedit
     source: https://dev.bukkit.org/projects/worldedit
     docs: https://worldedit.enginehub.org/en/latest/

 - Worldguard
     source: https://dev.bukkit.org/projects/worldguard
     docs: https://worldguard.enginehub.org/en/latest/
-----------------------------------------------------------------------------------------------                              
Step 1: go ahead to www.aternos.org and create a free account, this website is free due to 
constant ads being presented; however it is HIGHLY reccomended, but not neccesary, to purchase 
a dedicated server from a service like https://apexminecrafthosting.com.

+------------------IMPORTANT-----------------+
| **the guide that follows goes along with** |
|   **the free Aternos.org website**         |
+--------------------------------------------+

Step 2: You should be prompted with a screen with a button, "Create Server", click this, and 
you will be prompted with another screen confirming the creation, click "create", to continue.

Step 3: At this point you should be at the panel of your server, on the left side of your 
screen there will be multiple buttons/tabs, click into the "Software" tab. There will be
multiple options for software, select "Paper/Bukkit", then select the latest version of 
minecraft(at the time of writing this 1.20.1), then click the green "Install" button.

Step 4: On the left side of your screen there will be multiple buttons/tabs, click into 
the "Plugins" tab, this is where you will install all of your plugins/add-ons for the 
server. There is a search bar where you will search for plugins: 

 . First, search "ChatFilter" and install "ChatFilter - Chat, Signs, Books and Anvils"
 . Second, search "Clearlagg" and install "Clearlagg"
 . Third, search "Coreprotect" and install "Coreprotect"
 . Fourth, search "SimpleTpa" and install "Simple Tpa"
 . Fifth, search "WorldEdit" and install "WorldEdit for bukkit"
 . Last, search "Worldguard" and install "Worldguard"

Step 5: Go back to the main server panel and click the green "Start" button to boot your 
server. You will be prompted to "accept the minecraft EULA(end user license agreement)", 
cick yes. You should log onto the server using the provided ip address found on the server panel. 

Step 6: Once in the server, from the console, run the command "op {username here}", so for 
a username of weasalcrafter the command would be "op weasalcrafter". This command gives 
administrator privelidges to the user and allows for further configuration within the server itself.

some useful flags(rules) that can be set for the world:
/region flag __global__ tnt deny #disables tnt blasts
/region flag __global__ creeper-explosion deny #disables creeper explosions
/region flag __global__ other-explosion deny #disables any types of explosions
/region flag __global__ lighter deny #disables flint n steals
/region flag __global__ pvp deny #disables any type of player to player combat

usage: /cf blacklist add word {any word}
ex: /cf blacklist add word shit
google a list of english swear words and add common ones

/co i
/co rollback r:{radius} t:{time}

users can send teleport requests to one another by running
/tpa {username of other person}
and the request can be accepted or denied with
/tpaccept or /tpdeny
