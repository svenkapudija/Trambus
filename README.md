Trambus
=======

Public transportation app for city of Zagreb (and raw data route/stop data for Osijek). Although it's currently only for city of Zagreb, it can be used with slight modifications for any city.

##Route/stop data

Zagreb data is in `JSON` format while Osijek data is in CSV format (separated with `;`).

###Accurracy?

Osijek coordinates are collected via Android mobile phone (and it's GPS) while riding on the mountain bike.

Zagreb coordinates are collected from various sources - some of which were already available online, some are hand-picked manually from Google Maps (Earth & Street View) and some are also collcted via Android mobile phone while riding in public transport.

Zagreb route info is manually parsed (including timetables) from official [ZET page](http://zet.hr/) timetables and maps. Of course, most of the timetables are (probably) outdated.

###Why are there multiple coordinates for the same stop (Zagreb)?

Usually for every bus/tram stop there are `two coordinates` - for every side of the road (for every direction) one. However, in some cases you will find `four or more coordinates` for the same stop because it's on intersection/square/etc.

##Where is the app?

App consists of three parts - client side Android, server side PHP and Neo4j graph database (Java).
It's a total mess right now so it will take some time to organize it in order to put it here online.

Stay tuned...
