---
type: eventType
---
---
##### shortDescription
Fires before the submenu is displayed.

##### param(e): object
Information about the event.

##### field(e.component): DOMComponent
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): object
The model data. Available only if Knockout is used.

##### field(e.rootItem): dxElement
The container of the root menu element. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

---
Instead, you can use the [onSubmenuShowing](/api-reference/10%20UI%20Widgets/dxMenu/1%20Configuration/onSubmenuShowing.md '/Documentation/ApiReference/UI_Widgets/dxMenu/Configuration/#onSubmenuShowing') option to handle the event.

#####See Also#####
#include common-link-handleevents