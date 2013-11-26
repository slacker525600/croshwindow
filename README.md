croshwindow
===========

Crosh Window opens a new Crosh window without any chrome so that Ctrl-N/T/etc work. Chrome OS only.

Forked this to try and figure out why my crosh window app stopped working. 
after playing around a little bit, I assume chrome added a security feature to prevent launching an app / extension
using window.open('chrome-extension:/') ~shorthand. 
tried using chrome.api to open a new window, but only opens relative to the app. 
will continue investigating, currently just developing in my chroot.
