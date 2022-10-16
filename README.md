# update

This no longer works as of Chrome Version 106
if you are using any version before this it will still work

# ext remover

Bookmarklet exploit that can force-disable any extension installed on Google Chrome.

## Instructions

Here are the instructions to using this exploit! There are two ways, using the GUI and using the ids, the GUI method is better

### Using the GUI

Credit to CompactCow#4717 for the amazing UI!

1. Go to the file [`gui.js`](https://github.com/Potatosicle/ext-remover/blob/main/gui.js) and copy everything and create a new bookmark by right clicking on your bookmarks bar and selecting add page
2. Paste the code in the field that says URL and name it whatever.
3. Visit https://chrome.google.com/webstorex. (This is a 404 page, and that is ok.)
4. Click the bookmark (Make sure you are on the page above!)
5. Use the menu to toggle your extensions!

**If this helped please give me a star!**

![image](https://user-images.githubusercontent.com/58097612/190276894-fc492c5c-b0ce-4943-ae56-603f75634618.png)

### Using IDs

#### Disabling 

1. Visit chrome://extensions and on the extension you want to disable click on Details
2. Copy the text in the URL after the `?id=`
> For example if you have this URL: `chrome://extensions/?id=echoontop` you would only copy `echoontop`
3.  Go to the file [`bookmark.js`](https://github.com/Potatosicle/ext-remover/blob/main/bookmark.js) and copy everything and create a new bookmark and use the code you copied as the Page URL
4. Visit https://chrome.google.com/webstorex. (This is a 404 page, and that is ok.)
5. Click the bookmark (Make sure you are on the page above!)
6.  Put the ID you copied into the text box.

You're done! The extension should now be disabled.
