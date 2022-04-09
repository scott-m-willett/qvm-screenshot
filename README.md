# qvm-screenshot

A small yet effective way to take region screenshots in Qubes (in dom0), and auto upload them to a VM / Qube.

# How to use

After vetting this script, copy to dom0 (this can help with that: https://www.qubes-os.org/doc/how-to-copy-from-dom0/)

I recommend creating the dir /opt/qvm-screenshot and placing it there

Go to your Qubes app menu > system tools > keyboard

Click add and browse to this file. Assign the shortcut "Windows Key + S" (or Super + S).

Setting this up will mean pressing "Windows key + S" (or Super + S) will allow you to select a region of your screen for a screenshot, and upload it as a timestamped .png file to your vm (vault by default in this script)
