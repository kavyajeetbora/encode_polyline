# Encode GIS Polyline to Google Encoded Polyline Algorithm Format

Simple web application to encode the standard linestring geometry objects to Google's Encoded Polyline Algorithm Format.

# Run the application on google colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](http://colab.research.google.com/your_notebook_path)

# About Encoded Polyline Algorithm Format

Polyline encoding is a lossy compression algorithm that allows you to store a series of coordinates as a single string. Point coordinates are encoded using signed values. If you only have a few static points, you may also wish to use the interactive polyline encoding utility.

[Read mode](https://developers.google.com/maps/documentation/utilities/polylinealgorithm)

# TODO

1. Apply filter to check all geometries are LineString object or not
2.

# Reference

1. [python library - polyline 2.0.2](https://pypi.org/project/polyline/)
