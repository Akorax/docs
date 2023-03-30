# Server setup

In this section we’ll talk about what you need to run your own server and we assume you already got basic knowledge of computer and network hardware. A private server can be run on your own computer, a computer on your local network or on a remote computer.

## System requirements

I (the author) haven’t found any hard specifications but servers will run alright even with a 10 year old CPU. RAM however will need to be proportional to your player count (or bot count). For this pack I personally recommend no less than:
-   RAM: 16GB
-   CPU: Intel core 4th gen
-   GPU: Noone needed for the server
-   HDD: 50 GB of free space*

*Space is assumed based on my current install which contains vanilla, TBC and WotLK at the same time.*

## Software

You can find links to the software in the [links](Links) section. **Installation instructions** are provided on the target website. You’ll be downloading a [CMaNGOS](https://cmangos.net/)-server which has a few tweaks to it and a simple yet extensive boot-menu. The package or *repack* will let you host WoW Vanilla, TBC or WotLK. See a list of features [here](https://singleplayerproject.com/viewtopic.php?f=4&t=373).

If you intend to invite your friends or family to the server you might want to take a look at [Local Setup](Setup2) or [Remote Setup](Setup3).

## Starting the server

Once you have installed the repack you’ll be facing three start-scripts.

![](../_media/820befcb08632edfda4211577a904ade.png)

-   **Server_fix.bat** can fix some errors you may encounter, the SPP
-   **Server_Start.bat** will start the *SPP Classics Collection-menu*
-   **Server_update.bat** will automatically download and update the software if there’s a new release available on [Github](https://github.com/celguar/spp-classics-cmangos/releases).

## The SPP Classics-menu

The SPP Classics Collection-menu is what you’ll be using to install, run and shutdown the server. You navigate the menu by writing numbers or letters.

1. First you'll face a grey colored menu where you choose the game version you want to host, the webserver can also be controlled from this menu.
2. After selection of game version you’ll face a second menu with more details and control over that specific version. Note that at the bottom of this menu is **Core version**, **Database version** and **Webserver version** which is useful info for troubleshooting.

![](../_media/045c6f39c7f15eda134ba7d377567c44.png)![](../_media/e9809bbdf451a960c04b8d43ddd409de.png)

## Beta vs release

**Beta Build Menu** can be reached from the second menu. There you can activate the *beta build* which gernerally contains more bugfixes than release but may also be less stable at times. Note that this menu only works if the server isn't running.

**Releases** are the more official versions of the repack and they're generally stable. The beta versions see more frequent updates but can run into unexpected issues that may for example cause the server to shut down itself. I recommend using the beta as the most annoying bugs are fixed fairly quickly but you do **have to switch back to release version every now and then** to get the core updates.

The easiest way of keeping track on when you have to update your release version is joining the **Mangosbots discord** (of which I don’t have a permalink right now so better ask for a link in SPP-discord).

![](../_media/a0da93389eac7191079e18d3f2a00c87.png)
