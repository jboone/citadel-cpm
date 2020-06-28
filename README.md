# citadel-cpm

Citadel BBS for CP/M computers, with Kaypro 2X modifications.

I've taken the `ctdl210.zip` sources, cleaned them up a bit, and added configuration and code to support the internal 300 baud modem in my Kaypro 2X computer.

# Compiling

You'll need the BDS C compiler 1.4 to build this. It's available on the Internet, and is apparently being distributed with consent of the BDS C author. Do not use BDS C 1.6, as the C API it implements in its standard library has changed (to be more like the modern C we all know and love). If you wanted to compile using BDS C 1.6, you'd need to port some of the code to the new C API.

# License

Changes made to the source are by Jared Boone. I'm unclear how to license my changes. [The original source was placed in the public domain](1STREAD.ME). I'd license my changes as Apache + MIT, as seems popular these days for very permissive projects. But I'm not sure I can do that on top of a public domain project?
