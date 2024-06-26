.. _about-collector-configuration-tutorial:

*****************************************************************************************
Tutorial: Configure the Splunk Distribution of OpenTelemetry Collector on a Linux host
*****************************************************************************************

.. meta::
    :description: Follow this tutorial for a walkthrough of configuring the Splunk Distribution of OpenTelemetry Collector to collect telemetry in common situations.

.. toctree::
   :hidden:
   :maxdepth: 3

   collector-config-tutorial-start
   collector-config-tutorial-edit
   collector-config-tutorial-troubleshoot

The Splunk Distribution of OpenTelemetry Collector is a :new-page:`distribution <https://docs.splunk.com/Splexicon:Distribution>` of OpenTelemetry Collector that includes Collector components, installers, and default settings so that it's ready to work with Splunk Observability Cloud.

Follow this tutorial for a walkthrough of configuring the Splunk Distribution of OpenTelemetry Collector to collect telemetry in common situations, such as adding new receivers and processors, or setting up different export targets.

.. raw:: html

    <h2>What's in this tutorial</h2>

After completing this tutorial, you can accomplish the following tasks:

* Configure the Splunk Distribution of OpenTelemetry Collector.

* Add, remove, or configure Collector components.

* Troubleshoot common configuration issues.

.. raw:: html

    <h2>How to use this tutorial</h2>

Follow the tutorial parts in order:

1. Install the Collector and learn about the location and structure of the Collector configuration file. See :ref:`collector-config-tutorial-start`.

2. Edit the Collector configuration file to activate a new receiver and processor. See :ref:`collector-config-tutorial-edit`.

3. Troubleshoot common configuration issues. See :ref:`collector-config-tutorial-troubleshoot`.

.. raw:: html

    <h2>Prerequisites</h2>

To get the most out of this tutorial, you need a Linux operating system compatible with .deb packages and a code editor. The tutorial uses the Ubuntu package of the Splunk Distribution of OpenTelemetry Collector.

Additionally, you must have your Splunk Observability Cloud realm and access token to deploy the Splunk Distribution of OpenTelemetry Collector. For more information, see :ref:`admin-org-tokens`.

.. raw:: html

    <h2> Get started </h3>

To get started with the tutorial, see :ref:`collector-config-tutorial-start`.
