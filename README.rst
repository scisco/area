geojson-area
============

.. image:: https://travis-ci.org/scisco/boolean.svg?branch=develop
    :target: https://travis-ci.org/scisco/boolean

.. image:: https://badge.fury.io/py/boolean.svg
    :target: http://badge.fury.io/py/boolean

.. image:: https://img.shields.io/pypi/l/boolean.svg
    :target: https://pypi.python.org/pypi/boolean/
    :alt: License


Calculate the area inside of any `GeoJSON <http://geojson.org/>`_ geometry. This is a port of Mapbox's `geojson-area <https://github.com/mapbox/geojson-area>`_ for Python.

Installation
------------

.. code::

  $ pip install area

Usage
-----

.. code::

  >>> from area import area
  >>> obj = {'type':'Polygon','coordinates':[[[-180,-90],[-180,90],[180,90],[180,-90],[-180,-90]]]}
  >>> area(obj)
  511207893395811.06


Credit
------

- `geojson-area <https://github.com/mapbox/geojson-area>`_
