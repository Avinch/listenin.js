# listenin.js
## Setup
**Step 1:** Create a [last.fm](http://www.last.fm) account and set up scrobbling

It's simple, really. Just click 'Join' in the top right corner of [this] (http://www.last.fm) page, enter some details, verify your email and you are set! If you want, you can tell them your music tastes, but you don't *have* to do that.

After that, go to [http://www.last.fm/start/scrobbling](http://www.last.fm/start/scrobbling) to set up scrobbling. Follow the instructions for your preffered service from there. From there, go to your profile and click the little RSS icon next to "Recently Listened Tracks". You'll need that page later.

**Step 2:** Add these sippets to the header(s) of the webpage(s) that you want to display this feed on: 
```javascript
<script src="http://www.google.com/jsapi" type="text/javascript"></script>
<script src="listenin.js" type="text/javascript"></script>
```
Also, add this to the body of your webpage(s). This is where the feed will be displayed on your page.
```<span id="listenin"></span>```

**Step 3:** Go to the listenin.js and change ```YOUR FEED HERE``` on line 15 to the feed URL from earlier.(Keep the quotation marks)

**Step 4:** ???

**Step 5:** Profit!

If you have any questions, tweet me [@thesamja](twitter.com/thesamja). 

