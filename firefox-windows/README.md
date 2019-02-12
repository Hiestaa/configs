# Readme

## How to create the userChrome file?
_Thanks to https://www.userchrome.org/how-create-userchrome-css.html for detailed explanation_

### 1.  Open your currently active profile folder

The quickest way to open the profile folder in Firefox right now is to launch it from the Troubleshooting Information page. To access that page, you can use any of these methods:

* Click the menu button ("hamburger" menu button), then Help ("?" button), then Troubleshooting Information
* On the top menu bar, click Help, then Troubleshooting Information. To activate a hidden menu bar on Windows, tap the Alt key or the F10 function key.
* Type or paste `about:support` in the address bar and press Enter/Return to load it.

In the first table on the page, find the Profile Folder row and click the button to the right, which will say "Open Folder", "Show in Finder" or "Open Directory" on Windows, Mac or Linux, respectively. This should launch a new window with your system's file browser (e.g., Windows Explorer). You should see numerous files and folders. On Mac, if Finder shows you a semi-randomly-named folder, double-click that folder to view its contents.

### 2. Create a new folder named `chrome`

### 3. Copy the `userChrome.css` file in this folder

## How to inspect browser styles and rapidly test changes
_Thanks to https://www.reddit.com/r/FirefoxCSS/comments/7xr7nb/knowing_the_name_of_the_elements/ and for asking the question and DanTheMan74 for getting us a response_

Firefox has a dev-tool modus that calls itself "Browser Toolbox" and you can find an entry to it in the web developer sub-menu of the hamburger menu. A bit quicker is the shortcut ctrl+shift+alt+i. Once the new window opens you should also get a pop-up that asks you to accept or deny the connection request. Unless you have configured the browser to automatically accept these, hit "OK".

You now have an element picker and can use it on a lot of the Firefox interface, at least the immediately visible one. Things like menus and other interactive displays are more challenging. Personally, I'm using the dxr.mozilla.org website, which offers a fulltext and regex search of the browser's source code.

That's no doubt a bit more challenging than just looking up an applied CSS selector, but it's the most powerful method I know of.




