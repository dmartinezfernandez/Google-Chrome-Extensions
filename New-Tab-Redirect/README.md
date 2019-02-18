# Google-Chrome-Extensions-NewTab-Blank
1. Download manifest.json and newtab.html from https://github.com/dmartinezfernandez/Google-Chrome-Extensions-NewTab-Blank.
2. Change newtab.html redirect url if you want to change 'about:blank' behaviour.
3. Open chrome://extensions/.
4. Enable developer mode.
5. Load unpacked manifest.json and newtab.html files from download directory.

See https://developer.chrome.com/extensions/override for more information.

See [Hide Chrome's Disable developer mode extensions warning](https://www.ghacks.net/2017/07/04/hide-chromes-disable-developer-mode-extensions-warning/). I only want a blank new tab, so I only need to configure (gpedit.msc) the policy "User Configuration/Administrative Templates/Google Chrome/New Tab Page/Configure the New Tab page URL".
