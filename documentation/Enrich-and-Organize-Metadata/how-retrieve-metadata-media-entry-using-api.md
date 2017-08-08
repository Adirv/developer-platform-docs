---
layout: page
title: How to Retrieve Metadata of a Media Entry using the API?
weight: 101
---

To get a specific video entry, call the API [media.get](https://developer.kaltura.com/api-docs/#/media.get), which provides the ID of the Kaltura Entry.

The media.get request will return the basic metadata and information associated a Kaltura Entry.

 

Using the Kaltura REST API, the media.get request will look as [follows](http://www.kaltura.com/api_v3/index.php?service=media&action=get&entryId=yourentryId&ks=%7bks%7d).

```
http://www.kaltura.com/api_v3/index.php?service=media&action=get&entryId={yourentryId}&ks={ks}
```

Where *{yourentryId}* is the id of the media entry you'd like to retrieve information about, and *{ks}* is a valid [Kaltura Session](/api-docs/VPaaS-API-Getting-Started/how-to-create-kaltura-session.html) of an entitled user who has access to that media entry.

For a full list of the available Media Entry fields that will be returned by the media.get API, visit the [media.get API documents](https://developer.kaltura.com/api-docs/#/media.get).

 
