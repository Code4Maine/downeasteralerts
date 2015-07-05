downeasteralerts/feeds
 Hosts different approaches for parsing the feed from Amtrak's [official train location map](http://www.amtrak.com/train-routes).  The maps feed displays locations for every train in the country by default, so to track the location of a single train like the Downeaster, various parsing methods will need to be deployed.

 downeasteralerts/feeds/Feed Parsing/Amtrak API Tutorial is copied from an excellent step-by step tutorial at- http://cheesehead-techblog.blogspot.com/2013/12/amtrak-real-time-train-data.html

 downeasteralerts/feeds/Feed Parsing/DEGTFSfeedsample- provides a sample of the unfiltered Downeaster Feed as it appears in the MapsEngine API

downeasteralerts/feeds/NodeRED contains files used to create a NodeRED "node" that parses the Amtrak location feed and translates into an MQTT message which can be interpreted by the [Owntracks](http://owntracks.org/) application.  Original Files should be credited to User [Ed Vielmetti](https://plus.google.com/u/0/+EdwardVielmetti/posts) per this discussion on the NodeRED forum- https://groups.google.com/d/topic/node-red/nQLi3zO3-mQ/discussion
