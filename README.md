# Videoland Party Chrome Extension

This repository contains code for a Chrome extension to watch Videoland shows/movies synchronized with friends. It is a slightly altered version of the famous Netflix Party extension, so all credits to the original author!

## Development

You can test the extension locally by spinning up a local instance of the chat server (https://github.com/nielstenboom/videolandparty-server), be sure to point to a correct working URL in [content_script.js](content_script.js).

```
  // url of the chatserver, should be running and reachable, else extension does not work
  var serverUrl = "http://localhost:3000"
```

Then create a chrome extension from the location where you cloned this directory, for instructions on how to point chrome to a local extension see this URL https://developer.chrome.com/extensions/getstarted 

Now you can test and debug the application by opening two tabs playing the same video on Videoland https://www.videoland.com/