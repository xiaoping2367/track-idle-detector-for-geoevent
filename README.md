# track-idle-detector-for-geoevent

ArcGIS GeoEvent Processor Sample Track Idle Detector.

![App](TrackIdle.png?raw=true)

## Features
* Detects whether an event has moved and caches the last known location and timestamp for a new or moved event.
* Allow user to define a distance tolerance and a idle time threshold.
* Idle report can be generated in a continuous mode or in onChange mode.
* Works with GeoEvent Processor 10.2.x

## Instructions

Building the source code:

1. Make sure Maven and ArcGIS GeoEvent Processor SDK are installed on your machine.
2. Run 'mvn install -Dcontact.address=[YourContactEmailAddress]'

Installing the built jar files:

1. Copy the *.jar files under the 'target' sub-folder(s) into the [ArcGIS-GeoEvent-Processor-Install-Directory]/deploy folder.

## Requirements

* ArcGIS GeoEvent Processor for Server.
* ArcGIS GeoEvent Processor SDK.
* Java JDK 1.7 or greater.
* Maven.

## Resources

* [Download the connector's tutorial](http://www.arcgis.com/home/item.html?id=041138094e5348eb902f4b71175eeb6f) from the ArcGIS GeoEvent Processor Gallery
* [ArcGIS GeoEvent Processor for Server Resource Center](http://pro.arcgis.com/share/geoevent-processor/)
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis/)
* [twitter@esri](http://twitter.com/esri)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Esri welcomes contributions from anyone and everyone. Please see our [guidelines for contributing](https://github.com/esri/contributing).

## Licensing
Copyright 2013 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](license.txt?raw=true) file.

[](ArcGIS, GeoEvent, Processor)
[](Esri Tags: ArcGIS GeoEvent Processor for Server)
[](Esri Language: Java)