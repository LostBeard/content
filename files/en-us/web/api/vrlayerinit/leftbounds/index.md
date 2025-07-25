---
title: "VRLayerInit: leftBounds property"
short-title: leftBounds
slug: Web/API/VRLayerInit/leftBounds
page-type: web-api-instance-property
status:
  - deprecated
  - non-standard
browser-compat: api.VRDisplay.getLayers
---

{{APIRef("WebVR API")}}{{Deprecated_Header}}{{Non-standard_Header}}

The **`leftBounds`** property of the {{domxref("VRLayerInit")}} interface (dictionary) defines the left texture bounds of the canvas whose contents will be presented by the {{domxref("VRDisplay")}}.

> [!NOTE]
> This property was part of the old [WebVR API](https://immersive-web.github.io/webvr/spec/1.1/). It has been superseded by the [WebXR Device API](https://immersive-web.github.io/webxr/).

## Value

An array of four floating point values, which can take values from 0.0–1.0.

- The left offset of the bounds.
- The top offset of the bounds.
- The width of the bounds.
- The height of the bounds.

If `leftBounds` is not specified in the dictionary, the default value used is `[0.0, 0.0, 0.5, 1.0]`.

## Examples

See [`VRLayerInit`](/en-US/docs/Web/API/VRLayerInit#examples) for example code.

## Specifications

This property was part of the old [WebVR API](https://immersive-web.github.io/webvr/spec/1.1/) that has been superseded by the [WebXR Device API](https://immersive-web.github.io/webxr/). It is no longer on track to becoming a standard.

Until all browsers have implemented the new [WebXR APIs](/en-US/docs/Web/API/WebXR_Device_API/Fundamentals), it is recommended to rely on frameworks, like [A-Frame](https://aframe.io/), [Babylon.js](https://www.babylonjs.com/), or [Three.js](https://threejs.org/), or a [polyfill](https://github.com/immersive-web/webxr-polyfill), to develop WebXR applications that will work across all browsers. Read [Meta's Porting from WebVR to WebXR](https://developers.meta.com/horizon/documentation/web/port-vr-xr/) guide for more information.

## Browser compatibility

{{Compat}}

## See also

- [WebVR API](/en-US/docs/Web/API/WebVR_API)
