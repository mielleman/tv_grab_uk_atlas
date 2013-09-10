tv_grab_uk_atlas
----------------

Fetch TV and radio programme listings from "Atlas" data store and reformat into XMLTV format.


JUSTIFICATION
-------------

Most people in the UK use the excellent Radio Times ".dat" file feed to obtain TV and radio programme schedules for their PVR or Listings Viewer.

The Radio Times service was taken over by Metabroadcast in January 2012 who continue to provide the feed.  However Metabroadcast have stated it is their intention to terminate the .dat feed at some point.  Further they are no longer actively maintaining this feed and have publicly stated they will not be adding any new channels to it.  So as new channels become available, there is no schedule info available for them.  

At the time of writing (Sep. 2013) an increasing number of channels are not available in the .dat feed (e.g. Drama, Movie Mix, BT Sport, etc.)

In place of the .dat feed Metabroadcast would like people to use their "Atlas" database via its API.  This module does just that by building on the "XMLTV" package.



OPERATION
---------

Drop-in module for the XMLTV package, run as a command-line script.  Output to a disc file in XMLTV format.

Includes a CGI script to run via a web browser.



PRE-REQUISITES
--------------

Assumes you already have a working copy of "XMLTV".

Optional: web server if you want to use the web browser front-end.



COMPATABILITY
-------------

Tested with Perl v5.8.8 and Apache 2.2.3

(Tech note: many web hosts provide only 5.8.8 so no features are included which require a more recent version of Perl.)



LINKS
-----

"Atlas" : http://atlas.metabroadcast.com/

XMLTV DTD : http://xmltv.cvs.sourceforge.net/viewvc/xmltv/xmltv/xmltv.dtd

XMLTV : http://wiki.xmltv.org/index.php/Main_Page

