Only works for WebKit based browser (Chrome, Safari, ...)
=========================================================

Video demo
----------
http://www.youtube.com/watch?v=zpP0Ob8vpgA

Installation
------------

- Create a new Bookmark.
- In the "Name" field, you can put "AirdroidNotifier".
- In the "URL" field, Copy and Paste following lines :
<pre>
    javascript:(function(){
        var jsFile=document.createElement('script');
        jsFile.setAttribute("type","text/javascript");
        jsFile.setAttribute("src", "https://raw.github.com/FlorianBezagu/AirDroid-Webkit-Notifier/master/airdroid-webkit-notifier.js");
        document.getElementsByTagName("head")[0].appendChild(jsFile);  
    })();
</pre>
That's it !


Usage
-----

- Open your Airdroid as usual.
- LOGIN BEFORE NEXT STEPS
- Click the bookmark you created before : (DO NOT OPEN IN A NEW TAB !)
  - The first time, you will see a button "Enable desktop notifications for AirDroid"
  - Click this button and click "Allow".
- Ask a friend to send you a message and see the result !

NOTE
----

- You have to click the bookmark each time you login to your Airdroid.
- Desktop notifications question is asked only the first time.
- It doesn't work yet for http://web.airdroid.com access. Use your IP address instead. This case is checked now and you can enable this notifier, you'll have a choice to do.

Enjoy ! ;-)


Troubles ?
----------

Tell me what is your problem : florian@bezagu.com
