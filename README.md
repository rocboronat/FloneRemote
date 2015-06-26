# FloneRemote
A Multiwii drone remote controller, driven with performance in mind.

### Current features
- Autoreconnection: if connection drops, the app will try to connect again to the drone automatically
- Automagic heading: the drone will mimic your orientation automatically
- Connects with the drone via Bluetooth
- The communication is handled in a Service, so the drone wouldn't fall if someone calls you
- It works with all Multiwii boards, not only the Flone

### Next releases features
- Connection via WiFi Direct
- Connection via Internet (using a phone to drive the drone, and another one on the drone to connect the drone to the Internet)
- Get the altitude of the drone above the ground
- Get the GPS location of the multiwii board
- Get the GPS location of the phone, when connecting over the Internet (for boards without GPS)
- Do you have an idea? [Create an issue!](https://github.com/aeracoop/FloneRemote/issues/new) 

## The project goal
This is what we want to reach. The main issue is that we update the mockup frequently...!<br/><br/>
![The goal](https://github.com/aeracoop/FloneRemote/blob/master/balsamiq/Mockup.png)

## Pictures
Some pictures of the yet-flying totally Open Hardware drone:<br/><br/>
![The Flone](http://fewlaps.com/xtra/flone/flone-projecting.jpg)<br/>
![A broken Flone](http://fewlaps.com/xtra/flone/flone-broken.jpg)<br/>
![Flone at RNE](http://fewlaps.com/xtra/flone/flone-at-RNE.jpg)

## References
Like you guess, we didn't this magic alone. We want to thank these great projects:
- [@zjusbo's Multiwii-Remote](https://github.com/zjusbo/Multiwii-Remote): to connect the phone with the multiwii board
- [@greenrobot's EventBus](https://github.com/greenrobot/EventBus): the great way to have a Bus in your loved Android
- [@google's GSON](https://github.com/google/gson): a standard and simple way to work with JSON
- [@square's Phrase](https://github.com/square/phrase): a fancy way to format strings

## Download
Get it at [Google Play!](https://play.google.com/store/apps/details?id=com.fewlaps.flone) 

## Want to know more about Flone?
Don't hesitate to read the official website: http://flone.aeracoop.net/
