## Intro
This is a minimal Adium message style with touch of [Metro](http://en.wikipedia.org/wiki/Metro_%28design_language%29) design principles. Here is how it looks like (Empathy preview):

![](https://dl.dropbox.com/u/1401886/img/metro-adium.png)

It was only tested on Empathy, but should work on any program that supports Adium message styles (including Adium itself :)) Also, I recommend using [Open Sans](http://www.google.com/webfonts#UsePlace:use/Collection:Open+Sans) or [Droid Sans](http://www.google.com/webfonts#UsePlace:use/Collection:Droid+Sans) font, which are freely available from Google Web Fonts.


## Installation
 - **Linux and Empathy**

    Easiest way is to run this (just paste to the terminal along with line breaks):

        wget http://j.mp/metro-adium-dl -O [^] && mkdir -p ~/.local/share/adium/message-styles && \
        tar -C $_ -xvzf [^] --strip=1 metro-adium-master/Metro.AdiumMessageStyle && rm [^]

    You can do the same manually: download and decompress [latest repository snapshot](http://j.mp/metro-adium-dl), then put `Metro.AdiumMessageStyle` to `~/.local/share/adium/message-styles`.

 - **OS X and Adium**

    Download and decompress [latest repository snapshot](http://j.mp/metro-adium-dl), then just double click `Metro.AdiumMessageStyle`, Adium should do the rest =)

 - **Other systems and IM clients**

    Please consult corresponding documentation or community (it would be nice if you report back).

#### Any corrections, additions and improvements to the code and documentation are greatly encouraged, feel free to create issues or pull requests.

## Credits
This style was initially based on [the work of SoapyHamHocks](http://soapyhamhocks.deviantart.com/art/Windows-8-Messaging-style-332289807).
