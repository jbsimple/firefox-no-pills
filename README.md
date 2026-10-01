# No More FireFox Pills:
Tweaks to the main FireFox UI to remove the nasty pills introduced in version 157.0.

# What it does:
* Adjust the border radius of the tabs.
* Shrinks tab width to something more space efficient.
* Adjusts the border radius of the address bar.
* Adjusts the border radius of the search and zoom indicator inside of the address bar.
* Adjusts the border radius of the drop-down of the address bar.
* Adjusts the circle buttons of the buttons in the toolbar.
* Adjusts the border radius of the bookmarks.
* Adjusts the border radius of all context or click menus.
* Adjusts the border radius of the buttons within context or click menus.
* Fix to background color of the search engine button in address bar on new tabs; matches theme accent color that zoom indicator uses.

# How to install:
1. Open about:config in Firefox, accept the prompt, and set `toolkit.legacyUserProfileCustomizations.stylesheets` to true.
2. Open about:support, find Profile Folder, and click Open Folder.
3. Open/Create a folder called `chrome` and enter.
4. Create a file `userChrome.css` inside of aforementioned chrome folder.
5. Paste in contents of `userChrome.css` from the repo.
6. Adjust any of the root variables as you see fit: `--goodbyePills` is the border radius used on all things mentioned above for consistency. I like 8px but you can set it to 0 and make everything a rectangle or 50% and truly live out the pill life. `--thinTabsMin` and `--thinTabsMax` are for the narrow tab widths.
7. There are other adjustments that can be made here, too.
8. Save, and relaunch FireFox
