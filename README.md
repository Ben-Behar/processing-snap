

steps:
 -
 - sudo snap install --classic snapcraft # this installs snap craft which is the snap build tool
 - snapcraft init # creates a generic template for snap/snapcraft.yaml
 - snapcraft # does the building
 - snap install --devmode *.snap
