TrainingApp
===========

Play Store Link
===============
The app is also available for free in Google's [Play Store](https://play.google.com/store/apps/details?id=de.uwr1.training).

Contact
=======
http://uwr1.de/kontakt

Developer Prerequesites
=======================
The project files are created with Android Studio 0.8.6 and tested with 0.8.9

Todo
====
+ Improve caching logic.
  + Make cache persistent.
  + Show old data, if no network connection is available.
    + Show note if data is older than some threshold.
  + Do not use forceReload all the time
+ Fix Text and icon colors in Holo and Holo.Light themes 
+ Add link to Einteilung (or implement it)
+ Push-Notifications (mit ja/nein)
+ Toasts erst zeigen, nachdem der Async call fertig ist.
+ x Std vorm Training nachfragen: hey, was is los?
+ Bei kurzfristiger Meldung: Option Luk/Geza/Hannes anzurufen/SMS/App Notification zu schreiben.
+ Bei kurzfristiger Meldung: Option Luk/Geza/Hannes anzurufen/SMS zu schreiben.
+ Add notice if no valid data is available (e.g. data expired and no network connection)
+ Add Badbild (PHOTO_[THUMB_]URL, replace ${location}, temp replace path in JSON pic.thumb/full)
+ Große Datenmengen (z.B. Badbilder) nur bei aktivem WiFi runterladen (uses-permission android.permission.ACCESS_WIFI_STATE)
+ Toasts abwechslungsreich machen
+ Tilman: Fahrplanung, Statistik-Tool
+ Nichtssagend-Liste
  + (add comment field to dialog)

Acknowledgements
================
The app uses the android support libraries v4 and v7 by Google. They are licensed under Apache License 2.0

The app uses the Support PreferenceFragment library by machinarius. It is licensed under Apache License 2.0

The app uses the Action Bar Icon Pack. It is licensed under Creative Commons Attribution 2.5 license.

The launcher icon uses the Android robot.
The Android robot is reproduced or modified from work created and shared by Google and used according to terms described in the Creative Commons 3.0 Attribution License.
