# microbitResourceLibrary
A set of resources that can be used with microbit.  

Using global constants or local litertals in your program can be costly - the memory available on a micro:bit is severely limited.

The objective of the resource library is to allow for richer programs to be built for microbit. </br>
It does this by providing a range of resources that can be used with a simple function call. </br>
The resource library includes Strings and images.  Images are for the 5x5 LED array and also for a SSD1306

For example: </br>
... to print the String "It is the end of the world as we know it" you would call a function like: getString("200001") </br>
... to show an animation of 10 images on the microbit 5x5 LED array you would call a function like: showAnimation("10001") </br>
... to show an image on an SSD130 (128x64 OLED array) you would call a function like: showImage("30002")

The library is designed to be saved on persistent memory (e.g. on a microSD card).
Given the capacity of microSD cards and the average size of an asset in this library (less than 30Kb) we have the opportunity to build up a vast library of resources.

Where no persistent memory is available it is possible to use specific assets from the library:
... identify the resource required
... open the associated text file
... set up the binary String as a constant in your code.
You won't be able to 
