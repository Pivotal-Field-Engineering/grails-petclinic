Petclinic Sample Application
============================

This is the standard introductory sample application for Grails. To get started with it, simply clone the repository and then from within your local copy run:

    ./grailsw run-app

on Unix-like systems, or

    grailsw run-app

on Windows via the command prompt. Once the server has started up, you can copy the URL and paste it in a browser.

Follow the tutorial link to learn about Grails or click on the View Source for Controller/View links to see the underlying code for whatever page you are currently on.

To build the app run

    ./grailsw war


### To deploy on Cloud Foundry
please have a look at manifest.yml You need to create a MySQL service called **petclinic-mysql**

    cf push
