# OpenIEDemo1

A simple java program to run OpenIE(https://github.com/knowitall/OpenIE). This seems to be the simplest way though the only thing that needs to be done is building OpenIE assembly jar. 

Download the required version of openIE from https://github.com/knowitall/openie/releases. 

The project has been made with version v4.2.1, & downloaded the zip from https://github.com/knowitall/openie/archive/v4.2.1.zip.

Run sbt -J-Xmx2700M clean compile assembly

Add the jar(openie-4.2.1/target/scala-2.10/openie-assembly-4.2.1.jar) to the project classpath.

You are done, just run the main file as java application.

