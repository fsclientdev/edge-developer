---
description: Host web content in your Win32 app with the Microsoft Edge WebView2 control
title: 0.8.355 - WebView2 Win32 C++ IWebView2CreateWebViewCompletedHandler
author: MSEdgeTeam
ms.author: msedgedevrel
ms.date: 07/20/2020
ms.topic: reference
ms.prod: microsoft-edge
ms.technology: webview
keywords: IWebView2, IWebView2WebView, webview2, webview, win32 apps, win32, edge
---

# 0.8.355 - interface IWebView2CreateWebViewCompletedHandler 

[!INCLUDE [deprecation-note](../../includes/deprecation-note.md)]

```
interface IWebView2CreateWebViewCompletedHandler
  : public IUnknown
```

The caller implements this interface to receive the WebView created via CreateWebView.

## Summary

 Members                        | Descriptions
--------------------------------|---------------------------------------------
[Invoke](#invoke) | Called to provide the implementer with the completion status and result of the corresponding asynchronous method call.

## Members

#### Invoke 

Called to provide the implementer with the completion status and result of the corresponding asynchronous method call.

> public HRESULT [Invoke](#invoke)(HRESULT result,[IWebView2WebView](IWebView2WebView.md) * webView)

