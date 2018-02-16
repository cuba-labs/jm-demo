# CUBA JavaMelody monitoring integration demo

## Abstract
It is a demo application that uses [cuba-jm](https://github.com/cuba-platform/cuba-jm)
application component to enable JavaMelody monitoring.

## Settings used

We configured JavaMelody monitoring settings in this project in the following way:
1. `cubajm.monitoringUrl`: `/cm/` for the middleware tier and `/wm/`
for the web client
2. `cubajm.authorizedUserLogin` & `cubajm.authorizedUserPassword` are
`demo`, `demo` for both tiers

You can change these settings in `app.properties` & `web-app.properties`
files.

## Usage

To open monitoring dashboards use the following URLs:
1. [http://localhost:8080/app-core/cm/](http://localhost:8080/app-core/cm/) -
monitoring dashboard for the middleware tier
2. [http://localhost:8080/app/wm/](http://localhost:8080/app/wm/) -
monitoring dashboard for the web client