RapidFTR
=============

RapidFTR is a mobile application that lets aid workers collect, sort and share information about children in emergency situations. RapidFTR is
specifically designed to streamline and speed up Family Tracing and Reunification efforts both in the immediate aftermath of a crisis and during ongoing recovery efforts.

RapidFTR allows for quick input of essential data about a child on a mobile phone, including a photograph, the child's age, family, health status and location information. Data is saved automatically and uploaded to a central database whenever network access becomes available. Registered aid workers will be able to create and modify entries for children in their care as well as search all existing records in order to help distressed parents find information about their missing children. Because RapidFTR is designed specifically to collect and distribute information about children, data security is extremely important.

Initial development is focused on building an API and web interface, with subsequent development of on-phone applications for multiple mobile platforms.

Find more information at the [project website](http://rapidftr.com)
and join the [google group](http://groups.google.com/group/rapidftr/)

Developer Info
-------------

We're working with developers from ThoughtWorks and around the version on version one of the API and Web Interface.
You can get the source code by forking the GitHub repositories.
Please feel free to comment or contribute.

Join the google group and read through the wikis on the main repo for how to join the project.

* [RapidFTR Repository](http://github.com/jorgej/RapidFTR/)
* [RapidFTR BlackBerry Repository](http://github.com/jorgej/RapidFTR---BlackBerry-Edition)
* [RapidFTR Android Repository](http://github.com/jorgej/RapidFTR-Android)

RapidFTR is being developed using Ruby on Rails and CouchDB. Alongside the development of the API,
we've also started to develop the BlackBerry client, with an Android client to follow.
If you've got experience with any of these and want to help, please get in touch.

Install and run RapidFTR on OSX
-------------

PLEASE SEE [INSTALLATION INSTRUCTIONS](http://wiki.github.com/jorgej/RapidFTR/install-and-run-rapidftr-on-osx)

To run RapidFTR
-------------

1. From the command line, go to the folder where your GitHub repo is and enter this command which will start SolR and the application server:

        rake app:run

2. Open CouchDBX

4. in a browser, go to:

    http://localhost:3000/children
    or
    http://localhost:3000/users/

    CouchDB itself should be running here: http://localhost:5984

    You should also be able to see the built-in database admin tool, Futon, here: http://localhost:5984/_utils/

Story Development
-------------

Stories should be on the [website](http://rapidftr.com/userstories/) which pulls from  [mingle](https://minglehosting.thoughtworks.com/unicef/projects/rapidftr/)

Cucumber & RSPEC Tests
-------------

To run cucumber tests, type in the command line:

    cucumber

To run rspec tests, type in the command line:

    rake spec

