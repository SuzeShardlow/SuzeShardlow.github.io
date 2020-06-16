---
layout: coding_project
name: Boris Bikes
sub_headline: A little JavaScript app I built in one evening using the TfL and Google Maps APIs.
github: boris-bikes
live_app:
image: /images/coding_projects/boris_bikes/boris_bikes.jpg
comments: true
---

A map showing the locations of the Boris Bike (officially called Santander Cycle) stations. Data is pulled from the Transport for London (TfL) API and shown on a map using the Google Maps API.

[Try it out!](http://suze.dev/boris_bikes)

[View code](https://github.com/SuzeShardlow/boris_bikes)

I created a web page showing a Google Map and then replaced the custom Google Maps markers to show Boris Johnson's head on the map at the location of each Boris Bike docking station.

His head shows in full colour if there is more than one bike at the docking station, or in black and white if there are 0 or 1 bikes at the docking station (thus saving the user a wasted journey).

When each head is clicked, an info window showing the name of each docking station, the number of available bikes and the number of spaces appears.
