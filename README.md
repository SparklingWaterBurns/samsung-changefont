# samsung-changefont
A shell script to easily change the font on One UI devices. Doesn't use APKs. Have the original Samsung sans font app installed first.
Comes as a Magisk module.

It works by directly changing the font cache in /data/app_fonts/0, bypassing the need for APKs and signatures.
you can install it through magisk or copy the script and put it in your own ROM.
CREDIT ME FIRST PLEASE!!

# Usage
if you set it up correctly, you should be able to execute in your terminal by typing "changefont".
Your font .ttf file HAS to be named "DroidSans.ttf".

you can specify the directory as an argument. DON'T put "DroidSans.ttf" in the argument because the script already looks for that file.
If no argument is passed, the default directory ends up being /storage/emulated/0.
(This will be changed in the future.)

Example: changefont /data/local/tmp
It will copy DroidSans.ttf from that directory and into the font cache.
