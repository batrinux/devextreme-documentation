---
type: eventType
---
---
##### param(e): object
Information about the event.

##### field(e.component): DOMComponent
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): object
The model data. Available only if Knockout is used.

##### field(e.itemIndex): number | object
The index of the item being held. In a grouped list, the index represents an object defining the group and item indexes: { group: 0, item: 0 }.

---