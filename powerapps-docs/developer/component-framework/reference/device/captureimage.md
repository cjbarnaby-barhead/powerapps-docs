---
title: CaptureImage | Microsoft Docs
description: Invokes the device camera to capture the image.
keywords:
author: adrianorth
ms.date: 03/07/2022
ms.author: jdaly
ms.reviewer: jdaly
manager: kvivek

ms.suite: ""
ms.tgt_pltfrm: ""
ms.topic: "article"
ms.assetid: 1d9c0063-add2-4002-acab-1be07ca1f6b6
---

# captureImage

[!INCLUDE[./includes/captureimage-description.md](./includes/captureimage-description.md)]

## Available for

Model-driven (mobile client) and canvas apps (mobile client)

## Syntax

`context.device.captureImage(options)`

## Parameters

| Parameter Name | Type     | Required | Description                  |
| -------------- | -------- | -------- | ---------------------------- |
| `options`      | `Object` | No       | Options for capturing image. |

The `options` parameter object has the following properties:

| Name                | Type      | Description                                                              |
| ------------------- | --------- | ------------------------------------------------------------------------ |
| `allowEdit`         | `Boolean` | Indicates whether to edit the image before saving.                       |
| `height`            | `Number`  | Height of the image to capture.                                          |
| `preferFrontCamera` | `Boolean` | Indicates whether to capture image using the front camera of the device. |
| `quality`           | `Number`  | Quality of the image file in percentage.                                 |
| `width`             | `Number`  | Width of the image to capture.                                           |

## Return Value

Type: `Promise<FileObject>`

See [Promise](https://developer.mozilla.org/docs/Web/JavaScript/reference/Global_Objects/Promise) and [FileObject](../fileobject.md)

## Exceptions

See [Web service error codes](../../../data-platform/org-service/web-service-error-codes.md)

### Related topics

[Device](../device.md)<br/>
[Power Apps component framework API reference](../../reference/index.md)<br/>
[Power Apps component framework overview](../../overview.md)

[!INCLUDE[footer-include](../../../../includes/footer-banner.md)]
