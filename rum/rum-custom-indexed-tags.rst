:orphan:

.. _rum-custom-indexed-tags:

**********************************************************************
Filter and troubleshoot with custom tags 
**********************************************************************


.. meta::
   :description: words


Create custom tags to improve filtering and troubleshooting capabilities in Tag Spotlight. First, create a custom span tag, then index it by adding a MetricSet to the span tag. Adding a MetricSet to the span tags lets you use all of the features associated with indexed span tags. See, :ref:`apm-index-span-tags`. 

Track custom processes 
=================================


Adding your own tags that are meaningful to your organization like custom tags, helps you refine results and glean insights most pertinent to you. Custom span tags are especially useful for tracking processes that are unique to your organization. For example, customer support, tier, department, or internal geo locations for facilities.  



 ..
   "How can I add my own tags to Tag Spotlight?", "How can I filter on custom tags?" "How can I troubleshoot with custom tags?


Avoid high cardinality in MetricSets
=============================================
Choose tags with a reasonable amount of cardinality. Tags like userID, or sessionID are inefficient choices because there could be a huge number of users in your organization and visitors to your application, so creating a troubleshooting MetricSet for each userID is not optimal for performance. For high cardinality ID based tags full-fidelity session search is a better option. High cardinality MetricSets can also affect your org limits :ref:`rum-limits`. Limits are determined by your subscription: enterprise and standard. For more information on each type of subscription, see :new-page:`Splunk RUM Pricing <https://www.splunk.com/en_us/products/pricing/faqs/observability.html#splunk-rum>`.


Default tags
==============

The following tags are automatically indexed during ingestion by default depending on the metric:

       * url name
       * operation
       * HTTP Method and status code
       * custom event name
       * browser and version
       * OS name and version
       * city, region, country


Add custom tags to Tag Spotlight
========================================================

Follow these steps to add custom tags to Tag Spotlight 

1. Add a span tag following these steps: :ref:`create-a-span-rum`.

2. In Splunk RUM, select :strong:`RUM MetricSet`. 

.. image:: /_images/rum/rum-metricset.png
      :width: 20%
      :alt: Settings panel for adding metric sets. 


3. Select :strong:`Add MetricSet` and confirm with the checkmark. 


