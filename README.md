## user.js
NARGA customized preferences to Enhance Firefox Productivity - user.js

---
This is personaly [NARGA Firefox's tweaks](http://www.narga.net/ultimate-guide-tweaks-enhance-firefox-productivity/) which focusing on debloated, speed, performance UI/UX, and more to enhance Firefox's productivity with some tweaks, disabling or removing unnecessary features, component, bloatware as well.

Unlike other similar projects, I built it by myself with my opinions, so may be all of these configuration is not best for you.

So, most important of all: *use your brain*, **don't just copy & past**

---
## Installation
- Copy then past the `user.js` file into your Firefox's profile folder (you can find the path of your profile folder via about:support).
- Restart your firefox to apply these tweaks.

## TODO
- [x] Arrange tweaks, settings in category with notes.
- [ ] Focusing on perfomance and privacy/security

## Source to know
Here are some resource that I've using in this collection of tweaks.
- pyllyukko's [user.js](https://github.com/pyllyukko/user.js)
- [firefox-debloat](https://github.com/amq/firefox-debloat)

## What does it do?
Here are some of the *highlights* from each category. For a full list of settings and references, check the `user.js` file itself.

### Firefox features
- Remove DRM media playback (Encrypted Media Extensions - EME)
- Disable Firefox Hello
- Disable Pocket intergration
- Disable built-in PDF viewer
- Disable HTML5 DOM local storage
- Enabled IndexedDB
- Disable Speed recognition
- Disable getUserMedia screen sharing
- Diasble sensor API
- Disable HTML5 pings
- Disable gamepad input
- Disable virtual devices
- Disable web notification services
- Disable webGL
- Disable face detection
- Disable Gnome Shell Integration
- Enable Click to Play feature
- Disable SVG OpenType fonts rendering ability
- Disable Share feature
- Disable "Snippets" (Mozilla content shown on about:home screen)

### Network Performance
- Enable Pipelining
- Tweak content timer-based reflows
- Decrease the waiting time before first displaying the page (default 250)
- Disable link prefetching
- Improve page load time by performing overhead for connections
- Enable Search suggestions
- Disable SSDP
- Disable support openh264 codec for peer-to-peer video when disable Hello
- Stop predictive connections to sites when the user hovers their mouse over thumbnails on the New Tab Page
- Disable Auto-update checking

### Firefox Performance
- Relocate cache to RAM
- Enabled HTTP Cache to get rid of most UI lags and other browser slowness issues
- Show full URLs in the address bar
- Get rid of the useless/redundant "Visit (site)" and "(keyword) - search with (engine)" dropdown in the URL bar (since FF43)
- Load searches from right-click context menu in background tab
- Remove "(site) is now fullscreen" nag message
- Disable tab animation
- Prevent sites from disabling the default right-click menu
- Prevent sites/popups from messing with certain UI elements
- De-crap new tab page, get rid of "directory tiles" ads
- Disable (broken) auto-scrolling via middle-click

### Privacy & Security
- Disable Google Safe Browsing
- Disable Block Reported Attack Sites
- Disable Safe Browsing remote lookups fore downloaded files.
- Stop Firefox stats collecting
- Disable Telemetry
- Enable Tracking Protection
- Prevent WebRTC leaks real IP
- Disable Gelocation & Geotargeting detect
- Don't reveal internal IP
- Stop getUserMedia
- Disable sending of the health report
- Disable New Tab tile ads & preload
- Disable Heartbeat

### Development Tool
- Enable eyedropper
- Use dark theme

### Plugins & Extensions
- Allow install unsigned addons
- Disable plugins & addons phone-home
- Opt-out of add-on metadata updates
- Update addons automatically
- Enable blocked addons
- Disable flash and get rid of missing flash plugin
