# Darkmode Bookmark
> Enable dark mode from bookmark with Darkmode.js

## Usage
Create a bookmark and modify the url to follow code.
```javascript
javascript:(function(){var%20script=document.createElement('script');script.type='text/javascript';script.src='https://cdn.jsdelivr.net/npm/darkmode-js@1.5.7/lib/darkmode-js.min.js';document.getElementsByTagName('head')[0].appendChild(script);const%20options={label:'🌙'};const%20darkmode=new%20Darkmode(options);darkmode.showWidget();})()
```
Then enable dark mode on any page by click on the bookmark (Sometimes you may need click it twice).
