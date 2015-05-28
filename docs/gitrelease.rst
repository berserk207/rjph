Git Release Process
===================

Intro
-----

The release process will apply to all PH releases (internal tools and front-facing websites). 

The Process
-----------

Development
~~~~~~~~~~~

This process will mostly involve the develop and feature branches. The process starts when the developer receives the request via redmine. The first step that needs to be done is to create a new feature branch for that request. This can be done using either tortoisegit or sourcetree (or by using git commands).

Features are named thusly:

.. note::
	- feature/grmXXX* - green redmine requests
	- feature/rmXXX* - blue redmine requests
	- feature/jprmXXX* - JP redmine requests
	- feature/asYYmmddX** - Chatter asana requests

	- *XXX stands for the redmine number.
	- **YYmmdd is the current date, X is [a-z] depending on the sequence of the request for that day.