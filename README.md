# samsung-changefont
A shell script to easily change the font on One UI devices. Doesn't use APKs. Have the original Samsung sans font app installed first.
Comes as a Magisk module.
**ROOT IS REQUIRED, OBVIOUSLY!**

It works by directly changing the font cache in /data/app_fonts/0, bypassing the need for APKs and signatures.
you can install it through magisk or copy the script and put it in your own ROM.
CREDIT ME FIRST PLEASE!!

# Usage
if you set it up correctly, you should be able to execute in your terminal by typing "changefont".
you can optionally specify the path as an argument.
If no argument is passed, the default path ends up being /storage/emulated/0/DroidSans.ttf.

Example: changefont /data/local/tmp/custom.ttf
It will copy the font file from that directory and into the font cache. It will be renamed DroidSans.ttf with a duplicate file being named DroidSans-Bold.ttf.
