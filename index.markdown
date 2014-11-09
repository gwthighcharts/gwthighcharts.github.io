---
layout: index
title: Highcharts4gwt
---

<div class="jumbotron">
  <h1>Highcharts wrapper for GWT</h1>
  <h2>An always "up to date" GWT wrapper for highcharts</h2>
</div>

<div class="major-links">
    <a href="{{site.github_page}}"><i class="fa fa-github"></i><span >Fork {{site.project_name}} !</span></a>
</div>

[![Build Status](https://travis-ci.org/highcharts4gwt/highcharts4gwt.svg?branch=master)](https://travis-ci.org/highcharts4gwt/highcharts4gwt) [![Coverage Status](https://coveralls.io/repos/highcharts4gwt/highcharts4gwt/badge.png)](https://coveralls.io/r/highcharts4gwt/highcharts4gwt)

To know more about Highcharts please have a look to [the official web page](http://www.highcharts.com/products/highcharts)


##How can it be always up to date ? 

This wrapper is generated using the JSON file that describes highcharts options. This is the same file that is used by highcharts to generate its documentation. We parse this file, then we generate the JSNI code for getter and setters method.

##What does it look like in GWT ?

The goal was to write an API that was as close as possible to the JavaScript API so that by reading any example in JavaScript it would be easy to write it in GWT. To do that we use a fluent API.

##Why not using moxie wrapper ?

I have used moxie wrapper both for personal and professional projects. It works fine. Thanks a lot to them, it saved me lots of time ! But their wrapper does not seemed to be maintained anymore, plus I disagree with some of their design choices.

To Knowles more about [Moxiegroup](http://www.moxiegroup.com/) and their highcharts wrapper [http://www.moxiegroup.com/moxieapps/gwt-highcharts/](http://www.moxiegroup.com/moxieapps/gwt-highcharts/), have a look to the sources of that project that can be found on [sourceforge](http://sourceforge.net/projects/gwt-highcharts/) 


## Status
v0 still in development.

Go to [Highcharts wrapper](https://github.com/highcharts4gwt/highcharts) to test the wrapper !

I created a new project "highcharts" were I put all the chart options. It is cleaner so that the chart options are not mixed with the generator code. You can use that project to test the api in your gwt project. 

See the project readme for more info on how to use it.


