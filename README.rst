Network Pipeline Datasets
=========================

This repository holds csv datasets from captured network traffic during ZAP scans on web applications. I hope these datasets can help you build, train and tune defensive machine learning models to defend your applications.

I generated these datasets with the `Network Pipeline`_ capture framework. With the capture framework running, I ran the `ZAP simulations`_ and targeted a web application.

.. image:: https://www.owasp.org/images/1/11/Zap128x128.png
    :align: center

I have only had time to capture an attack on a vanilla `Django 2.0`_ application server running on Ubuntu 17.10.

.. _Network Pipeline: https://github.com/jay-johnson/network-pipeline
.. _ZAP simulations: https://github.com/jay-johnson/network-pipeline/tree/master/simulations#network-traffic-simulations
.. _Django 2.0: https://github.com/jay-johnson/network-pipeline/tree/master/simulations#django-2.0
