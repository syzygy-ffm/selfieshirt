# #SelfieShirt

## What?

Selfies, Selfies, Selfies.  
2013 was the year of the digital self portrait.  
At the Academy Awards.  
At funerals.  
In advertising.  
And there is something else on the rise:  Wearable Tech. Glasses, bracelets, watches, whatever.  We put these two things together – and [we built the #SelfieShirt](http://syzygy.de/selfieshirt).  A wearable tech-shirt that liberates selfies from the digital space:  Every time someone tweets #selfie, your mobile phone sends a signal to your T- Shirt... and it flashes.Now we show you how to build the shirt.And we like you ro show us your creativity: Create your own shirt and share it with us: #Selfie-Shirt

## How does it work?
The shirt is equipped with a arduino based micro controller, a [bluetooth low energy](http://en.wikipedia.org/wiki/Bluetooth_low_energy) shield and a smart led for the flash effect. An iPhone communicates with the shirt based on notifications from a simple server. The trick here is that the iPhone is able to receive those notifications even when the app is in background mode. This enables you to use the phone as normal and the app will do it's thing only when needed - which helps saving battery power.

![HowItWorks](https://raw.githubusercontent.com/syzygy-ffm/selfieshirt/master/Content/HowItWorks.jpg)

## How can i do my own?

### Shirt
On our [accompanying website](http://syzygy.de/selfieshirt) we prepared a nice how-to for building the shirt and connecting the hardware to it.  
The needed arduino sketch for the controller can be found at [selfieshirt-controller](https://github.com/syzygy-ffm/selfieshirt-controller).

### Nodejs server
The server will take care of device registration, twitter polling, image extraction and sending push notifications. You can find it at [selfieshirt-server](https://github.com/syzygy-ffm/selfieshirt-server). For those of you that have no access to a server we provide a demo server at [http://selfieshirt.cloudapp.net]()

### iOS application
The iOS application that connects the server to the shirt is located at [selfieshirt-ios](https://github.com/syzygy-ffm/selfieshirt-ios). If you have no access to a mac or don't want to buy an apple developer account to compile your own, we provide you a precompiled version which is available at [https://syzygyffm.blob.core.windows.net/selfieshirt/index.html](https://syzygyffm.blob.core.windows.net/selfieshirt/index.html). Just open this url in your mobile browser and install it.


## Share it!

Build your own Shirt. Create, imitate, improvise, play around. And don’t forget to share: #SelfieShirt  
If you have any questions see [syzygy.de/selfieshirt](http://syzygy.de/selfieshirt) for more details and contact information.