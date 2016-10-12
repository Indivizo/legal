# Technical Requirements

Effective from 12 October, 2016.

Indivizo is a web application. As such it requires a stable internet connection.


## Supported devices, operating systems

The supported operating systems are Windows 7, Windows 8, Windows 10 and Mac OS X 10.9+.

The application can be used on Linux systems as well, but we don't officially support those and don't do testing on these operating systems.

Mobile devices, tablets are not supported. It is on our development roadmap to introduce support for them.

### Supported browsers

#### Windows 7, 8, 10

* Google Chrome, two latest versions;
* Mozilla Firefox, two latest versions;
* Internet Explorer 10 and 11.

#### Mac OS X 10.9+

* Google Chrome, two latest versions;
* Mozilla Firefox, two latest versions;


## Web addresses

In case of using a firewall or any software that controls network traffic, allowing the following web addresses is required:

#### https://app.indivizo.com

* TCP port 443

Our application.


#### https://fonts.googleapis.com

* TCP port 443

We retrieve fonts to be used in our application from here.


#### https://api.mixpanel.com

* TCP port 443

Analytics, statistics and data for support requests are tracked here.


## Requirements for video interviews

### Supported browsers

#### Windows 7, 8, 10

* Google Chrome, two latest versions;

#### Mac OS X 10.9+

* Google Chrome, two latest versions;

Recording video interviews on mobile devices, tablets are not supported. It is on our development roadmap to introduce support for them.

## Web addresses

In case of using a firewall or any software that controls network traffic, allowing the following web addresses is required:

#### https://video.indivizo.com

* TCP port 443;
* TCP and UDP port 3478.

Our video interview application.


#### http://46.101.130.28

* TCP and UDP port 3478.

Our [TURN server](https://en.wikipedia.org/wiki/Traversal_Using_Relays_around_NAT).

