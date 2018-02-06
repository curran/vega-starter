# vega-starter
Starting point for using Vega.

Exported from [Datavis.tech: Temperature in Different Cities Area Charts](https://datavis.tech/vis/5a391ee51b1043c5ac7c8cb1fd0249e7).

## The Visualization

Small multiples area chart showing temperature across different cities for one week in 2015.

Draws from

 * [News Source by Age Grouped Bar Chart](https://datavis.tech/vis/796c3e7fc116452d952ffe78004d8a0b) for Vega-Lite setup.
 * [Vega-Lite: Trellis Area Example](https://vega.github.io/vega-lite/examples/trellis_area.html)

Also related - [Vega-Lite GitHub Issue: Specify Label Width for Facet](https://github.com/vega/vega-lite/issues/3195)

## The Data

A week of rich sensor data collected by the "Sense Your City" project.

Contains:

 * Hourly readings for one week
 * Different cities: San Francisco, Bangalore, Boston, Geneva, Rio de Janeiro, Shanghai, Singapore
 * Various mertics from sensors: temperature, light, air quality, sound, humidity, dust

The data was collected from the (now defunct) [Data Canvas - Sense Your City Project](http://grayarea.org/initiative/data-canvas-sense-your-city/). The data was filtered using the data processing script found in [GitHub: curran/data/senseYourCity](https://github.com/curran/data/tree/gh-pages/senseYourCity).
