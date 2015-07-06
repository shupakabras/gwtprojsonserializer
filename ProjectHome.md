**News:** now GWTProJSONSerializer has support for GWT 2.2

GWT Professional JSON Serializer is a free, open source library that allows you to serialize any JSON text into a java object (and reverse). It is crucial functionality when there is no GWT-RPC on server side. This JSON serializer allows easy connecting GWT client side to any standard server side technology.

All Java classes in your project which are marked just by implementing JsonSerializable interface are put into JSON serialization context.

Thanks to gwtjsonserializer project and gwtapps on which this project based on.

# Maven #
The project has now its own Maven [googlecode repository](http://gwtprojsonserializer.googlecode.com/svn/repo/)

See the dedicated wiki page http://code.google.com/p/gwtprojsonserializer/wiki/GettingStartedOnMaven2 for more information.

# Support #
The project support the last GWT 2.0+ version.

**Remark**: due to the last evolution of GWT, Google has decided that GWT 2.2 should break backwards compatibility, thus the lastest version of GWTProJSONSerializer will not work with GWT anterior to 2.2. Please use:
  * GWTProJSONSerializer-1.0.3 for GWT <= 2.1
  * GWTProJSONSerializer-1.0.4 for GWT >= 2.2.

# Tutorial #
Quick getting started tutorial: http://code.google.com/p/gwtprojsonserializer/wiki/GettingStarted