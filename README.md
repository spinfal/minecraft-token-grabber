# MCToken Grabber
A simple way to gain access to a Minecraft account. No username/email/password needed.

# How does this work?
When someone runs the `mc-token` file, it grabs the Access token from their `.minecraft` folder and some other files. It then sends it all over a webhook to your server.

# How can I get someone to run mc-token?
Use something like `pyinstaller` to turn it into an EXE file, and have someone run it
 - `pyinstaller --onefile mc-token.py`

# How do I use the Token Login tool?
Simply [download](https://github.com/spinfal/minecraft-token-grabber/releases/) then run the EXE file and follow the prompts it gives you

# Extra Info
I wrote/made all of this, but I got inspiration from this repo: [wodxgod/Minecraft-Session-Token-Stealer](https://github.com/wodxgod/Minecraft-Session-Token-Stealer). This code and tool I made is in no way as advanced as wodxgod's, but it does work.
