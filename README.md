# tesser_OSCSend

This device sends out one stream of messages via OSC. It also alllows to store the OSC prefix and to scale the input value as needed.

![img/gui.png](img/gui.png)

---

## ISSUES

* It can only send out one stream of values. It is problematic if there are more than one controller!

* OSCpipe should help with that. (I keep this one as it is for backwards compatibility)