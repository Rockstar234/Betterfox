![GitHub Maintained](https://img.shields.io/badge/open%20source-yes-orange)
![GitHub Maintained](https://img.shields.io/badge/modified%20-yes-g)
![GitHub Maintained](https://img.shields.io/badge/gets%20updates-yes-g)
![GitHub Maintained](https://img.shields.io/badge/maintained-yes-yellow)

# Betterfox
[about:config](https://support.mozilla.org/en-US/kb/about-config-editor-firefox) tweaks to enhance [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/). 



---
---
## Getting started
*If you don't have it already: [Get Firefox](https://www.mozilla.org/en-US/firefox/all/#product-desktop-release)*

1) Create a [backup profile](https://github.com/yokoffing/Betterfox/wiki/Backup).
2) Download the user.js file [here](https://raw.githubusercontent.com/Rockstar234/Betterfox/main/user.js) (Right click > `Save Link As…`).
3) Review [Common Overrides](https://github.com/yokoffing/Betterfox/wiki/Common-Overrides) and make any necessary changes.
4) Open Firefox. In the URL bar, type `about:profiles` and press `Enter`.
5) For the profile you want to use (or use default), click `Open Folder` in the **Root Directory** section.
6) Close Firefox.
7) Move the `user.js` file into the folder.
8) Open Firefox and make changes in settings if you need.

*After restarting Firefox:*
1) Get an **ad blocker** like [uBlock Origin](https://addons.mozilla.org/blog/ublock-origin-everything-you-need-to-know-about-the-ad-blocker/) with our [recommended filters](https://github.com/yokoffing/filterlists#guidelines).
2) Go to `C:\Program Files\Mozilla Firefox\distribution` and put policies.json there. 
3) Restart again and then check `about:policies`, if you see tweaks there, then you're good to go.
    * You probably don't have distribution, so create it.
    * If your Firefox folder isn't in that path, so find it yourself and do the same steps.

### **Optional**
1) Enable **DNS-level protection** with [NextDNS](https://nextdns.io/?from=xujj63g5), and check out our configuration [guide](https://github.com/yokoffing/NextDNS-Config).
    * See how to [quickly enable](https://support.mozilla.org/en-US/kb/dns-over-https) **secure DNS** in Firefox.


See [Optional Hardening](https://github.com/yokoffing/Betterfox/wiki/Optional-Hardening) for other suggestions.

## Simple configs

| List      | Description |
|:---------:|-------------|
| [Fastfox](https://github.com/yokoffing/Betterfox/blob/main/Fastfox.js)   | Immensely increase Firefox's browsing speed. Give Chrome a run for its money!|
| [Securefox](https://github.com/yokoffing/Betterfox/blob/main/Securefox.js) | [Global Privacy Control](https://blog.mozilla.org/netpolicy/2021/10/28/implementing-global-privacy-control/). [HTTPS-by-Default](https://blog.mozilla.org/security/2021/08/10/firefox-91-introduces-https-by-default-in-private-browsing/). [Total Cookie Protection](https://blog.mozilla.org/security/2021/02/23/total-cookie-protection/) with [site isolation](https://blog.mozilla.org/security/2021/05/18/introducing-site-isolation-in-firefox/). Enhanced [state](https://developer.mozilla.org/en-US/docs/Web/Privacy/State_Partitioning) and [network](https://blog.mozilla.org/security/2021/01/26/supercookie-protections/) partitioning. [Telemetry](https://github.com/yokoffing/Betterfox/blob/e66a549985f6b0db4b14226904b8c09eaaea998f/Securefox.js#L1262-L1265) disabled. |
| [Peskyfox](https://github.com/yokoffing/Betterfox/blob/main/Peskyfox.js)  | Unclutter the new tab page. Remove [Pocket](https://support.mozilla.org/en-US/kb/what-pocket). Restore [compact mode](https://support.mozilla.org/en-US/kb/compact-mode-workaround-firefox) as an option. Stop webpage notifications, pop-ups, and other annoyances. |
| [Smoothfox](https://github.com/yokoffing/Betterfox/blob/main/Smoothfox.js) | Get Edge-like smooth scrolling on your favorite browser — or choose something more your style. |
| [user.js](https://github.com/yokoffing/Betterfox/blob/main/user.js) | All the essentials. None of the breakage. This is your `user.js`. |

`Fastfox`, `Securefox`, `Peskyfox`, and `Smoothfox` are guides to settings within Firefox.

The `user.js` — a configuration file that controls Firefox settings — is curated from these guides.

## Support

If you like the project, leave a :star: (top right) and become a [stargazer](https://github.com/yokoffing/Betterfox/stargazers)!

[![Stargazers repo roster for @yokoffing/Betterfox](https://reporoster.com/stars/dark/yokoffing/Betterfox)](https://github.com/yokoffing/Betterfox/stargazers)

## Credit
<div>
<img align="right" src="https://media.tenor.com/m_knf6IKaJwAAAAC/hi-fox.gif" width="110" height="120"/>
</div>

* Modified by [pr3ttyleaf](https://twitch.tv/pr3ttyleaf) for everyday usage and perfomance. [Buy me a coffee.](https://www.donationalerts.com/r/pr3ttyleaf)
* This repository benefits from the ongoing research provided by [arkenfox](https://github.com/arkenfox/user.js).
* Appreciation goes to the [Firefox](https://www.mozilla.org/en-US/firefox/new/) team and developers working on [Bugzilla](https://bugzilla.mozilla.org/home), fighting for the open web.
* A special thanks to [Alex Kontos](https://github.com/MrAlex94) of [Waterfox](https://github.com/WaterfoxCo/Waterfox) for his collaboration in v.116.
* Many thanks to the 2021 [Ghostery](https://github.com/ghostery) team for testing Betterfox at scale in its early days.

<div align='center'>
  <a href='https://www.websitecounterfree.com'><img src='https://www.websitecounterfree.com/c.php?d=9&id=19653&s=1' border='0' alt='Free Website Counter'></a><br / >
since 23 July 2022</div>
