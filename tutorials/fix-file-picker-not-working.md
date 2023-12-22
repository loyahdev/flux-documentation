---
description: >-
  This issue is due to you sideloading Flux with an app such as ESign or
  Scarlet.  Though, if you’re using ESign, this issue can be fixed. If you are
  using Scarlet, you are out of luck.
---

# Fix File Picker Not Working

**(Tutorial by @ Gnalraid or “Gid”)**

&#x20;First you need to go into your settings tab, certificate management, and then press on the certificate and it should be looking for an app ID.\
\
You want to copy the app ID where it starts on “Com”. After that, you want to change the bundle Id for the app into the copy text.\
\
Then, when you see signature and more setting, you want to press more settings and you should see the mobileprovision remove after signing. You want to toggle that on and then sign it. \
\
Now, install it and it should work normally
