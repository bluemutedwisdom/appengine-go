Google AppEngine Go SDK - Cloud application development
=======================================================

The Go language version of the `Google App Engine SDK`_ enables
developers to build Go web applications that can be hosted on Google's
App Engine platform, on the same scalable infrastructure that power
Google's own applications. App Engine applications are easy to build,
easy to maintain, and easy to scale.

We also have versions of the Google App Engine SDK for the `Java`_ and
`Python`_ programming languages.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Google AppEngine SDK configurations:
   
   - Installed from upstream source code to /var/www/google_appengine

- Includes TurnKey Web Control panel with useful information and
  references.
- Postfix MTA (bound to localhost) to allow sending of email (e.g.,
  password recovery).
- Includes Webmin Postfix module.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  Webmin, SSH: username **root**


.. _Google App Engine SDK: https://developers.google.com/appengine/
.. _Java: http://www.turnkeylinux.org/appengine-java
.. _Python: http://www.turnkeylinux.org/appengine-python
.. _TurnKey Core: http://www.turnkeylinux.org/core
