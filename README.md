TrainingApp
===========

Play Store Link
===============
The app is also available in Google's [Play Store](https://play.google.com/store/apps/details?id=de.uwr1.training).

Todo
====
+ Add link to Einteilung (or implement it)
+ x Std vorm Training nachfragen: hey, was is los?
+ Improve caching logic.
++ Make cache persistent.
++ Show old data, if no network connection is available.
++ Show note, if data is older than some threshold.
+ Add notice if no valid data is available (e.g. data expired and no network connection)
+ Add Badbild (PHOTO_[THUMB_]URL, replace ${location}, temp replace path in JSON pic.thumb/full)
+ Gro�e Datenmengen (z.B. Badbilder) nur bei aktivem WiFi runterladen (uses-permission android.permission.ACCESS_WIFI_STATE)
+ Add Nichtsgesagt list / load all-players JSON / an-/abmelden von anderen
+ Push-Notifications (mit ja/nein)
+ Toasts abwechslungsreich machen
+ Toasts erst zeigen, nachdem der Async call fertig ist.
+ Tilman: Fahrplanung, Statistik-Tool
+ Add version auto-increment

Acknowledgements
================
The app uses the android support libraries v4 and v7 by Google. They are licensed under Apache License 2.0

The app uses the Support PreferenceFragment library by machinarius. It is licensed under Apache License 2.0

The launcher icon uses the Android robot.
The Android robot is reproduced or modified from work created and shared by Google and used according to terms described in the Creative Commons 3.0 Attribution License.
