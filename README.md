# lakehouse
Scripts to monitor the in-law's lakehouse

mkrrd
=====

Simple script to create an RRD file for logging temps.

monitor
=======

Take a photo with the camera on the raspberry pi, then gather temp and humidity info from the Ambient Weather WS-1400-IP weather station.

pin
===

Small shell script to ease interaction with raspi GPIO pins

temp1wire
=========

Monitor temps on any installed 1-wire sensors (DS18B20) and the CPU

tstat
=====

Ultra primitive thermostat written in bash

noisetoggle
===========

A way to toggle the verbosity (to STDERR) of a long-running/looping script via SIGUSR1

suntimes
========

Get sunrise and sunset times via API call. Used by the "monitor" script to know when to start and stop taking photos.

temp1wire
=========

Testing out some concepts and different approaches with a USB webcam and 1-wire temp sensors.

uptemp
======

An actually functional but still ugly and primitive thermostat in bash.
