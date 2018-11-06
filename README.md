# Events

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](#)

Events is a cloud-enabled, mobile-ready, online-storage recommendation web APP on Java EE.

  - Show nearby events
  - Provide events you might like
  - Login feature

# Show events!

**Some events around you will pop up when you visit the index page!**
[![events](https://user-images.githubusercontent.com/33920615/48034279-b8cc2f80-e12c-11e8-9aab-230e32d0338e.jpeg)](#)
> *Your location is based on your GeoIP, for demo use only and no furthur use.

# Make favorite
**You can simply click the HEART icon, the system would record this**
[![favorite](https://user-images.githubusercontent.com/33920615/48034474-8a9b1f80-e12d-11e8-9787-8ba7c4cd449f.jpeg)](#)

# Show Recommendation
**When you pick some of your favorite items, click "Recommendation" to see events you may like!**
[![recommendation](https://user-images.githubusercontent.com/33920615/48034534-cdf58e00-e12d-11e8-8fc4-dbb86d6fdb4a.jpeg)](#)
**The more items you set as favorite, the more accuracy for us to give choose events for you**


## Insights
  -We use TicketMaster API to gather events, based on your geoIP location.
  -All events you viewed are stored in the backend database(MySQL & MongoDB supported), along with login info and favorite info.
  -We have an algorithm to determine what kind of events to recommend based on personal favorite items' catagories, view history and other users' favorites, etc.
