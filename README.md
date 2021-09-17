# Simple YouTube Age Restriction Bypass

A very simple to use userscript to bypass YouTube's age verification by retrieving the video info from YouTube's incompletely restricted ``/youtubei/v1/player`` endpoint. As fallback (for some non-embeddable videos) an open source <a href="https://github.com/zerodytrash/Simple-YouTube-Age-Restriction-Bypass/tree/main/account-proxy">Account Proxy Server</a> is used. This allows you to watch age-restricted videos without login and without age verification. All videos will be unlocked automatically.

![youtube-age-restriction-bypass-v3](https://user-images.githubusercontent.com/59258980/133007022-c12253c0-036c-49fe-8fce-42b62da14e8a.png)


## Installation
1. Install the Tampermonkey extension for your browser:<br>
&bull; [Tampermonkey for Chrome](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)<br>
&bull; [Tampermonkey for Firefox](https://addons.mozilla.org/en-US/firefox/addon/tampermonkey/)<br>
&bull; [Tampermonkey for Opera](https://addons.opera.com/en/extensions/details/tampermonkey-beta/)<br>
&bull; [Tampermonkey for Brave](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo)<br>
&bull; [Tampermonkey for Edge](https://microsoftedge.microsoft.com/addons/detail/tampermonkey/iikmkjmpaadaobahmlepeloendndfphd)<br>
&bull; [Tampermonkey for Safari](https://apps.apple.com/app/apple-store/id1482490089?mt=8)<br>

3. Add "Simple-YouTube-Age-Restriction-Bypass.user.js" by clicking [this link](https://github.com/zerodytrash/Simple-YouTube-Age-Restriction-Bypass/releases/latest/download/Simple-YouTube-Age-Restriction-Bypass.user.js).
4. Done.


## Usage
No further actions are necessary. All age restricted videos are automatically unlocked.

## Mobile Device Compatibility
This script also works with the mobile YouTube website (m.youtube.com). But currently only [Kiwi Browser for Android](https://play.google.com/store/apps/details?id=com.kiwibrowser.browser) and [Firefox Nightly for Android](https://play.google.com/store/apps/details?id=org.mozilla.fenix) supports extensions. In Kiwi Browser you can simply visit the Chrome Web Store to install [Tampermonkey](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo). After that add the script.
Using [NewPipe](https://github.com/TeamNewPipe/NewPipe) for Android is probably easier. But currently (2021-07-30) age-restricted videos do not seem to work in NewPipe. An update will hopefully be released soon.

## Development
We use [babel](https://github.com/babel/babel) to transpile the components into a single userscript file. If you want to customize the script follow these steps:
1. Clone this repository
2. Install the required packages with `npm install`
3. To create the userscript run `npm run build`

## Alternative mirrors
Greasyfork: https://greasyfork.org/en/scripts/423851-simple-youtube-age-restriction-bypass <br>
OpenUserJS: https://openuserjs.org/scripts/zerodytrash/Simple_YouTube_Age_Restriction_Bypass
