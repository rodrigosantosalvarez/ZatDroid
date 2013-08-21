ZatDroid
========

ZatDroid: Satellite Tracking &amp; Augmented Reality App for Android

Report: https://dl.dropboxusercontent.com/u/59011997/_ZalDroid_Report.pdf

TechnicalManual: https://dl.dropboxusercontent.com/u/59011997/_ZatDroid_TechnicalManual.pdf

UserManual: https://dl.dropboxusercontent.com/u/59011997/_ZatDroid_UserManual.pdf

The purpose of ZATDROID is to offer the user the possibility of tracking any artificial satellite. It locates it in Google Maps together with its predicted trajectory and also it allows the user to see it in real time in the sky with augmented reality camera view. The application is implemented in Java for ANDROID devices (tablets or smartphones).

Orbital mechanics calculations are developed following Newton equations and NORAD (North American Aerospace Defence Command) propagation models, firstly published in 1980 Spacetrack Report #3: Models for Propagation of the NORAD Element Sets

ZATDROID downloads information from a data base of satellites provided by CELESTRAK.COM, does the orbital mechanics calculations (NORAD models), gets the device sensors magnitudes, connects to the web service Google Maps Elevation to get the altitude of the user location, processes data in terms of XML language, creates a GOOGLE MAPS views with the updated position in real time of the satellite picked and shows the position in the sky in augmented reality using OPENGL for the camera view.

The GUI (Graphical User Interface) manages to lead the users through an easy and friendly navigation to achieve their aims quickly, showing the results of the user picks with BreadCrumbs, supporting English and Spanish, showing icon-based menus and keeping the users informed of the longer processes by “progress bars”.

