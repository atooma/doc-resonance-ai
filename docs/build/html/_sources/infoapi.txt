.. infoapi:

Info API
====================

Resonance AI implements a set of functions, allowing to get specific information about users and their attitudes.

Below are reported some example of questions that Resonance AI is able to answer to developers:

Which are user Home / Work locations?
Where user parked his car?
User is driving. Which is his most probable destination?
Which are user favorite restaurants?
What is important to highlight is that information comes from data analysis on backend and doesn’t require a direct user input (in case feedbacks can be used for adjusting results).

The Info APIs are collected in the following categories:

* User Basic Habits
* Vehicle
* Suggestions
* Weather
* Traffic
* Fitness
* Shopping Habits
* RAW data

User Basic Habits
---------------------

.. cssclass:: table-bordered

+------------------------+-------------------------------------------------+
| API                    | Description                                     |
+========================+=================================================+
| wake_up_time           | time when the user wakes up;                    |
+------------------------+-------------------------------------------------+
| slip_time              | time when the user goes to sleep;               |
+------------------------+-------------------------------------------------+
| to_work                | time when the user leaves home to go at work;   |
+------------------------+-------------------------------------------------+
| to_home                | time when the user leaves work to go at home;   |
+------------------------+-------------------------------------------------+
| restaurant_day         | day of the week when the user goes to restaurant|
+------------------------+-------------------------------------------------+
| cinema_day             | day of the week when the user goes to cinema    |
+------------------------+-------------------------------------------------+

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up

Vehicle
---------------------

.. cssclass:: table-bordered

+------------------------+-------------------------------------------------+
| API                    | Description                                     |
+========================+=================================================+
| trip_destination       | predicted destination of the trip;              |
+------------------------+-------------------------------------------------+
| car_location           | GPS position of the car;                        |
+------------------------+-------------------------------------------------+
| car_status             | alert and error status of the car;              |
+------------------------+-------------------------------------------------+
| legal_trip_percentage  | percentage of the time under speed limit;       |
+------------------------+-------------------------------------------------+
| fuel_station_near_by   | list of fuel statation;                         |
+------------------------+-------------------------------------------------+

The devices used to estimate these informations are:

* Android/iOS
* Samsung Connect Auto
* TEXA OBD
* Octo OBD
* Automatic
* VIASAT

Suggestions
---------------------

Resonance AI provides a series of messages for the user to suggest actions.

.. cssclass:: table-bordered

+------------------------+-------------------------------------------------+
| Message type           | Description                                     |
+========================+=================================================+
| vehicle_suggestion     | tricks about the car (oil control, ...);        |
+------------------------+-------------------------------------------------+
| home_suggestion        | tricks about home (home temperature, ...);      |
+------------------------+-------------------------------------------------+
| path_suggestion        | path to go at work or at meetings;              |
+------------------------+-------------------------------------------------+

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up
* Samsung Connect Auto
* TEXA OBD
* Octo OBD
* Automatic
* VIASAT
* Nest
* Netatmo Thermostat
* Smartthings

Weather
---------------------

.. cssclass:: table-bordered

+------------------------+-------------------------------------------------+
| API                    | Description                                     |
+========================+=================================================+
| temperature            | temperature of the city;                        |
+------------------------+-------------------------------------------------+
| weather_type           | weather condition;                              |
+------------------------+-------------------------------------------------+
| forecast_weather_1d    | weather forecast for tomorrow;                  |
+------------------------+-------------------------------------------------+
| forecast_weather_2d    | weather forecast for two day;                   |
+------------------------+-------------------------------------------------+
| forecast_weather_3d    | weather forecast for three day;                 |
+------------------------+-------------------------------------------------+


The devices used to estimate these informations are:

* Android/iOS


Traffic
---------------------

.. cssclass:: table-bordered

+------------------------+-------------------------------------------------+
| API                    | Description                                     |
+========================+=================================================+
| traffic_status         | traffic status of the streets nearby;           |
+------------------------+-------------------------------------------------+
| forecast_traffic       | forecast of the traffic status                  |
+------------------------+-------------------------------------------------+

The devices used to estimate these informations are:

* Android/iOS



Fitness
---------------------

.. cssclass:: table-bordered

+------------------------+-------------------------------------------------+
| API                    | Description                                     |
+========================+=================================================+
| time_at_fitness        | number of hours of fitness;                     |
+------------------------+-------------------------------------------------+
| heart_rate_min         | heart rate at resting state                     |
+------------------------+-------------------------------------------------+

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up


Shopping Habits
---------------------

.. cssclass:: table-bordered

+------------------------+-------------------------------------------------+
| API                    | Description                                     |
+========================+=================================================+
| favorite_shop          | the favorite shop of the user                   |
+------------------------+-------------------------------------------------+
| time_at_shopping       | time that user do shopping                      |
+------------------------+-------------------------------------------------+
| shopping_time          | time when user goes to shopping                 |
+------------------------+-------------------------------------------------+

The devices used to estimate these informations are:

* Android/iOS
* Fitbit
* Jawbone Up
