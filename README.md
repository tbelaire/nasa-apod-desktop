nasa-apod-desktop
=====

Python Script to Download the NASA APOD and Set it as Your Background for OSX
-----

About:
=====
The popular NASA Astronomy Picture of the Day produces wonderful images that make for a great desktop background. This script will download the NASA APOD and set it as your background in OSX.

![NASA APOD Example](http://randomdrake.com/nasa_apod.jpg "An example of a NASA APOD image.")

http://en.wikipedia.org/wiki/Astronomy_Picture_of_the_Day

http://apod.nasa.gov/apod/astropix.html

Tested on, OSX 10.7.4
During testing, it just sets the backgroud for the space you happen to be on at 6AM, or when the computer unsleeps next.


Development:
=====
I just modified it to work on OSX, and commented out the use of PIL and the resizing of the image, as OSX can deal with that itself.
Now I've learned how to set a up a launchd plist file to make it run once a day.


Installation:
=====
* Place the file wherever you like and chmod +x it to make it executable
* Set the defaults in the file 
* Move net.belaire.nasa_apod_desktop.plist to ~/Library/LaunchAgents
* Run 'launchdctl load ~/Library/LaunchAgents/net.belaire.nasa_apod_desktop.plist'.

To Do:
=====
* Nothing, I don't really intend to do much with it.

License:
=====
Open-source and free for use.
>Copyright 2012 David Drake
>
>Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at
>
>http://www.apache.org/licenses/LICENSE-2.0
>
>Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License. 

Author:
=====
David Drake 

[@randomdrake](https://twitter.com/randomdrake) | [http://randomdrake.com](http://randomdrake.com) | [LinkedIn](http://www.linkedin.com/pub/david-drake/52/247/465)


Modifier:
=====
Theo Belaire
