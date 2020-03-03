# plex-autoplay-time-patch
**Plex**: Reduces the auto play time to 5 seconds.
Tested in the web view.

## Installation
Apply the patch file to:  
`/usr/lib/plexmediaserver/Resources/Plug-ins-77cb9455c/WebClient.bundle/Contents/Resources/js`  
`chunk-2-7f5e9044ba52846083b1-plex-4.22.2-2a5c45e.js`

May be called slightly different if the plex version changes/depending on your profile.
If in doubt, grep for `secondsLeft`.

Credit: [kdizzley](https://www.reddit.com/r/PleX/comments/8mgr5r/how_to_disablechange_15_second_autoplay_delay/)
