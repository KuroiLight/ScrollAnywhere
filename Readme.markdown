# ScrollAnywhere
###### A AHK Script that allows the user to quickly scroll windows that are not active.
###### Last tested working with Autohotkey Unicode 1.1.22.07

##### **Please note this script is no longer getting new feature updates only bug fixes; windows 10 now includes other window scrolling, (this script will still work in windows 10 however).**

#### Installation
> Download the pre-compiled binary, or download the .ahk file and install AutoHotkey_L from the official site and run the script. AutoHotkey_L can be found here https://github.com/Lexikos/AutoHotkey_L or http://ahkscript.org/

#### Usage

> Right click on tray icon to select mode or disable.

#### Scroll modes (select in tray)

* Off                     -> turns the script off.
* Software Scrolling      -> scrolling will be simulated using Sendmessage, doesnt have a adjustable scroll speed yet.
* Native + Activate       -> scroll using mouse, while windows and controls under the cursor get auto activated.
* FastScroll              -> (SoftwareScroll Only) makes scrolling faster, see INI Settings below.

#### INI Settings

iFASTSCROLL can be 0 for off or 1 for on.
iFASTSCROLLMODIFIER can be a number 1 to 10, being the number of times it will scroll additionally.
iFASTSCROLLKEY can be a key from the list here: http://ahkscript.org/docs/KeyList.htm any modifier symbols must be at the beginning (e.g. !+LWin). leave blank to disable hotkey.
