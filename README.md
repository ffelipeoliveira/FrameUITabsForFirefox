# FrameUI

Simple, elegant, minimal, like a polaroid photo.

![image](https://github.com/ffelipeoliveira/frameUI_tabs/assets/102631323/aa471fef-0b69-477f-8ea1-4a70ec9e406d)

# Installation step-by-step
**Installing**
* Download this repository's folder and extract it.`userChrome.css` will be inside it, you can copy it using CTRL+C keys.
* Search for `about:config` on your browser's searchbar.
* Click the `Accept risks` button on the confirmation page.
* Search for `toolkit.legacyUserProfileCustomizations.stylesheets` using the searchbar that will appear.
* Toggle to `true` using the toggle button.
* Search for `about:profiles` on your browser's searchbar.
* Click `Open folder` on `Root folder`.
* Your file explorer should have opened. On the folder that opened check for a `chrome` folder. If there's none then create it.
* Paste the `userChrome.css` file into your `chrome` folder and restart Firefox.

**Uninstalling**:
 * Delete `userChrome.css`.


# Screenshots 
*paired with Tabliss extension for firefox for better looking*

![image](https://github.com/ffelipeoliveira/frameUI_tabs/assets/102631323/ecc202ab-6bde-4afa-b353-0bd0bd098d4f)
![image](https://github.com/ffelipeoliveira/frameUI_tabs/assets/102631323/b63d4534-8c3e-4e4c-83fb-87a1fbed99c0)
![image](https://github.com/ffelipeoliveira/frameUI_tabs/assets/102631323/30857433-4136-40a8-bc45-646c63822c41)


*Main:*
![image](https://github.com/FineFuturity/FrameUIForFirefox/assets/19298107/73b7328d-3b6c-47f6-b4fe-d341aa46b88b)
![image](https://github.com/FineFuturity/FrameUIForFirefox/assets/19298107/2beeeb4b-99d6-4316-87cf-ca461f959516)

# Changelog

**Fork:**
* **0.2a**: Bug fixes
* **0.2**: Added theme support for tabs.
* **0.1c**:  Added workaround for theme support on tabs.
* **0.1b**: Fixed line appearing on the bottom right.
* **0.1a**: Fixed buggy application menu transition.
* **0.1**: Added Centered, semi transparent tabs and transitions. Two flaws were introduced: A tiny line on the bottom right of the screen and the transition on the menu is buggy. I'm working on it.

**Main:**

**Version 0.3a:**
* The latest Firefox update caused some issues with clicking on interface elements, including the window controls.  The latest update to the theme fixes this issue.
  * I'm not sure if the update caused any other issues, so please report them as you see them.  
* Fixed the alignment of the private browsing indicator when in private browsing mode.
 

**Version 0.3:**
* Better support for configurations where the title bar buttons are either on the left or right side of the window, regardless of OS.
  * HUGE thanks to MrOtherGuy's CSS ![code](https://github.com/MrOtherGuy/firefox-csshacks/blob/master/chrome/toolbars_below_content.css), without which I would not have been able to fix this as well as the below issues.
* Fixed issues with the menubar not playing nicely with the navigation bar when it's active.
* Fixed issue with the private browsing indicator icon being misaligned with the navigation bar when in private browsing mode.
* Fixed issue where the bookmarks toolbar would push the navigation toolbar past the bottom window boundary if "Only Show on New Tab" was set.
* When clicked, the address bar's URL text now stays at the bottom rather than moving to the top.
  * This should make typing a URL or search term much less jarring.


**Version 0.2:**
* Initial macOS support.
  * Platform detection has been added, so the theme now accounts for configurations where either the title bar buttons are on the left (e.g., macOS/Linux title bar buttons on left) or on the right (e.g, Windows/Linux title bar buttons on right).
* Fixed issue with user-selected themes either working inconsistently or not at all.
* Inactive window title bars are now darker to differentiate them from the active window.
 
**Version 0.1:**
* Initial release

# Known Issues
* The entire area of the nav bar cannot be used to drag the window in the 0.3 update.
  * I am still figuring out how MrOtherGuy's code works and should be able to fix this in the next update.

* ~~Haven't found any just yet.  Please report if you find any. :)~~
* ~~Menu bar overlaps with the navigation bar when it's active.~~
* ~~The private browsing indicator icon is misaligned with the navigation bar when in private browsing mode.* The bookmarks toolbar pushes the navigation toolbar past the bottom window boundary if "Only Show on New Tab" was set.~~
* ~~When clicked, the address bar's URL text moves to the top of the results dropdown rather than staying in place.~~

**macOS note**
* FrameUI was designed to have the window control buttons on the bottom. However, due to the way that fullscreen windows work on macOS, the window control buttons will remain at the top of the window like other macOS apps. This complication is not present in windowed mode.

# Notes from fork:
* This fork isn't itended to be merged into the main repo since it's intended to be a workaround for those who, like me, prefer the native horizontal tabs insted of vertical ones, which are preferred by FineFuturity.
* It have yet to be tested on Mac, I've only used it on a Ubuntu and Windows 10.
* I'm inexperienced on Firefox customization, so there will be lots of erros. If you want please tell me suggestions and report issues, I plan on improving this and keep up to date with the main repo.
  
# Notes from main:
* After restarting, you'll notice that *all* of the controls -- the navigation bar, the window controls, *everything* -- has been moved to the bottom in a manner reminiscent of the Metro-based Internet Explorer app seen in Windows 8/8.1.  While I think Microsoft was on the right track with their attempts at a tablet-based interface... well, we all know what happened.  Apart from Microsoft's attempt at a touch interface (which was a half-done attempt anyway), I think no company to this day has yet to get right.

* This theme is a step towards what I believe may solve the grand problem of unifying the desktop and tablet interface for ANY device form factor.  What I hope you'll find is that this interface works really well on *both* tablet and desktop form factors, precisely because there is no longer a need for a user to lift their arms to get to something as basic as the window controls -- they're now just a mere finger reach away.  

# Reporting Issues
FYI, this project is my first go at using CSS.  As this is the initial release on top of that, I anticipate there will be issues.  If you encounter any bugs or other issues, please post a thread and I'll do what I can, when I can. 
Also: as this theme is a both a thought experiment and work in progress, it is possible the look and feel will change over time.  I welcome any and all suggestions for how this could be improved.  :)

# Credits
* HUGE SHOUTOUT to MrOtherGuy's ![Collection of random CSS hacks for Firefox](https://github.com/MrOtherGuy/firefox-csshacks) repo.
* Private testers (who I can name here if they wish)



