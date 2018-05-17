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

Deployment
----------

jain slee server is the pre req to deploy this. So you can download the release candidate from following link:
https://github.com/RestComm/jain-slee/releases

You will find wildfly 10 in the zip. Go to wildfly->bin and run it by following command:

./standalone.sh



jain slee is now deployed. Now you need xmpp ra deployed. You can find the complete ra already built in the resource folder of restcomm release.

simply copy the jar file to deployments in wildfly.

After deploying the xmpp ra you can deploy the GoogleSBBTalkBot SBB jar.









