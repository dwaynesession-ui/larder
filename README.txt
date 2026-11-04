LARDER: install it on your phone

Larder is a web app that installs like a regular app. It has to be hosted once
on a free website (any https address). After the first visit it works fully
offline, and your data stays on your phone.

EASIEST WAY (about 5 minutes, free)
1. Unzip larder-app.zip on a computer. You get a folder called "larder-app".
2. Go to https://app.netlify.com/drop and sign up for a free account.
3. Drag the "larder-app" folder onto the page. Netlify gives you a link
   like https://something-random.netlify.app
4. On your Android phone, open that link in Chrome.
5. Tap the menu (three dots), then "Install app" (or "Add to Home screen").
   On iPhone: open the link in Safari, tap Share, then "Add to Home Screen".

Larder now has its own icon, opens full screen, and works with no signal.

BONUS ON ANDROID
- Share to Larder: in any app (Chrome, Notes, Messages), select text,
  tap Share, and pick Larder. It opens the Paste screen with your text.
- Long-press the Larder icon for a "Paste" shortcut.

BACKUPS
Your lists, recipes and prices are stored only on that phone. In Larder,
open Settings, then "Download backup file" now and then. Use "Restore from a
backup" to move everything to a new phone.

UPDATING
If you replace index.html with a newer version, also change VERSION in sw.js
(for example to larder-v2) and upload the folder again.
