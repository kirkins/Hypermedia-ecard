#Hypermedia e-card

[Demo page](https://kirkins.github.io/Hypermedia-ecard/#)

This e-card is based off the [snowStorm javascript library] (https://github.com/scottschiller/Snowstorm).

The main changes to the SnowStorm demo are an attempt to follow a hypermedia pattern where the content of a multimedia application is completely seperate from the data. The hypermedia way of doing things also encourages making an application portable which is an advantage that the use of json has over traditional databases. The contents of this e-card can be put on a usb and viewed anywhere in the world, with or without an internet connection.

The only exception to that is the third image example defined in the demo json. The example json includes 3 ways to use the image src attribute base64, local, and web hosted. The third method web-hosted is significantly slower and stops the card from being used offline. For maximum speed I recommend using base64.

The project also includes a json schema file which can be used with json-schema based gui-builders. These builders allow non-programmers to create new instances of card with their own data, without ever having to open a text editor.

I hope to update this in the future by adding a GUI-based card-builder.

There are also some small changes to the original demo, for example I added the count-down so I'd have a better example for json attributes which needed to be properly validated.
