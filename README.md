HTAConsole
==========

> Never use alert() again to debug your HTA application.

HTAConsole is a Javascript Console Log for HTAs (HTML Applications). It was made to increase HTA development productivity, and it does. It will also log errors that would normally appear in a popup box.

**HTAConsole does not require any dependency.**

##Features
* Usage of console.* for debugging
* Enter commands within the console
* Command History (Type `history` in the console to see all your commands)
* Clearing of console log (Type `clear` in the console)
* Transparency

##Installation and Initialization

Simply include the script file in your main HTA file, and it will initialize automatically.
```html
<script src="./Path/To/htaconsole.js"></script>
```
You can now use console.log in your application, or use directly the command line.

##Toggle
To hide and show the console, press `F12`, or insert this code :
```javascript
htaConsole.toggle()
```


