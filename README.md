# esri-amd-samples-js

## AMD-Style Samples of Esri's ArcGIS API for JavaScript

The purpose of this project is to show modified versions of Esri's [ArcGIS API for JavaScript](http://developers.arcgis.com/en/javascript/) [sample pages](http://developers.arcgis.com/en/javascript/jssamples/) that use [Dojo's AMD-style loading](http://help.arcgis.com/en/webapi/javascript/arcgis/jshelp/inside_dojo_amd.html) instead of the pre-AMD dojo.require syntax.

The intended audience is ArcGIS developers that are either just getting started with AMD, or who might be struggling to adapt a particular sample to work in their AMD project.

[View it live](http://tomwayson.github.io/esri-amd-samples-js/)

This project does not aim to convert every sample page to AMD. I only convert samples to AMD when I need to incorporate them into my own projects.

The samples in this project do not presume to show the "right" way to implement an AMD solution to a given problem. Only the minimal amount of code needed to convert the sample to AMD is added/updated. Whenever possible, the original code is commented out instead of replaced.

For a comprehensive open source example that covers most of the common mapping operations (basemap, geocoding, etc) using the ArcGIS API for JavaScript with AMD, I recommend that you check out Allan Laframboise's excellent Quick Start Map guide:
- [Repository](https://github.com/alaframboise/quickstart-map-js)
- [Live samples](http://esri.github.com/quickstart-map-js/index.html)

## Contributing

Anyone and everyone is welcome to contribute. The next time you find yourself converting one of the sample pages to AMD, I encourage you to share it here!

## Licensing

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](https://raw.github.com/Esri/dojo-bootstrap-ui-for-maps-js/master/license.txt) file.
