# PitchDark-Fox
Firefox Stylesheets intended for my Personal use. Sharing them since I've benefitted immensely from others sharing their own work.

![PitchDarkFox](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/pitchdarkfox.gif)

### NOTE
This is just a collection of stylesheets that I've cobbled together, after Proton Update broke my earlier stylesheet. This is NOT a 'release' of theme/style for firefox, for several reasons:

1. Much of it is based on others' hardwork. [**See Credits**](https://github.com/im-hm/PitchDark-Fox/blob/main/README.md#credits)
2. It was always meant for personal use. So, I've hidden many elements which many people would find useful; tweaked height/width of menus, etc to my own liking
3. I've been working on these stylesheets on my main profile, which is heavily modified. I'm not sure if everything in it would work as intended on a different profile, different resolution, different OS.
4. I don't have a programming background. I only have a working knowledge of css, acquired mostly through trial and error. Hence, while I can make it work for myself, I won't have any clue if it doesn't work for you.
5. Due to 4, I haven't followed CSS Best Practices while putting together these stylesheets. Ex, I couldn't for the life of me figure out how to make some of my rules apply to about-addons. So, I ended up using universal selector (*) 

The best use anyone can make of these stylesheets would be to look for individual code snippets for styling an individual component, and using it for creating one's own style. The stylesheets won't work as intended on setups different from my own (having different resolution, different buttons on toolbar, different user settings, etc).

## CREDITS

1. [**MrOtherGuy's firefox-csshacks**](https://github.com/MrOtherGuy/firefox-csshacks) for One-Liner, about:addons column view, multi-row urlbar dropdown results, and numerous other minor tweaks
2. u/MotherStylus has helped with styling many problematic elements over at [**r/firefoxcss**](https://reddit.com/r/firefoxcss). His gems of scripts at his [**duskFox repository**](https://github.com/aminomancer/uc.css.js) have helped me extend functionality, style tooltips. I've also stolen many rules from his repo.
3. [**Izheil's Quantum Nox**](https://github.com/Izheil/Quantum-Nox-Firefox-Dark-Full-Theme/) for introducing me to the realm of add-on themes. Their themes for uMatrix, uBlock Origin, and Containers form the base for my own themes. 
4. [**PROxZIMA's Sweet_Pop**](https://github.com/PROxZIMA/Firefox-Theme/) inspired the use of gradient line below Navigation Toolbox. Their code for styling library helped me achieve dark mode for libray view.
5. u/dilfool2nice's [**Firefox BlueMoon**](https://github.com/GrosBourrin/FIREFOX-BLUE-MOON/) helped me style ctrl+tab preview, inspired use of gif in About Firefox dialog.

## PREVIEW

### About Firefox Dialog
![AboutFirefox](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/AboutFirefox.png)

### All-Tabs View
![AllTabsView](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/AllTabsView.png)

### Clear All History Dialog
![ClearAllHistoryDialog](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/ClearAllHistoryDialog.png)

### Close Window Dialog
![CloseWindowDialog](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/CloseWindowDialog.png)

### Context Menus
![ContextMenus](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/ContextMenus.png)

### Create Profile
![CreateProfile](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/CreateProfile.png)

### Ctrl+Tab View
![CtrlTabView](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/Ctrl%2BTabView.png)

### Downloads View
![DownloadsView](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/DownloadsView.png)

### Edit Bookmark
![EditBookmark](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/EditBookmark.png)

### HTTPS Only Error
![HttpsOnlyError](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/HttpsOnlyError.png)

### Library
![Library](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/Library.png)

### Net Error
![NetErrorPage](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/NetErrorPage.png)

### New Private Window Page
![NewPrivateWindowPage](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/NewPrivateWindowPage.png)

### New Tab Page
![NewTabPage](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/NewTabPage.png)

### PDF Viewer
![PDFViewer](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/PDFViewer.png)

### Page Info
![PageInfo](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/PageInfo.png)

### Print Dialog
![PrintDialog](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/PrintDialog.png)

### Save File Dialog
![SaveFileDialog](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/SaveFileDialog.png)

### Tracking Protection Popup
![TrackingProtectionPopup](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/TrackingProtectionPopup.png)

## USAGE

The best use anyone can make of these stylesheets would be to look for individual code snippets for styling an individual component, and using it for creating one's own style.

### Using the stylesheets as they are:

For using as they are, these stylesheets require:

1. Fira Sans Font https://github.com/mozilla/Fira/releases/
2. Dark Magic Theme https://addons.mozilla.org/en-US/firefox/addon/nicothin-dark-magic/
3. Certain Scripts from [**u/MotherStylus's repository**](https://github.com/aminomancer/uc.css.js)
4. Scrips need to be loaded with [**fx-autoconfig**](https://github.com/MrOtherGuy/fx-autoconfig), as detailed in above repository
5. [**chrome.manifest**](https://github.com/aminomancer/uc.css.js/tree/master/utils) from u/MotherStylus's repository - for restoring Pre-Proton icons - since I've scaled down toolbarbuttons, and new thinner icons look horrible when scaled.

Scripts Required:

1. [**userChrome_as_css_module.uc.js**](https://github.com/aminomancer/uc.css.js/blob/master/script/userChrome_as_css_module.uc.js) for styling tooltips
2. [**allTabsMenuExpansionPack.uc.js**](https://github.com/aminomancer/uc.css.js/blob/master/script/allTabsMenuExpansionPack.uc.js) 
3. [**atoolboxButton.uc.js**](https://github.com/aminomancer/uc.css.js/blob/master/script/atoolboxButton.uc.js) - as I've hidden 'Inspect Element' from context-menu
4. [**searchSelectionShortcut.uc.js**](https://github.com/aminomancer/uc.css.js/blob/master/script/searchSelectionShortcut.uc.js) - as I've hidden 'Search *InsertSearchEngineName* with' from context menu
5. [**restoreTabSoundButton.uc.js**](https://github.com/aminomancer/uc.css.js/blob/master/script/restoreTabSoundButton.uc.js) - as I've hidden 'Playing' Label from tabs playing media

All the stylesheets and folders included in this repo need to be placed directly inside chrome folder in firefox profile.

Rules from TreeStyleTabs-TextArea.css (inside Extensions folder) need to be copied, and pasted in text area provided by TreeStyleTabs Addon in about:preferences. 

## STYLING ADDONS

Themes for Addons are contained in 'Extensions' folder. For styling addons, you've to go to about:debugging, copy Internal UUID of addon, and paste in addon's stylesheet, in place of 'Enter Internal UUID here'. Addons I've styled:

### Auto Tab Discard
https://addons.mozilla.org/en-US/firefox/addon/auto-tab-discard/

![AutoTabDiscard](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_AutoTabDiscard.png)

### Bitwarden Password Manager
https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/

### Bypass Paywalls Clean
https://addons.mozilla.org/en-US/firefox/addon/bypass-paywalls-clean/

### Clear URLs
https://addons.mozilla.org/en-US/firefox/addon/clearurls/

![ClearURLs](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_ClearURLs.png)

### Cookie Auto-Delete
https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/

Works only if addon is placed in Overflow menu. The style breaks the addon's popup, if placed directly on the toolbar. 

![CookieAutoDelete](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_CookieAutoDelete.png)

### Dark Reader
https://addons.mozilla.org/en-US/firefox/addon/darkreader/

![DarkReader](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_DarkReader.png)

### Enhancer For Youtube
https://addons.mozilla.org/en-US/firefox/addon/enhancer-for-youtube/

![EnhancerForYoutube](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_EnhancerForYoutube.png)

### Local CDN
https://addons.mozilla.org/en-US/firefox/addon/localcdn-fork-of-decentraleyes/

![LocalCDN](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_LocalCDN.png)

### Multi Account Container
https://addons.mozilla.org/en-US/firefox/addon/multi-account-containers/

![MultiAccountContainer](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_MultiAccountContainer.png)

### Notes By Mozilla
https://addons.mozilla.org/en-US/firefox/addon/notes-by-firefox/

![NotesByMozilla](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_NotesByMozilla.png)

### Save WebP as PNG
https://addons.mozilla.org/en-US/firefox/addon/save-webp-as-png-or-jpeg/

![SaveWebPasPNG](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_SaveWebPasPNG.png)

### Set Tabs Aside
https://addons.mozilla.org/en-GB/firefox/addon/tabs-aside/

### Temporary Containers
https://addons.mozilla.org/en-US/firefox/addon/temporary-containers/

### Translate Web Pages
https://addons.mozilla.org/en-US/firefox/addon/traduzir-paginas-web/

![TranslateWebPages](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_TranslateWebPages.png)

### Tree Style Tab
https://addons.mozilla.org/en-US/firefox/addon/tree-style-tab/

![TreeStyleTab](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_TreeStyleTab.png)

### uBlock Origin
https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/

![uBlockOrigin](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_uBlockOrigin.png)

### uMatrix
Requires latest Pre-Release Version of uMatrix from https://github.com/gorhill/uMatrix/releases

![uMatrix](https://github.com/im-hm/PitchDark-Fox/blob/main/Previews/addon_uMatrix.png)
