# CUBA JavaMelody monitoring integration demo

## Abstract
It is a demo application that uses [cuba-jm](https://github.com/cuba-platform/cuba-jm)
application component to enable JavaMelody monitoring.

## Settings used

JavaMelody monitoring configuration:
1. `cubajm.monitoringUrl`: `/cm/` (Middleware), `/wm/`(Web client)
2. `cubajm.authorizedUserLogin`: `demo`
3. `cubajm.authorizedUserPassword`: `demo`

You can change these settings in `app.properties` & `web-app.properties`
files.

## Usage

To open monitoring dashboards use the following URLs:
1. [http://localhost:8080/app-core/cm/](http://localhost:8080/app-core/cm/) -
middleware monitoring dashboard
2. [http://localhost:8080/app/wm/](http://localhost:8080/app/wm/) -
web client monitoring dashboard