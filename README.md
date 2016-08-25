# Data validation ideas

Ideas for (automated) data validation during a software project. This was inspired by a talk by Arnuf Christl [Software comes and goes. Mind the Data!](https://streaming.media.ccc.de/foss4g-2016/relive/1060/)

## Problem

### Scenario
Lets say you are building a data visualization application. However the data for the visualization is created by a number of analysis steps. Starting with Shapefiles, perhaps using some excel files all processed to create a final output. This output might even go through several iterations. At the end of the process the data may or may not be valid. Currently there are no tools (that we know of) that help validate the data against some rules.

## Some existing projects that might be relevant

* http://specs.frictionlessdata.io/data-packages/

