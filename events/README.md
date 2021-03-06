```
                       ▄ •▄  ▌ ▐·▪  ▄▄▄   ▄▄·     ▄▄▄ . ▌ ▐·▄▄▄ . ▐ ▄ ▄▄▄▄▄.▄▄ · 
                       █▌▄▌▪▪█·█▌██ ▀▄ █·▐█ ▌▪    ▀▄.▀·▪█·█▌▀▄.▀·•█▌▐█•██  ▐█ ▀. 
                       ▐▀▀▄·▐█▐█•▐█·▐▀▀▄ ██ ▄▄    ▐▀▀▪▄▐█▐█•▐▀▀▪▄▐█▐▐▌ ▐█.▪▄▀▀▀█▄
                       ▐█.█▌ ███ ▐█▌▐█•█▌▐███▌    ▐█▄▄▌ ███ ▐█▄▄▌██▐█▌ ▐█▌·▐█▄▪▐█
                       ·▀  ▀. ▀  ▀▀▀.▀  ▀·▀▀▀      ▀▀▀ . ▀   ▀▀▀ ▀▀ █▪ ▀▀▀  ▀▀▀▀ 
```

### About

#### :black_small_square: **```OnChannelMessage.kveventbotnoise.kvs```**

KVIrc and many other projects share a Bot service provided by [Notifico](https://github.com/notifico/notifico).  
This bot outputs messages current development related messages into [#KVIrc]{ircs://chat.eu.freenode.net:7070/#KVIrc), this is a valuable service.  

However, if you find that there's too much noise going on, but don't want to fully ignore all output, you can use the provided  
**```OnChannelMessage.kveventbotnoise.kvs```** which is a KVIrc event to silence **Bot** output for specific messages types, based on keyword.

>#### Default Keywords 

:black_small_square: **labeled**  
:black_small_square: **unlabeled**

>#### Extending Keywords

Its possible to filer any valid keywords

:black_small_square: **edited**  
:black_small_square: **commented**  
:black_small_square: ...

### Installation

:black_small_square: Download the respective script(s) to your local drive and place e.g. on your Desktop

>##### Via UI

:mans_shoe: In KVIrc press **```Ctrl+Shift+X```**  

:mans_shoe: Browse to your Desktop and select script  

:mans_shoe: Click Open

>##### Via command-line

:mans_shoe: In KVIrc input line type **```/parse path/to/the.script.kvs```**  
:mans_shoe: Press Enter

### Uninstallation

#### **```OnChannelMessage.kveventbotnoise.kvs```** has no automatic uninstall method at this time.  

>##### Manual uninstallation:

:mans_shoe: Press **```Ctrl+Shift+E```**  

:mans_shoe:* Find the event named **```OnChannelMessage```**  

:mans_shoe: Right click the ```kveventbotnoise``` handler and select **Remove**.  

:mans_shoe: Click apply and exit the Event Editor.

### License

[![my kvirc scripts GPLv2+](https://img.shields.io/badge/my_kvirc_scripts-GPLv2+-blue.svg)](LICENCE)