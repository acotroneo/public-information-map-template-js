# public-information-map-template-js

![App](http://esri.github.io/public-information-map-template-js/images/item.png)

This is a fully configurable public facing mapping application that highlights areas through authoritative data feeds and social content, allowing the public to tell a story.

[View it live](http://esri.github.io/public-information-map-template-js/)

The template can be configured using the following options:

- **Map:** Choose the web map to use in your application.
- **Interactive:** Map Notes: An author can describe areas on the map using a map notes layer.
- **Responsive:** A side drawer is shown when its size can be accommodated. The responsive drawer can be toggled on or off by the user and allows the application to be embedded into blogs and websites.
- **Navigation:** Home and Locate buttons add ease of map navigation.
- **Content:** Choose to display geo-located content from Flickr, Twitter, Instagram or Webcams.travel.
- **Summary:** Briefly describe your application in the "Area" panel.
- **Keywords:** Use query keywords to search on Flickr or Twitter.
- **Search:** Enable Searching for addresses and places.
- **Share:** Share this application through Twitter, Facebook, Google+ or generate HTML for embedding in a blog or website.
- **Basemap:** Enable toggling between two Esri basemaps.
- **Layers:** Toggle visibility of layers.
- **Legend:** Display a legend.
- **Bookmarks:** Webmap bookmarks can be used to navigate the map.
- **About:** Display information about the application. The dialog can also be set to open on startup.
- **Access and Use Constraints:** Display Access and Use Constraints for the webmap in a pop-up dialog when the map opens.

## Instructions

1. Download and unzip the .zip file or clone the repository.
2. Web-enable the directory.
3. Access the .html page.
4. Start writing your template!

[New to Github? Get started here.](https://github.com/)

## Deploying

1. To deploy this application, download the template from Portal/ArcGIS Online and unzip it.
2. Copy the unzipped folder containing the web app template files, such as index.html, to your web server. You can rename the folder to change the URL through which users will access the application. By default the URL to the app will be `http://<Your Web Server>/<app folder name>/index.html`
3. Change the sharing host, found in defaults.js inside the config folder for the application, to the sharing URL for ArcGIS Online or Portal. For ArcGIS Online users, keep the default value of www.arcgis.com or specify the name of your organization.
  - ArcGIS Online Example:  `"sharinghost": location.protocol + "//" + “<your organization name>.maps.arcgis.com`
  - Portal Example where `arcgis` is the name of the Web Adaptor: `"sharinghost": location.protocol + "//" + "webadaptor.domain.com/arcgis"`
4. If you are using Portal or a local install of the ArcGIS API for JavaScript, change all references to the ArcGIS API for JavaScript in index.html to refer to your local copy of the API. Search for the references containing `"//js.arcgis.com/3.14"` and replace this portion of the reference with the url to your local install.
  - For example: `"//webadaptor.domain.com/arcgis/jsapi/jsapi"` where `arcgis` is the name of your Web Adaptor.
5. Copy a map or group ID from Portal/ArcGIS Online and replace the default web map ID in the application’s index.html page. You can now run the application on your web server or customize the application further.

> **Note:** If your application edits features in a feature service, contains secure services or web maps that aren't shared publicly, or generate requests that exceed 200 characters, you may need to set up and use a proxy page. Common situations where you may exceed the URL length are using complex polygons as input to a task or specifying a spatial reference using well-known text (WKT). For details on installing and configuring a proxy page see [Using the proxy](https://developers.arcgis.com/javascript/jshelp/ags_proxy.html). If you do not have an Internet connection, you will need to access and deploy the ArcGIS API for JavaScript documentation from [developers.arcgis.com](https://developers.arcgis.com/).

## Requirements

* Notepad or HTML editor
* A little background with Javascript
* Experience with the [ArcGIS Javascript API](http://www.esri.com/) would help.

## Webfonts

This application uses a custom webfont created on [Fontello](http://fontello.com/). If you're hosting this application on your own server, make sure that it's configured to host the webfont files with the correct mime types. Some servers require a mime type set for these files to be able to serve them correctly. See the following URLs for more information. There is a zip archive of the webfont with it's fontello config in the "resources" folder in this repository.
- [IIS Mime types](http://codingstill.com/2013/01/set-mime-types-for-web-fonts-in-iis/)
- [Properly serve webfonts](http://blog.symbolset.com/properly-serve-webfonts)

## Resources

* [ArcGIS for JavaScript API Resource Center](http://help.arcgis.com/en/webapi/javascript/arcgis/index.html)
* [ArcGIS Blog](http://blogs.esri.com/esri/arcgis/)
* [twitter@esri](http://twitter.com/esri)

## Issues

Find a bug or want to request a new feature?  Please let us know by submitting an issue.

## Contributing

Anyone and everyone is welcome to contribute. :)

## Licensing
Copyright 2012 Esri

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

A copy of the license is available in the repository's [license.txt](https://raw.github.com/Esri/public-information-map-template-js/master/license.txt) file.

[](Esri Tags: ArcGIS ArcGIS Online Web Application Local Impact Map template Public)
[](Esri Language: JavaScript)
