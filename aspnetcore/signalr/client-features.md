---
title: SignalR client features
author: bradygaster
description: Learn which features are supported by the various ASP.NET Core SignalR clients.
monikerRange: '>= aspnetcore-3.0'
ms.author: bradyg
ms.custom: mvc
ms.date: 09/18/2019
uid: signalr/client-features
---
# ASP.NET Core SignalR client features

## Feature distribution

The table below shows the features and support for the clients that offer real-time support.

| Feature | .NET | JavaScript | Java |
| ---- | :-: | :-: | :-: |
| Azure SignalR Service Support |✔|✔|✔|
| [Server-to-client Streaming](xref:signalr/streaming)          |✔|✔|✔|
| [Client-to-server Streaming](xref:signalr/streaming)          |✔|✔|✔|
| Automatic Reconnection ([.NET](/aspnet/core/signalr/dotnet-client?view=aspnetcore-3.0&tabs=visual-studio#handle-lost-connection), [JavaScript](/aspnet/core/signalr/javascript-client?view=aspnetcore-3.0#reconnect-clients))          |✔|✔| |
| WebSockets Transport |✔|✔|✔|
| Server-Sent Events Transport |✔|✔| |
| Long Polling Transport |✔|✔|✔|
| JSON Hub Protocol |✔|✔|✔|
| MessagePack Hub Protocol |✔|✔| |

Support for automatic reconnect in the Java client is tracked in [our issue tracker](https://github.com/aspnet/AspNetCore/issues/8711).

## Additional resources

* [Get started with SignalR for ASP.NET Core](xref:tutorials/signalr)
* [Supported platforms](xref:signalr/supported-platforms)
* [Hubs](xref:signalr/hubs)
* [JavaScript client](xref:signalr/javascript-client)
