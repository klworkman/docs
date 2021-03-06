﻿---
title: Parsing from a Path
keywords: messages, messaging, parsing, rest, querystring, path, http

created: 20170927
updated: 20170927
createdby: Kevin D. Wolf
updatedby: Kevin D. Wolf
---
[Home](../../Index.md) > [Device Messaging](../Index.md) > [Parsing Strategies](ParsingStrategies.md)

# Parsing from a Path

To Extract value from the path, select the search location

**Search Location**  
Path

And use the following syntax in the Path Locator

**Path Locator**  
`/deviceadmin/{deviceid}`


With the above **Path Locator** and the a given path of

`/deviceadmin/device1234`

The value ```device1234``` will be made available to the message.

##### Storage Type
You will also need to add a [Storage Type](../TypeSystem/Index.md) to identify how this field should be stored.