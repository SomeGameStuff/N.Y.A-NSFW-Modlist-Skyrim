![alt text](https://i.imgur.com/LLmFq2o.png "Logo Title Text 1")
First things first: this list contains adult content and you must be of legal age in your country. This means 18+ in most countries, 21+ in others. It is up to you to be sure of the age requirement in your country.
Support and general talk about N.Y.A you can find on the following Discord: https://discord.gg/V38xZ6CtzQ



#### N.Y.A-NSFW-Modlist-Skyrim

Release Beta Test Version of N.Y.A. The List runs on 16640 Version. AE on its own.
You still need latest Skyrim Version + AE Content. You get the AE Content when you start Vanilla and Download it all atleast once.



#### Accounts

In terms of accounts you will need: Nexus Account, Premium would be best.

ALSO WARNING: You cant login anymore into Loverslab in the Wabbajack Settings. You have todo it now when the first Loverslab Mod pop up, you need to login over the Windows that pops up. If it works for you first time, good, if not only Login then restart the Install.


#### Please download the Mods Manually before Downloading the List with Wabbajack. Sometimes you will likely get lots of Errors and Stuff, and if you manually downloads these Things you can avoid some Headaches.

https://github.com/Millionsfrost/N.Y.A-NSFW-Modlist-Skyrim/blob/main/Downloads


#### Nexus Premium Account

LoversLab Account - for manual downloads through your browser.



#### Installation

I would heavily recommend that you download the LoversLab mods in your browser prior to running Wabbajack. Doing this may be long winded but can prevent a lot of issues from happening. All links to mods hosted on LoversLab can be found here.
( https://github.com/Millionsfrost/N.Y.A-NSFW-Modlist-Skyrim/blob/main/Downloads.md )

When downloading mods from Mega, always right click > Standard Download. Mega defaults to its "Download as ZIP" option will means it recompresses already compressed files and Wabbajack won't be able to recognise the download.
After downloading the non-Nexus mods, put them all into the folder you'd like the rest of the N.Y.A downloads to be stored in. If you have an existing Skyrim mods downloads folder from other modlists or your own modding, use that as you might have mods N.Y.A needs already, meaning you won't need to download those mods again.



#### Preparation

Install Microsoft Visual C++ Redistributable Packages
This package is a must as it is needed by MO2 - you may already have it if you've used MO2 before. If you do not have it, you want to download the x64 version under "Visual Studio 2015, 2017 and 2019".



#### Download Visual C++ Redistributable Package and the Thing underneath it.

Also get the Thing underneath, i think it was needet for Sexlab+.

https://dotnet.microsoft.com/en-us/download/dotnet/thank-you/runtime-desktop-7.0.15-windows-x64-installer



#### Setup your Page File

Skyrim modlists need a large amount of memory purely because of the amount of stuff in them - especially modlists on the larger side or with a lot going on. For the best experience, you should setup a pagefile of at least 20GB - yes, even if you have a million GB of RAM. To setup your pagefile;

Hold down the LEFT Windows key and press R
Type in systempropertiesadvanced in the run box and then press ENTER
Under the "Performance" option, click the "Settings..." button
Switch to the "Advanced" tab
Under "Virtual Memory", click the "Change..." button
Uncheck Automatically manage... if it's checked
Select your fastest SSD in the list of drives
Check "Custom Size"
Set Initial Size to 20480
Set Maximum Size to 40000
Press the "Set" button
Press OK
Press APPLY and then OK
Restart your PC to apply the pagefile setting
Setup your Shader Cache
Driver defaults from Nvidia and AMD for shader cache size is limited to 4GB. Being this small can lead to rare crashes in heavily modified out 4 installs. Increasing the shader cache size is done via the Nvidia Control Panel (I assume the same for AMD users is true also but I don't have AMD hardware to check with).

AMD USERS: See this link for some manual tweaks that may or may not help.

Open the NVidia Control Panel
Head to Manage 3D Settings
Scroll down in Global Settings to find the Shader Cache Size option
Set the Shader Cache to at least 10GB
Done

![alt text](https://github.com/iAmMe27/WoD/raw/main/img/ShaderCache.png "Logo Title Text 1")

#### Setup your Antivirus
Before you go down the route of "I don't have an antivirus" - you do, it's built into Windows. You need to exclude your Wabbajack folder and your WoD installation folder from your antivirus' real-time protection stuff as it will likely interfere with your install and worst case, it can remove files, ruining your install. It can and will interfere whilst you are playing too, causing poor performance and obvious stuttering.

How do I do this, you ask? Click here to find out how.

Note: If you're using Webroot or any other free 3rd party antivirus it's likely that adding the folders to exclusions will not be enough and you'll need to disable or uninstall your 3rd party AV as they can incorrectly mark usvfs_proxy_x86.exe, among other files, as a virus, a file needed for Mod Organizer 2 to work. We recommend doing so anyway in case it's a free one, as Windows Defender is likely much better at stopping threats than that is (according to data from av-test.org https://www.av-test.org/en/antivirus/home-windows/).



#### Disable Steam Overlay

The Steam overlay is known to cause issues when using ENBs. I recommend you turn it off to be sure that it doesn't interfere in any way and you can do so by heading into Steam, right clicking on Skyrim Special Edition in your game library and clicking Properties > General > Deselect "Enable Steam Overlay while in-game".



#### Set game language to English

Wabbajack and the modding tools out there only support English language versions of games. Setting the language to English in Steam will stop issues like Wabbajack file verification failures when installing. As with disabling the overlay, right click on Skyrim Special Edition in your game library and click Properties > Language > Select English.



#### Change Steam's Updating Behavior

If for some reason Bethesda decide to release an update for Skyrim, everything will probably break. Well, not everything but something will definitely break until mods can be updated to suit. To stop this from happening, you need to tell Steam that you only want to update when you tell it to. You can do this by right clicking on Skyrim in your game library and clicking Properties > Updates > Change Automatic Updates to "Only update this game when I launch it". Whilst you're in here, it's also recommended to disable Steam Cloud too.

Clean current Skyrim Special Edition installation
If you have not yet installed Skyrim Special Edition, you can skip this part.

Right click on Skyrim Special Edition in your game library and click Properties > Local Files > Browse.
Uninstall the game via Steam - right click on Skyrim Special Edition in your game library and click Manage > Uninstall.
Check the explorer window for any left over files - if there are any, delete them.
Open Windows start menu/search and type in %LOCALAPPDATA%.
Delete the Skyrim Special Edition folder.
Head to Documents\My Games and delete the Skyrim Special Edition folder.
Install Skyrim Special Edition
Once you've done the steps above, you can now set Steam to download Skyrim Special Edition again but do not install Skyrim Special Edition to a protected folder, such as Desktop, Downloads or Program Files of any kind. It's best to create a new, dedicated folder for it using the Steam Library function somewhere on the root of your drive such as C:\SteamLibrary. A lot of people have a dedicated secondary drive for their games, keeping the OS install separate; using this secondary drive will also work.



#### Start Skyrim Special Edition

That's right - start the game. You need to let the game do its initial start up jobs such as creating registry entries and generating default config files. Once you've gotten to the main menu you can close the game again. Also download all AE Content.



#### Wabbajack

Installing the list is straight forward, Wabbajack will do most of the heavy lifting for you - you only have to tell it where to put stuff.

Set the installation location to a folder on the root of a drive, something like C:\WoD. Do not install it to one of the protected folders as mentioned earlier. The download location will have likely been filled in for you too - ensure it matches the directory you set for the installation location, or if you have multiple Skyrim Special Edition modlists installed, use a common download folder - this will stop you from having to redownload common mods across multiple modlists.

Once you have everything set in Wabbajack, hit GO and let it do its thing. It might take a while as there is a fair bit to download and the speed of this will depend on your internet performance as well as your CPU in the later stages for hashing and unpacking the downloads.

You can verify your Install here

https://github.com/Oghma-Infinium/Modding-Guides/blob/main/tutorials/Verifying%20your%20Modlist%20Install.md




#### Please read very carefully from here on!!!!!!!!!!!!!!!!!

#### In the MCM Menu Skyrim Undbound you do your Settings and then press Lets go. When you are done with Character Creation please click Stay Here. Then go into the MCM Menus and go to MCM Recorder. Please run N.Y.A Nr1 Recording. When everything is finished ( Let Sexlab Install in Peace ) then please click enter and then Continue.

#### If you want a more stable Experience aka less Script Heavy Stuff, disable everything in relation to Paradise Halls, Diary of Mine and all its Addons. They are all close together in Mo2. Troubles of Heroines aswell. These are the big nsfw Mods atm in this List but some People might not like this Content.
So if you dont wanna use it feel free to disable it and all of its PATCHES.


#### Post Installation
#### Manual Settings

"Set CompassCheat to 1". Then save and reload the save ( Probably restart the Game ). ( If you want Compass back, other Lorefriendly Way is Campfire Perks )

Please remove the Autosave Feature in Skyrim Unbound for less Crashes on Character Creation for Future new Characters you create.

Please change the Hotkey from the Where are you MCM Menu for opening the Menu. Normal Key is F3 and that interferes with our Stances Mod. So pls rebind that. I use it on Comma Key and it works.

Later in the Game you can open the Int. Voiced Ditry Talk. Under Assign Voice you will pick Voice Slot 1. Then a new Screen opens. On the right side you will manually enter the Name of your Character, beware Typos. In the top right you can listen to Samples.
Under assign Voice as Default you pick Voice 2 for Females and for the Male one you can pick 1-8. Keep in Mind this is an Alpha Patch, so not everything might work 100%. Dialogue Options dont work yet.
You can also ignore all this and just dont use this Feature if you dont like Voices during Scenes. But this Mod also has moaning and such, so i think you wanna use it. You can fiddle around with it as you want.

Currently used version of Better Third Person Selection is 0.6.0. It was reported by some people that it can cause issues with Faster HDT-SMP and end up crashing the game on loading screens. If you experience such issues, please revert the Mod back to 0.5.9 and message me so i can think about using 0.5.9 in general for the List. Also send Crash Reports if you crash ONLY ON THE SAME SPOT more then twice. https://www.skyrimcrashdecoder.com/ Can be used to analyze Crash Reports but sometimes spits out nonsense Mods, so beware.

#### WARNING

If your Sexlab+ doesnt get started correct via MCM Recorder, ignore it and do it manually afterwads yourself. Just open it in MCM and click Install. Also activate "Disable Victim Controls" and disable "Auto Advance Stages". 


NOTE: DO NOT USE VANILLA as A START


#### Survival Mode

Do not use Survival Mode. It has been reported that with Survival there are many Freezes and Stuff and your Game will stop working!




#### Buttons

Middle Mouse out of Combat = Masturbation, but also you can try to seduce People while looking at them via your Sexcraft Perk Tree. ( You can change Sexcraft Key via Console Command, how to is on Sexcraft Modpage. )

To change the sex key use "set SCConfHotkeySex to XX" where XX is the DX Scan Code, see https://ck.uesp.net/wiki/Input_Script#DXScanCodes
To enable/disable the curves perk controlling weight use "set SCConfCurvesEnableWeightUpdate to 0/1" where 0 is off, 1 is on (Default is 1)
lots of other settings, see full list at https://www.loverslab.com/files/file/31540-sexcraft-a-speechcraft-overhaul-beta/



ß Button = Free Cam ( Button next after 0, can be adjustet. -> -_ Button = Free Cam ( Button next after 0, can be adjusted. For Sexlab/Scenes.

Middle Mouse = Target Lock

G Button = Quick Light

C Button = Dodge Roll

V Button = Block

< Button = Additional Attack ( Every Weapon Type has a Special Attack, if you equip an Ashes of War, same Button uses that. < Button is left of Y, in US cases Z i think. You can change this in the Additional Attack MCM.

L Button = Hunters Pride ( Turning this on and off lets you do things to downed Enemies )

ß Button = Free Cam ( Button next after 0, can be adjustet. Lets you go into free Cam in Sex Scene, or well in general. Dont use auto Freecam.


On this Link here: https://gist.github.com/MissCorruption/887725102fb18d96d43e26555e008bbb 
On the Page above you can check whats not compatible with Sexlab+
I should also mention Sexlab+ and Pandora are in an Alpha State, so some thing Like Orgasms/Sounds, Voices, Seperate Orgasms, Schlong Control Up/Down and some other Thints dont work yet, or dont work that well. I thought i just tell people upfront.
PS: We dont have Intelligent Dirty Talk working atm in an Alpha State aswell.

