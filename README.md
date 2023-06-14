`janar`: Best Lecturers' Quotes (University of Edinburgh)
========================================================
 
`janar` is an R package that contains several main functions based on the names of UoE lecturers  (for example `wendy()`), which play a sound from a recorded lecture with a funny remark. It's purpose is obvious - when you are feeling sentimental about your uni and our wonderful lecturers, you can easily replay some of the best moments fro lectures. It is also intended to be useful, for example, if you are running a long analysis in the background and want to know when it is ready, you simply put the sound at the end of your script..
 

Installation
----------------

You can install the development version of `janar` directly from github:
 

```
library(devtools)
install_github("Janka1112/janar")
```

Requirements
---------------

If you are using Windows or OS X `janar` relies on the `audio` package for sound playback and no external program is needed.
 

If you're on Linux, I have no idea how it works.
 

Details
------------

`wendy()` plays a short quote from Professor Wendy Johnson which is useful if you want to get notified, for example, when a script has finished. As an added bonus there are a number of different sounds to choose from.
 

### Usage
 
`wendy(1)`

### Arguments
 

`x`  is a number specifying what sound to be played by either specifying one of the built in sounds or specifying the path to a wav file. The default is 1. Possible sounds are:

1. "Shut up"
 

2. "Thank you"
