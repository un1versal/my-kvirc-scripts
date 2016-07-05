### About

#####**bot.kvs**

An alias script named *DoiT for Angelina*, Angelina is a community member provided [Cbot (written in C#)](https://github.com/AndrioCelos/CBot) to aid with support in [#KVIrc]{ircs://chat.eu.freenode.net:7070/#KVIrc).  
It's a ```/bot <cmd>``` alias, to **add**, **remove** and **change** **data** or **triggers** into the bots database. this is really a memory-aid for myself as the commands are simple enough but in time one forgets,

For script usage, type ```/bot``` and press ```[Enter]``` to get a list of supported switches/syntax with explanations on what each action does.

#####**sys.kvs**

An alias script named *SysInfo*, and as the name may indicate, it provides a simple way to output system information about various hardware components in your machine and your OS.  
**SysInfo** script requires [inxi](https://github.com/smxi/inxi) and [lm-sensors](https://github.com/groeck/lm-sensors/issues/3). At this time *SysInfo* is only available for UNIX-like / Linux systems.

For script usage, type ```/sys``` and press ```[Enter]``` to get a list of supported switches with explanations on what each action does.

>###### Requires inxi 2.2 or newer  
>###### sen (sensors) option requires lm-sensors installed and configured (not required otherwise)

#####**search.kvs**

This alias script is named *SearchiT*, it facilitates searches for terms or anything else at all via Duck Duck Go SSL search engine. It opens a browser window with your results.  
This was a request by another KVIrc user on IRC at [#KVIrc]{ircs://chat.eu.freenode.net:7070/#KVIrc). 

For script usage, type ```/search``` and press ```[Enter]``` to get a list of supported switches/syntax with explanations on what each action does.

### Installation

:mans_shoe: [Click for inxi installation details](https://code.google.com/archive/p/inxi/wikis/Installation.wiki)  

:mans_shoe: lm-sensors installation should be available from your favorite distro's package manager. Else have a look at [This search](https://duckduckgo.com/?t=disconnect&x=%2Fhtml&q=install+lm-sensors&ia=web)  

:mans_shoe: Download the respective scripts to your local drive and place e.g. on your Desktop.

>##### Via UI

:mans_shoe: In KVIrc press ```Ctrl+Shift+X```  

:mans_shoe: Browse to your Desktop and select script  

:mans_shoe: Click Open

>##### Via command-line

:mans_shoe: In KVIrc input line type ```/parse path/to/the.script.kvs```  

:mans_shoe: Press Enter

### Uninstallation

>##### Via command-line

:mans_shoe: In KVIrc input line type ```/scriptname uninstall```  

:mans_shoe: Press Enter

### License

[![my kvirc scripts GPLv2](https://img.shields.io/badge/my_kvirc_scripts-GPLv2-blue.svg)](https://github.com/un1versal/my-kvirc-scipts/blob/master/LICENSE)
