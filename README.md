# Events

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](#)

Events is a cloud-enabled, mobile-ready, online-storage recommendation web APP on Java EE.
# BackEnd
  - Created JavaServlets with RESTful APIs to Handle HTTP requests and responses
  - Dual DataBaeses (MySQL, MongoDB) to capture real data from TicketMaster API and store user data
  - Desinged an algorithm to handle recommendation
# FrontEnd
  - Designed  the web page with AJAX, HTML, CSS, and Javascript 
# Features
  - Show nearby events
  - Provide events you might like
  - Login / Logout feature

# Show events!
**Login**
[![login](https://user-images.githubusercontent.com/33920615/48434995-4de0b100-e749-11e8-9418-0323b1d7c75d.png)](#)
**Some events around you will pop up when you visit the index page!**
[![events](https://user-images.githubusercontent.com/33920615/48434996-4de0b100-e749-11e8-82b0-77c00c8800d3.png)](#)
> *Your location is based on your GeoIP, for demo use only and no further use.

# Make favorite
**You can simply click the HEART icon, the system would record this**
[![favorite](https://user-images.githubusercontent.com/33920615/48434997-4de0b100-e749-11e8-9ee4-8d29216e2e18.png)](#)

# Show Recommendation
**When you pick some of your favorite items, click "Recommendation" to see events you may like!**
[![recommendation](https://user-images.githubusercontent.com/33920615/48434998-4de0b100-e749-11e8-9ce5-f8c3d4894835.png)](#)
**The more items you set as favorite, the more accuracy for us to give choose events for you**

## Insights

  - We use TicketMaster API to gather events, based on your geoIP location.
  - All events you viewed are stored in the backend database(MySQL & MongoDB supported), along with login info and favorite info.
  - We have an algorithm to determine what kind of events to recommend based on personal favorite items' categories, view history and other users' favorites, etc.
