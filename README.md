BBEdit-LMs
==========

A compilation of BBEdit language modules that I use, initially I am putting modules I have created here, if I end up with others in here I will make sure to show attribution etc.


###Dockerfiles.plist
This CLM goes for a simple handling of the Dockerfile syntax. It allows files to either be named "Dockerfile" (case-insensitive), or \*.docker. It highlights the base Dockerfile keywords as well as core shell keywords. Strings are allowed using ' or " and are __NOT__ allowed to be multiline. It will also honor comments using #.