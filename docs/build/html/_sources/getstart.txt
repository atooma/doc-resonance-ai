.. _getstart:

Getting Started
=======================================

This section provides a tutorial on how to create a Resonance AI powered application from scratch.

As a first step, it’s essential to create a user account allowing to add new projects. This requires to open URL https://console.resonance-ai.com and fill the form reported in screenshot below:

.. figure:: _static/img/console1.jpg
   :width: 600 px
   :alt: Resonance console
   :align: center

Once your account is ready, login into web console and use add project button for starting creation wizard.

*   Declaring features of interest - This is a mandatory step and obviously depends on project itself.
*   Configuring data sources - According to choices made at step 1, a set of data sources is automatically selected by Resonance platform. User can apply changes to such configuration (typically by removing wearables and external systems that are not of interest), but with some restrictions, since making too many changes may have impact on effectiveness of selected features.
*   Configuring rule engine [ optional ] - First two steps allow to exploit Resonance Context API and Info API. In this phase it’s possible to declare whether project requires IF-DO smart actions to be executed in specific contexts.
*   Next sections describe more in depth each of the steps above.

Declaring Features of Interest
--------------------------------------

Screenshot below shows how to declare features of interest. In order to simplify this process, a set of Predefined Packs is provided. Each pack includes a subset of Context API and Info API functions.

More advanced users can directly select functions of interest, ignoring Predefined Packs panel.

.. figure:: _static/img/console2.jpg
   :width: 600 px
   :alt: Resonance console
   :align: center

In addition to functions, user is also requested to select mobile platform targets. This is extremely important because mobile devices are used not only for running applications but also for collecting data. Moreover some functions relies massively on mobile platform data, so their absence may have impact on functions effectiveness (e.g. location based functionalities relying on GPS data).

Data Sources Definition
--------------------------------------

Defining data sources is a complex activity. Resonance platform simplifies this process providing a pre-selection on all devices and external systems that can effectively contribute to implement functionalities declared at previous step.

User can decide to remove some data sources, but some of them cannot be excluded. That’s because they have an essential role in the implementation of the functionalities of interest.

.. figure:: _static/img/console3.jpg
   :width: 600 px
   :alt: Resonance console
   :align: center

Rule Engine Configuration
--------------------------------------

Once functionalities and data sources have been selected, user is requested to decide whether to enable Rule Engine (this can be done at any time later on).

.. figure:: _static/img/console4.jpg
   :width: 600 px
   :alt: Resonance console
   :align: center

Enabling Rule Engine requires also to define which are the modules of interest. By default Resonance automatically selects all modules related to devices and systems selected in data sources definition step.

.. figure:: _static/img/console5.jpg
   :width: 600 px
   :alt: Resonance console
   :align: center

Once configuration is completed, console shows a summary of all settings with details on how to configure your mobile and web applications for exploiting all features.

.. figure:: _static/img/console6.jpg
   :width: 600 px
   :alt: Resonance console
   :align: center

Now you have the API_KEY that must be used with the SDKs.

 
