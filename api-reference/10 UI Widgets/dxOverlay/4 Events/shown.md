---
type: eventType
---
---
##### shortDescription
Fires after the overlay is shown.

##### param(e): object
Information about the event.

##### field(e.component): DOMComponent
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): object
The model data. Available only if Knockout is used.

---
Instead, you can use the [onShown](/api-reference/10%20UI%20Widgets/dxOverlay/1%20Configuration/onShown.md '{basewidgetpath}/Configuration/#onShown') option to handle the event.

#####See Also#####
#include common-link-handleevents