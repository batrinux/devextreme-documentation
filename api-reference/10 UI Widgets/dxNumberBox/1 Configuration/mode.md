---
default: 'text', 'number' (mobile_devices)
acceptValues: 'number' | 'text' | 'tel'
type: String
---
---
##### shortDescription
Specifies the value to be passed to the [type](https://www.w3schools.com/tags/att_input_type.asp) attribute of the underlying `<input>` element.

---
[note] If you set the [format](/api-reference/10%20UI%20Widgets/dxNumberBox/1%20Configuration/format.md '/Documentation/ApiReference/UI_Widgets/dxNumberBox/Configuration/#format') option, the **mode** for mobile devices is changed to *"tel"*; *"number"* is not available.

When using the widget as an [ASP.NET MVC Control](/concepts/35%20ASP.NET%20MVC%20Controls/20%20Fundamentals '/Documentation/Guide/ASP.NET_MVC_Controls/Fundamentals/'), specify this option using the `NumberBoxMode` enum. This enum accepts the following values: `Text`, `Number`, and `Tel`.