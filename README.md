[GAE-Gaelyk](http://gae-gaelyk.appspot.com) - Groovy / Gaelyk / Google App Engine Base App
==============================================

GAE-Gaelyk Base-App
---------------

[Project-GAE](http://project-gae.appspot.com) is a multi-platform app-engine base-app created by 
Mark Finch to assist developers looking to build their first applications 
leveraging Google's Cloud Infrastructure. GAE-Gaelyk is adapted from 
[GAE-Py](http://gae-py.appspot.com) project.

The GAE-Gaelyk version of Project-GAE uses the Groovy Language along with 
the [Gaelyk](http://gaelyk.appspot.com) Framework to provide a simple application base to launch
new Google App Engine Applications from.  

Features of version 1 include Ad-Sense integration, examples of how to 
use basic templates, access the datastore to create and read.  Another 
goal of version 1 is to have a very simple application to benchmark 
various frameworks running on App Engine.  The reason to keep it simple 
is to see how much a performance hit a framework has on App-Engine.
GAE-Gaelyk is anticipated to perform the in the middle due to the extra
weight of Java and Groovy libraries.  We hope to answer how the Gaelyk
framework performs on App Engine with version 1 of Project-GAE.

NOTE: Due to App Engine requirements version numbers will all be integers.

Goals:
------
  * Version 2
    * Add update and delete
    * Add registration
    * Add authentication and application security
  * Planned Features
    * Add Date/Time Conversion from UTC
    * Add Gravatars
    * Add Validation and Error Handling
    * Error Pages (404...)
    * Add Safe HTML to Shouts
    * Integrate with Twitter / Facebook / MySpace / ...
    * Many many more!!!

Application Stack:
------------------
  * Google App Engine Java
  * Groovy Language
  * Gaelyk Framework
  * Blueprint CSS Framework


Issues:
-------
  * THIS APP IS NOT PRODUCTION READY!!!
  * App currently implicitly trusts user input (a really big NO NO for Production)
  * There is no validation and error handling
  * No Authentication

No Warranties:
-------------
There are no warranties expressed or implied.  Use at your own RISK!

License:
--------
GAE-Gaelyk Base-App source code is licensed under the [Apache 2.0 License](http://www.apache.org/licenses/LICENSE-2.0).  

Please check the file LICENSE to see other licenses that impact this project.

