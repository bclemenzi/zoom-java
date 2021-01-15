# zoom-java
A simplified Java library for use with the Zoom Meeting API

## What is Zoom?

[Zoom API](https://marketplace.zoom.us/docs/api-reference/zoom-api) provides an API that allows a developers to access information from Zoom

Features
--------

  * Supports Zoom API v2.0.0
  * Fully implemented authentication system.  Just enter your Zoom credentials and go!
  * Published on Maven Central Repository

Getting started
---------------
Including the Java library in your project

The easiest way to incorporate the library into your Java project is to use Maven. Simply add a new dependency to your `pom.xml`:

```xml
<dependency>
    <groupId>com.nfbsoftware</groupId>
	<artifactId>zoom-java</artifactId>
	<version>1.0.0</version>
</dependency>
```

Get some credentials
-----

First you need some credentials (a "Client ID" and a "Client Secret").  Either get some by paying Zoom
some money, or by [signing up for a Zoom account](https://zoom.us/signup).

Usage
-----
Below you will find a number of basic examples to guide you through the use of the Java library.

**Basic Client Option**

```java	
String clientId = "25...89e9";  // Set your unique client id. Obtained from Zoom Support.
String clientSecret = "25...89e9";  // Set your unique client identifier. Obtained from Zoom Support.
String userId = "25...89e9";  // Set a GUID to be used in creating signature key when making calls to the Academic Benchmarks API 

// Init our client object
ZoomClient zoomClient = new ZoomClient(clientId, clientSecret);
```
