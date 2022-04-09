# qvm-screenshot

A small yet effective way to take region screenshots in Qubes (in dom0), and auto upload them to a VM / Qube.

# How to use

After vetting this script, copy to dom0 (this can help with that: https://www.qubes-os.org/doc/how-to-copy-from-dom0/)

I recommend creating the dir /opt/qvm-screenshot and placing it there

Go to your Qubes app menu > system tools > keyboard

Click add and browse to this file. Assign the shortcut "Windows Key + S" (or Super + S).

Setting this up will mean pressing "Windows key + S" (or Super + S) will allow you to select a region of your screen for a screenshot, and upload it as a timestamped .png file to your vm (vault by default in this script)

# How this could be better

- Option for fullscreen, or region screenshots
- Option to be able to copy to the global clipboard, and then paste into a Qube
- Option to select a VM to copy this to after taking the screenshot
- Allow configuring a custom name for a screenshot (omitting the file name from the screenshot command can enable this)

No intention to do this currently since this serves my purposes, and adding the above will just make the task take a little longer. Being able to take a screenshot and be able to copy / paste would be a great features, however much more investigation on how to do this is likely required.
