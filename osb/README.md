OSB Build
============

Prerequisites:

- Ant (I tested with 1.9.4, but earlier versions might work as well)
- An installation of Oracle Service Bus PS6 and Weblogic (their libraries are going to be used during the build)

How to use:

- Place these files on a project in the same level as your OSB Project and Config. For example:
	

	|- OSBConfig

	|- OSBProject
	
	|- osb-builder (this project)
	
- Update build.properties with the configuration of your environment
- CD into the directory of the builder project
- Run Ant
