---
layout: default
title: Release notes | Highcharts4gwt
---

## 0.0.6 - 3 jun 2015

* Change naming of events. Drop the useless prefix. ChartAddSeriesEvent -> AddSeriesEvent
* Fix bug [issues/15](https://github.com/highcharts4gwt/highcharts4gwt/issues/15)

## 0.0.5 - 29 may 2015

* Support new series<xxx> options but looses type safety :(
* Fix bug [highcharts/issues/1](https://github.com/highcharts4gwt/highcharts/issues/1)

## 0.0.4 - 14 march 2015

* Capacity to add function ```setFunctionAsString(String fieldName, String functionAsString);```

## 0.0.3 - 7 march 2015

* Capacity to add any field using ```setFieldAsJsonObject(fieldName, fieldValueAsJsonObject)``` (example [TreeMap](http://data-dragon-766.appspot.com/#ChartPlace:TreeMapWithColumnAxis))
* Factories for injection (no dependency on JavascriptObject inside presenters) [issues/8](https://github.com/highcharts4gwt/highcharts4gwt/issues/8)


## 0.0.2 - 19th of January 2015

* Added : Basic support for Objects, accessible in event handlers. [issues/2](https://github.com/highcharts4gwt/highcharts4gwt/issues/2)
* Fixed : No access to Point/Chart/etc objects in event handlers (only series available for plotOptions events). [issues/6](https://github.com/highcharts4gwt/highcharts4gwt/issues/6)
* Fixed : Wrong inheritance implementation need to get rid of it (no inheritance between xAxis and yAxis for example).


## 0.0.1 - 27th of december 2014

* First available version

## Known issues (not exhaustive).
Feel free to add new ones if you find something. Help is appreciated.

* See [issues](https://github.com/highcharts4gwt/highcharts4gwt/issues)

