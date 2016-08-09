Random User-Agent
=========

English:

Automatically replaces the User-Agent after a specified time interval

![Screenshot](http://oi58.tinypic.com/2znpqc5.jpg)

### Get the Plugin! [Google Webstore]

User-Agent - a string that is sent along to any website you visit. This is a sort of "fingerprint" your browser leaves behind which contains:
- The name and version of your browser;
- The name of the operating system (Mac, Windows, Linux, etc.) and its version;
- Information about some of the plugins installed on the browser;
- Other information that identifies and exposes you.

In order to stop this information being leaked out onto the web, I created this extension. Once installed, your browsers "User-Agent" will be automatically replaced after a specified period of time, significantly increasing your anonymity.

Thanks to @Ohblindone for english translate.

Version History (Changelog)
----

* **2.0.1** -
* **1.5.5** - Updated User-Agent strings. (Updated the extension to use more "current" browsers)
* **1.5.4** - Fixed issue where auto-refresh interval wouldn't change
* **1.5.3** - Minor syntax amendments related to 'use strict'
* **1.5.2** - Fixed a bug with loading settings (caused by the previous version update =) )
* **1.5.1** - Fixed a bug with loading settings (default only after restarting the browser)
* **1.5** - Added exclusion (exception) list, changed the default settings, excluded files "content.js", minor bug fixes
* **1.4.1** - Updated language packs, minor improvements
* **1.4** - Redesigned User-agent's algorithm change - no longer selects from one preset option, it now generates fully - have randexp.js to thank for it. Removed the field "Description" as it was not correct. A large number of small improvements
* **1.3** - Added German (de) localization, fixed bugs in the absence of initialization
* **1.2** - First release on Github

[Google Webstore]:https://chrome.google.com/webstore/detail/random-hide-user-agent/einpaelgookohagofgnnkcfjbkkgepnp
[randexp.js]:http://github.com/fent/randexp.js