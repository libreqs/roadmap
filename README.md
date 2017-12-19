# LibreQS
LibreQS is an open source project building an ecosystem for managing time series data in a protected manner.
It contains several projects including a service for data storage, APIs to access this service and clients demonstrating how to use the API and making first applications possible.

The project is in an early prototyping phase and every open source developer is warmly welcomed.
We will organize and discuss the development roadmap under https://github.com/libreqs/roadmap .
Feel free to join the discussion, take part in the development or take eventually lead in any of the listed projects.

## Pitch // what is this about?
We are almost too late: Apple provides *Apple Health*, *Apple Watch*; Google is working on systems such as *Google Fit*, Fitbit provides several products such as *Fitbit Tracker* and *Fitbit Flex*.
There are dozens of other companies working on systems which can all be organized under the term *quantified self* and people seek out for products and solutions in this field.
Quantified self is under heavy competition regarding who will be in control of data.
Data is the new oil.
None of those participating in this data exploitation is in control of his or her data.
LibreQS aims to provide an ecosystem to lead software development in a direction in which each individual reclaims control over its data.
This will succeed if LibreQS can achieve the following:
* clarify what data control for the individual means
* clarify where data gets created
* describe processes which preserve properties such as ownership or control when data flows
* provide tools for developers to implement such processes

Eventually an ecosystem could evolve in which individuals collect data to quantify themselves without getting compromised to analysis of others.
Furthermore groups could aggregate their data and provide it pseudonymized to institutions such as universities or market analysts without compromising individual data (including possible creation of value for data providers).
Finally, it would result in an aware and resposible treatment of individual data.

## Projects
* **timed** is the name of a data storage service. This service will be the first version for our infrastructure to collect time series data and will include properties such as data protection, time series operations, anonymity, .. . Those properties will be illustrated extensively as soon as base functionality is provided. It is based on symfony4.
* **timed4j** will be the name for a java API with which *timed*-services can be accessed
* **pyTimed** will be the name for a python API with which *timed*-services can be accessed
* **aware** is a first android application supporting easy data creation.

### Timed
Url: https://github.com/libreqs/timed
Stack: server-side, API documentation
Language: php
Frameworks: symfony4, composer
Deployment: magallanes

### Timed4j
Url: https://github.com/libreqs/timed4j
Stack: middleend, server-side
Language: java
Frameworks: 

### pyTimed
Url: https://github.com/libreqs/pyTimed
Stack: middleend, server-side
Language: python
Frameworks: 

### Aware
Url: https://github.com/libreqs/aware
Stack: frontend
Language: java
Frameworks: android, grunt


