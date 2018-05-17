JAIN SLEE XMPP
==============

About
-----

This is an example to use xmpp resource adapter for jain slee and to run the GoogleTalkBotSBB.


Brief overall introduction
--------------------------

JAIN SLEE XMPP contains 2 folders: examples and resource

examples have code for "GoogleTalkBotSBB" and deployment unit. 
resource have all the code for "RA" "RAType" "library" "events". 

Setting up
----------

clone or download the master. Import it in JBoss or Eclipse.

File->Open projects from File system->Navigate to the folder containing jain-slee.xmpp

It will list down all the nested projects too. Just deselect all and select the root project. Press Finish

The project should be loaded now. Right click and run as 'maven build'. It may open run configurations.

Base directory should be: ${project_loc:jain-slee.xmpp-master} add 'clean install' in the goals.

Running it now will generate the required jars.








