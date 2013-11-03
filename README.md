ICSImport
=========

ICSImport is a small free and open source app for Android that intercepts the VIEW intent for text/calendar files and allows to add it to the calendar. At the moment it does not need any calendar-related permissions because it acts as a bridge. The original .ics file is parsed and the event is added using the native calendar application. This way you are free to change the event details before saving.

Building
========

The project should build as-is. Be aware that you need to use ant. The libraries contained in this project are taken from the [ical4j project](http://ical4j.sf.net/).


TODO
====

At the moment the project needs testing. A lot of testing! Especially this aspects are currently untested:
* Time Zone
* Full-day events 
* ICS files containing multiple events
* ...