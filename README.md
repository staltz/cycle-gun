# cycle-gun

**WIP**

A [cycle.js](https://github.com/cyclejs/cyclejs) driver that wraps a [gun.js](https://github.com/amark/gun) store instance.

Note: This driver currently depends on the [xstream](https://github.com/staltz/xstream) library.

## Overview

- A gun store is created inside a driver function pointing to an optional peer.
- A a method named `get` is returned with the sources.
- The `get` method accepts a function argument that accesses the gun store directly and returns an event stream.
- The returned event stream transforms selected events from the gun store into xstream events
- transform functions are bundled with the payload and streamed into driver sinks
 












