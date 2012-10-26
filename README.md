Tycho Plugin
============

This is an example Eclipse plugin, built to demonstrate the basic workflow for
creating an Eclipse plugin which deploys to a P2 repository.

Compiling
---------

    $ mvn clean install

Deploying
---------
The install task deploys to the local Maven repository and packages into the
p2 repository project. To deploy to the remote Maven repository:

    $ mvn deploy
