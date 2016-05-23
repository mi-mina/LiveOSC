# My version of LiveOSC

I have made small changes to the LiveOSC API in order to get what I need for my app.

#### Changes Log

/live/name/clip/ send a bundle of messages and I want to know when the last one is sent.  
line 498 Added: `self.oscEndpoint.send("/live/name/clip/done", "bundle sended")`
