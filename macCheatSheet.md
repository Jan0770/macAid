# MacAid


Much of this comes down to personal preference in the end, just see if you like any of this yourself.

<br>

## Finder
___
Finder can be set to display your folders and files in columns. Click on the highlighted icon and select "columns". 

You can navigate using the arrow keys. 

<image src="./images/FinderColumnsSmall.png" width=400>



From a certain window size upwards, Finder will display the column symbol directly.

<image src="./images/FinderColumnsLarge.png" width=500>


<br>
<br>


## Installing apps on Mac
___
After you download an app on Mac, it shows up as a dmg file in your Downloads folder (if you didn't specify a different target location). 

If you click on the dmg, a Finder window pops up that shows the installed application and your Applications folder. Move the app icon to your Applications folder. Close the window afterwards.

Example: I downloaded Steam, clicked on the dmg and this window pops up. 

<image src="./images/move app to applications.png" width=300>

(Steam is a bit of a stupid example since Mac doesn't like games too much but lets pretend it makes sense)

If you now click on the Finder, Steam will still show up as a "mounted image". You can click the dismount button next to it (this also works to dismount USB-drives etc.) and delete the dmg in the Downloads folder. Steam can still be found in the Applications folder. 


<image src="./images/dismount dmg.png" width=400>


Some apps will also lead you through a "normal" installation, in that case, follow the instructions. 

<br>
<br>


## Shortcuts
___
Many shortcuts on Mac are the same as with Windows, some are different. Anyhow, here is a list with a couple useful ones. 

> - "command + C" -> Copy
> - "command + V" -> Paste
> - "command + Q" -> Close application
> - "command + W" -> Close window
> - "command + N" -> Open new window
> - "command + A" -> Select all
> - "command + shift + N" -> Create new folder
> - "command + Z" -> Undo
> - "command + backspace" -> Delete
> - "command + tab" -> Switch through applications
> - "command + spacebar" -> Open spotlight search (search anything on your machine or the web)
> - "command + arrow left/right" -> Jump to beginning/end of line
> - "option + arrow left/right" -> Jump to beginning/end of words

<br>
<br>

## Touchpad
___

<br>

Go to System Settings -> Trackpad to adjust some behaviours.

If "Secondary click" is set to "Click or Tap with two Fingers", you can do a right-mouse click by clicking files/folders with two fingers.

Try the "Tap to click" option. A click can now be done by gently tapping the trackpad. 

<br>

Go to System Settings -> Accessibility -> Pointer Control -> Trackpad Options. Set "Dragging style" to "Three-finger drag".

Now you can drag&drop things by placing the cursor on files/folders and then using three fingers to move it.

<br>
<br>

## Invisbile Dock icon & Spectacle
___

Check Spectacle for Mac, a quick Google search should bring up the app. Lets you swiftly organize app windows without manually adjusting window-size. 

<br>

If you want to organize the Dock (the bar at the bottom of the screen with all the things), check out application spacers. 

Enter the following code into your Terminal (without the "quotationmarks"). An invisible icon will appear. 


"defaults write com.apple.dock persistent-apps -array-add '{"tile-type"="spacer-tile";}'; killall Dock"

<br>

<image src="./images/InvisibleDockIcons.png" width=600>



