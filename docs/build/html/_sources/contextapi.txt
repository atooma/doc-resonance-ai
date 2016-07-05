.. contextapi:

Context API
==================

Context Detection is the core of Resonance AI and it’s based on the idea of determining what user is doing, by combining information coming from different data sources (e.g. Android / iOS devices, wearables, external systems) and processing them through advanced models developed for Google Tensorflow.

The Context API are organized in eight groups:

* Basic: this group gives information about the type of the movement of the user;
* Vehicle: this group gives information about the type of in-vehicles movement of the user;
* User Places: this group gives access to user's favorite locations;
* On Foot: this group knows if user does certain activities on foot;
* Entertainment: this group gives information about the type of leisure activities;
* Health
* Business
* Holidays

Basic API
------------

.. cssclass:: table-bordered

+------------------------+-------------------------------------------------+
| API                    | Description                                     |
+========================+=================================================+
| still                  | The user is still in a place.                   |
+------------------------+-------------------------------------------------+
| in_vehicle             | The user is moving by some type of vehicle      |
|                        | (car, bus, train, subway, flight);              |
+------------------------+-------------------------------------------------+
| on_foot                | The user is running or walking;                 |
+------------------------+-------------------------------------------------+
| biking                 | The user is biking                              |
+------------------------+-------------------------------------------------+

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up

Vehicle API
---------------

.. cssclass:: table-bordered

+------------------------+-------------------------------------------------+
| API                    | Description                                     |
+========================+=================================================+
| car                    | The user is driving a car;                      |
+------------------------+-------------------------------------------------+
| bus                    | The user is moving by bus;                      |
+------------------------+-------------------------------------------------+
| train                  | The user is traveling by train;                 |
+------------------------+-------------------------------------------------+
| subway                 | The user is traveling by metro;                 |
+------------------------+-------------------------------------------------+
| flight                 | The user is traveling by flight;                |
+------------------------+-------------------------------------------------+
| ferry                  | The user is traveling by ferry;                 |
+------------------------+-------------------------------------------------+

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up
* Samsung Connect Auto


User Places API
-------------------

This group gives information about the user places; the types implemented are:

* home
* work
* favorite_restaurant
* favorite_coffee
* favorite_shop
* favorite_gym

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up
* Nest
* Netatmo Thermostat
* Smartthings

On Foot API
--------------------

This category collects context like:

* walking
* running
* workout

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up


Entertainment API
-----------------

This category collects context like:

* shopping,
* restaurant,
* fast food,
* cinema,
* theater,
* stadium,
* opera,
* museum,
* aquarium,
* disco,
* pub,
* bar

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up


Health API
------------------

This category collects context like:

* sleeping,
* emotional status

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up

Business API
------------------

This category collects context like:

* meetings
* business trip
* working
* business lunch
* business dinner

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up
* Facebook
* Twitter
* LinkedIn

Holidays API
------------------

This category collects context like:

* Cultural trips
* Sea
* SPA
* Relax

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up
* Nest
* Netatmo Thermostat
* Smartthings
