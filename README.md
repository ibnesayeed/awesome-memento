# Awesome Memento [![Awesome](https://awesome.re/badge.svg)](https://github.com/sindresorhus/awesome)
A list of things related to software, literature, and other content for Memento ([RFC7089](https://tools.ietf.org/html/rfc7089)).

## Contents

* [Software](#software)
  * [Web Browser Extensions](#web-browser-extensions)
  * [Mobile Apps](#mobile-apps)
  * [Command-line Clients](#command-line-clients)
  * [Server-side Enablers](#server-side-enablers)
  * [Web Archive Replay](#web-archive-replay)
* [Literature](#literature)
  * [Peer-Reviewed Publications](#peer-reviewed-publications)
  * [Blog Posts](#blog-posts)

## Software
### Web Browser Extensions
* Memento Time Travel - Google Chrome extension and Mozilla Firefox Add-On ([src](https://github.com/mementoweb/memento_chrome), [WebStore](https://chrome.google.com/webstore/detail/memento/jgbfpjledahoajcppakbgilmojkaghgm), [Add-On Store](https://addons.mozilla.org/en-US/firefox/addon/memento-timetravel/))
* MementoFox - Firefox Add-On ([src](https://code.google.com/archive/p/mementofox/), deprecated)
* Mink - Google Chrome Extension ([src](https://github.com/machawk1/mink), [WebStore](https://chrome.google.com/webstore/detail/mink-integrate-live-archi/jemoalkmipibchioofomhkgimhofbbem))

### Mobile Apps
* Memento-Browser - View web archives in the time dimension on Android ([src](https://github.com/machawk1/mementobrowser-android))
* MementoBrowser-ios - View web archives in the time on iOS ([src](https://github.com/machawk1/mementobrowser-ios))
* Mobile Mink - View and create archived versions of mobile and desktop pages on Android ([src](https://github.com/oduwsdl/mobilemink))

### Command-line Clients
* py-memento-client ([src](https://github.com/mementoweb/py-memento-client)) - Python-client to interface with Memento entities.
* mcurl ([src](https://github.com/aalsum/mcurl)) - Command Line Memento Client (perl)
* memento-client ([src](https://github.com/jarofghosts/memento-client), [npm](https://www.npmjs.com/package/memento-client)) - JavaScript client to interface with Memento services
* archive.is - ([src](https://github.com/qvint/archive.is), [npm](https://www.npmjs.com/package/archive.is)) - Memento-based API for [archive.is](http://archive.is/) in JavaScript

### Server-side Enablers
* django-memento-framework ([src](https://github.com/pastpages/django-memento-framework)) - Add Memento support to [Django](https://www.djangoproject.com/) applications.
* invenio-memento - ([src](https://github.com/inveniosoftware/invenio-memento)) - Add Memento support to [Invenio](http://invenio-software.org/) sites.
* Linked Data
  * [Apache Marmotta](http://marmotta.apache.org/) - An open implementation of the W3C Linked Data Platform specification, which supports versioning and access to versions compliant with the Memento protocol.
  * [Linked Data Fragments Server](https://github.com/LinkedDataFragments/Server.js/) - Server-side component offering [Triple Pattern Fragments](http://www.hydra-cg.com/spec/latest/triple-pattern-fragments/) and different versions of an evolving dataset using Memento.
* MediaWiki Extensions - Add Memento support to [MediaWiki](https://www.mediawiki.org/wiki/MediaWiki) instances: 
  * [Extension: Memento](https://www.mediawiki.org/wiki/Extension:Memento) - Provides complete Memento support. 
  * [Extension: MementoHeaders](https://www.mediawiki.org/wiki/Extension:MementoHeaders) - Provides only the necessary HTTP headers for minimal Memento support.
* Memento Tracer ([site](http://tracer.mementoweb.org/), no public prototype) - server-side processor to capture web publications for archival purposes.
* mementoweb - ([npm](https://www.npmjs.com/package/mementoweb)) - JavaScript module to add Memento functionality to [Express](http://expressjs.com/) projects.
* MemGator ([src](https://github.com/oduwsdl/memgator)) - Memento Aggregator written in Go.
* TimeGate ([src](https://github.com/mementoweb/timegate)) - Python and uwsgi script to intercept requests for resource to make them Memento-compatible.
* wordpress-memento-plugin - ([src](https://github.com/pastpages/wordpress-memento-plugin)) - Add Memento support to [WordPress](https://wordpress.com/) sites.

### Web Archive Replay
* OpenWayback ([src](https://github.com/iipc/openwayback)) - De facto web archive replay engine with the ability to provide Memento headers to archived resources. Written in Java.
* pywb ([src](https://github.com/webrecorder/pywb)) - Python-based replay engine.
* InterPlanetary Wayback (ipwb) ([src](https://github.com/oduwsdl/ipwb)) - Integration of WARCs with IPFS, supports Memento in bundled replay system.

## Literature
### Peer-Reviewed Publications
* [RFC7089](https://tools.ietf.org/html/rfc7089) - HTTP Framework for Time-Based Access to Resource States -- Memento.
* [The Off-Topic Memento Toolkit](https://www.cs.odu.edu/~mln/pubs/ipres-2018/ipres-2018-jones-off-topic.pdf) - S. Jones et al. - iPres - September 2018.
* [InterPlanetary Wayback: The Next Step Towards Decentralized Web Archiving](https://www.slideshare.net/ibnesayeed/interplanetary-wayback-the-next-step-towards-decentralized-web-archiving-108525567) - S. Alam et al. - Decentralized Web Summit and IPFS Lab Day - August 2018.
* [A Framework for Aggregating Private and Public Web Archives](https://dl.acm.org/citation.cfm?id=3197045) - M. Kelly et al. - JCDL - June 2018.
* [Focused Crawl of Web Archives to Build Event Collections](https://dl.acm.org/citation.cfm?id=3201085) - M. Klein et al.
* [Impact of URI Canonicalization on Memento Count](http://ieeexplore.ieee.org/abstract/document/7991601/) - M. Kelly et al. - JCDL - June 2017.
* [InterPlanetary Wayback: Peer-To-Peer Permanence of Web Archives](https://doi.org/10.1007/978-3-319-43997-6_35) - M. Kelly et al. - TPDL - August 2016 ([presentation slides](http://www.slideshare.net/ibnesayeed/interplanetary-wayback-peertopeer-permanence-of-web-archives)).
* [Detecting off-topic pages within TimeMaps in Web archives](http://link.springer.com/article/10.1007/s00799-016-0183-5) - Y. Anwar et al. - IJDL - July 2016.
* [InterPlanetary Wayback: The Permanent Web Archive](https://dx.doi.org/10.1145/2910896.2925467) - S. Alam et al. - JCDL - June 2016.
* [MemGator - A Portable Concurrent Memento Aggregator: Cross-Platform CLI and Server Binaries in Go](http://dl.acm.org/citation.cfm?id=2925452) - S. Alam and M. Nelson - JCDL - June 2016.
* [Routing Memento Requests Using Binary Classifiers](http://dl.acm.org/citation.cfm?id=2910899) - N. Bornand et al. - JCDL - June 2016.
* [Only One Out of Five Archived Web Pages Existed as Presented](http://dl.acm.org/citation.cfm?id=2791044) - S. Ainsworth et al. - Hypertext - September 2015.
* [Mobile Mink: Merging Mobile and Desktop Archived Webs](http://dl.acm.org/citation.cfm?id=2756956) - W. Jordan et al. - JCDL - June 2015.
* [Mink: Integrating the Live and Archived Web Viewing Experience Using Web Browsers and Memento](http://dl.acm.org/citation.cfm?id=2740872) - M. Kelly et al. - JCDL - September 2014.
* [Not All Mementos Are Created Equal: Measuring The Impact Of Missing Resources](http://dl.acm.org/citation.cfm?id=2740826) - J. Brunelle et al. - JCDL - September 2014.
* [Evaluating sliding and sticky target policies by measuring temporal drift in acyclic walks through a web archive](http://link.springer.com/article/10.1007/s00799-014-0120-4) - S. Ainsworth and M. Nelson - IJDL - August 2014.
* [Global Web Archive Integration with Memento](https://dl.acm.org/citation.cfm?doid=2232817.2232900) - R. Sanderson - JCDL - June 2012.

### Blog Posts
* November 1, 2016 - [Fixing broken links in Wikipedia](http://blog.dshr.org/2016/11/fixing-broken-links-in-wikipedia.html) 
* September 6, 2016 - [Memento at W3C](http://blog.dshr.org/2016/09/memento-at-w3c.html)
* August 25, 2016 - [Evanescent Web Archives](http://blog.dshr.org/2016/08/evanescent-web-archives.html)
* August 23, 2016 - [Content Negotiation and Memento](http://blog.dshr.org/2016/08/content-negotiation-and-memento.html)
* January 8, 2016 - [Aggregating Web Archives](http://blog.dshr.org/2016/01/aggregating-web-archives.html)
* April 23, 2013 - [Making Memento Successful](http://blog.dshr.org/2013/04/making-memento-succesful.html)
* March 5, 2013 - [Re-thinking Memento Aggregation](http://blog.dshr.org/2013/03/re-thinking-memento-aggregation.html)
* January 3, 2011 - [Memento & the Marketplace for Archiving](http://blog.dshr.org/2011/01/memento-marketplace-for-archiving.html)
