# Private WhatsApp™ Web ![Logo](https://github.com/UsmanAhmadSaeed/Private-WhatsApp-Web/blob/main/src/images/icon32.png?raw=true)
[![GitHub license](https://img.shields.io/github/license/UsmanAhmadSaeed/Private-WhatsApp-Web.svg)](https://github.com/UsmanAhmadSaeed/Private-WhatsApp-Web/blob/main/LICENSE) [![Chrome Web Store](https://img.shields.io/chrome-web-store/users/jbojhlhhggfmmkpefknmbdhlaghehini.svg)](https://chrome.google.com/webstore/detail/privacy-extension-for-wha/jbojhlhhggfmmkpefknmbdhlaghehini) [![Tweet](https://img.shields.io/twitter/url/https/github.com/UsmanAhmadSaeed/Private-WhatsApp-Web.svg?style=social)](https://twitter.com/intent/tweet?text=&url=https%3A%2F%2Fgithub.com%2FUsmanAhmadSaeed%2FPrivate-WhatsApp-Web)

<p align="center">
  <img width="48%" title="WhatsApp™ Web with the extension" alt="WhatsApp™ Web with the extension" src="https://github.com/UsmanAhmadSaeed/Private-WhatsApp-Web/blob/main/screenshots/PFWA_Header.png?raw=true">
  <img width="48%" title="WhatsApp™ Web with the extension" alt="WhatsApp™ Web with the extension" src="https://github.com/UsmanAhmadSaeed/Private-WhatsApp-Web/blob/main/screenshots/PFWA_Settings.png?raw=true">
</p>

## Credits

### This project is based on "Privacy Extension for WhatsApp™ Web" extension by Lukas Lenhardt available at his [Github Repository](https://github.com/LukasLen/Privacy-Extension-For-WhatsApp-Web). I've modified the code to my liking and updated the code for it to work with latest WhatsApp release as on September 08, 2023. I've not updated the "no transition delay" and "unblur all on app hover" options, so these might be broken.
### The links to webstores of Chrome and Firefox below are of original project and extension from which this project was forked. This ReadMe has not been fully updated either and some links might be broken, while others lead to original repository or website/webstores. Feel free to reach out for helping improve the project or anything in general.

To increase privacy in public spaces the Private WhatsApp™ Web blurs your messages as well as other content and only reveals one when you hover over it with your mouse cursor. Additionally, you can quickly toggle all effects by using a keyboard shortcut or by clicking the toggle button in the extension menu.

**Customize it**

It adapts to your needs by letting you decide which elements you want to blur. Your options:

- All messages in chat: *Blurs all messages in the current chat.*
- Last messages preview: *Blurs all message previews on the left.*
- Media preview: *Blurs all images, videos, stickers, ... in separation from the text.*
- Media gallery: *Blurs all small icons of images, videos, ... while viewing an image, video, ...*
- Text input: *Makes the color in your input field lighter to make it hard to read.*
- Profile pictures: *Blurs all profile pictures.*
- Group/Users names: *Blurs all group and usernames.*
- No transition delay: *Allows you to turn off the delay before revealing an item on hover.*
- Unblur all on app hover: *Unblurs all elements when you hover over the WhatsApp Web app.*

**Quick Toggle**

You can quickly toggle the blur in the settings or with a keyboard shortcut (Default: Alt+X).
To change this navigate to:
 - Chrome: "chrome://extensions/shortcuts"
 - Firefox: "about:addons" -> Settings icon on the top right -> Manage Extension Shortcuts

## Installation
Available for both Chrome and Firefox.

### Chrome
- Install if from [https://chrome.google.com/webstore/detail/privacy-extension-for-wha/jbojhlhhggfmmkpefknmbdhlaghehini](https://chrome.google.com/webstore/detail/privacy-extension-for-wha/jbojhlhhggfmmkpefknmbdhlaghehini)

### Firefox
- Install if from [https://addons.mozilla.org/firefox/addon/privacy-extension-for-whatsapp/](https://addons.mozilla.org/firefox/addon/privacy-extension-for-whatsapp/)

### For development purposes on Chrome
- Download the newest release [here](https://github.com/UsmanAhmadSaeed/Private-WhatsApp-Web/releases) and unzip it
- Rename the file /src/manifest-chromium.json to /src/manifest.json
- Navigate to chrome://extensions/
- Activate the developer mode (on the top right)
- Click on "Load Unpacked"
- Select the "/src" folder from your unzipped download (this folder has to be persistent so you might want to keep it somewhere where you won't delete it)
- Check back here for new releases

## Issues and Feature Requests
If you have a feature request or if you have encountered a problem, please create a new issue under this link: [https://github.com/UsmanAhmadSaeed/Private-WhatsApp-Web/issues](https://github.com/UsmanAhmadSaeed/Private-WhatsApp-Web/issues)

Alternatively you can get help at: PWA@UsmanAhmadSaeed.com

## License
This project is licensed under the MIT License - see the [LICENSE](https://github.com/UsmanAhmadSaeed/Private-WhatsApp-Web/blob/main/LICENSE) file for details.

### Acknowledgments
- [Eye Icon](https://www.iconfinder.com/icons/1608687/eye_slash_icon)


---
> This extension does not collect information about you or your messages. We only communicate with our server to display information about problems or updates. Visit the privacy policy to learn more.
>
> ***Disclaimer:*** *WhatsApp is a trademark of WhatsApp Inc., registered in the U.S. and other countries. This extension is an independent project developed by Lukas Lenhardt and has no relationship to WhatsApp or WhatsApp Inc.*
>
[//]: # (> [*Legal and Privacy notice*])