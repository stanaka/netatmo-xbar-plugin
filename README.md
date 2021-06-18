# A xbar plugin for Netatmo Weather Station

This [xbar](https://xbarapp.com/) plugin shows information sent from [Netatmo Weather Station](https://www.netatmo.com/en-us/weather/weatherstation).

![](https://raw.githubusercontent.com/stanaka/netatmo-xbar-plugin/main/netatmo-xbar-plugin.png)

## Install

This plugin depends on [golang](https://golang.org/) and [gorun](https://github.com/erning/gorun), so please install both of them.

## Configuration

<img src="https://github.com/stanaka/netatmo-xbar-plugin/blob/main/netatmo-xbar-plugin-configuration.png?raw=true" width=500>

Following tokens are necessary to fetch data from Netatmo server.
* Client ID
* Client Secret
* Refresh Token

You need to [create an app](https://dev.netatmo.com/apps/createanapp#form) to get Client ID and Client Secret.
To get Refresh Token is necessary to go through Authorization code grant process or Client credentials grant in this [document](https://dev.netatmo.com/apidocumentation/oauth)
