# 🐺 awesome-librewolf-profile

A (my personal) LibreWolf template that makes the browser less fingerprinting-proof, but more usable on the current web. Features add-ons like uBlock, LocalCDN, CanvasBlocker and more.

## 💡 About

I often switch between or reinstall Linux distributions and therefore tend to set up my browser a lot. I dislike wasting time on this and therefore created this repository. There might be a better way to do what I am trying to accomplish, but storing a pre-configured LibreWolf profile in git seems good enough to me.

### 💭 What has been changed compared to a base LibreWolf install?

Not much, actually! Here is a list of preferences that have been changed, compared to a fresh LibreWolf profile:
* DRM content can be viewed
* The start/new tab page has been slightly changed
* Automatic history, cookie and download history cleaning has been disabled
* Sent search queries and form entries will be saved instead of discarded
* userChrome.css customization has been enabled 
* ResistFingerprinting and "silently block canvas access requests" have been disabled
* WebGL has been enabled

## 🧩 Plugins included

* uBlock Origin
* Bitwarden
* Dark Reader
* Stylus
* LocalCDN
* Canvas Blocker
* Tab Stash
* YouTube Channel Whitelist for uBlock Origin
* Sponsor Block
* Return Youtube Dislike
* Don't track me Google
* FastForward
* Minimal Consent
* Facebook Container
* Link Cleaner

## 💻 Installation

* Download/clone the repository
* Open the LibreWolf browser and type `about:profiles` into the address bar.
* Create a new Profile.
* Open the root (NOT local!) folder of the newly created profile
* Replace all files inside the root folder with the contents of this repositories' `profile-root` folder.
* In LibreWolf, set the new profile as your standard profile.
* Restart the LibreWolf Browser.
