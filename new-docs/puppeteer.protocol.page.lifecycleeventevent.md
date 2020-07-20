<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [puppeteer](./puppeteer.md) &gt; [Protocol](./puppeteer.protocol.md) &gt; [Page](./puppeteer.protocol.page.md) &gt; [LifecycleEventEvent](./puppeteer.protocol.page.lifecycleeventevent.md)

## Protocol.Page.LifecycleEventEvent interface

Fired for top level page lifecycle events such as navigation, load, paint, etc.

<b>Signature:</b>

```typescript
export interface LifecycleEventEvent 
```

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [frameId](./puppeteer.protocol.page.lifecycleeventevent.frameid.md) | [FrameId](./puppeteer.protocol.page.frameid.md) | Id of the frame. |
|  [loaderId](./puppeteer.protocol.page.lifecycleeventevent.loaderid.md) | [Network.LoaderId](./puppeteer.protocol.network.loaderid.md) | Loader identifier. Empty string if the request is fetched from worker. |
|  [name](./puppeteer.protocol.page.lifecycleeventevent.name.md) | string |  |
|  [timestamp](./puppeteer.protocol.page.lifecycleeventevent.timestamp.md) | [Network.MonotonicTime](./puppeteer.protocol.network.monotonictime.md) |  |
