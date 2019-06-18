
I'm learning how to use snapcraft as an alternative to dockerizing local applications.

This project is going to be a long term work in progress as I develop better methods of implementing snappy applications.  As a guinea pig, I'm going to use one of my go to rendering applications, Processing.  It's not the most powerful or the most reliable, but it's very point and shoot.  Plus it's a good candidate for learning snapcraft since it relies on java and running a installation shell.

To try it out: `snapcraft try` & `snap try $(pwd)/prime --devmode`



---

Notes:

Current setup:
 - sudo snap install --classic snapcraft # this installs snap craft which is the snap build tool
 - snapcraft init # creates a generic template for snap/snapcraft.yaml
 - snapcraft # does the building
 - snap install --devmode *.snap
