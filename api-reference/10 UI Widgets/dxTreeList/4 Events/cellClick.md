---
type: eventType
---
---
##### shortDescription
Raised when a user clicks a cell.

##### param(e): object
Information about the event.

##### field(e.component): DOMComponent
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): object
The model data. Available only if you use Knockout.

##### field(e.jQueryEvent): jQuery.Event
The jQuery event that caused the handler execution. Deprecated in favor of the **event** field.

##### field(e.jQueryEvent).deprecated
Use 'event' instead.

##### field(e.event): event
The event that caused the handler execution. It is a [dxEvent](/api-reference/50%20Common/Object%20Structures/dxEvent '/Documentation/ApiReference/Common/Object_Structures/dxEvent/') or a [jQuery.Event](https://api.jquery.com/Types/#Event) when you use jQuery.

##### field(e.data): object
The data of the row to which the cell belongs. Available if the **rowType** is *'data'*, *'detail'* or *'detailAdaptive'*.

##### field(e.key): any
The row's key. Available if the **rowType** is *'data'*, *'detail'* or *'detailAdaptive'*.       
For plain data, the key value depends on the [keyExpr](/api-reference/10%20UI%20Widgets/dxTreeList/1%20Configuration/keyExpr.md '/Documentation/ApiReference/UI_Widgets/dxTreeList/Configuration/#keyExpr') option. For hierarchical data, the key is generated automatically or set in the underlying **Store** of the [data source](/api-reference/10%20UI%20Widgets/GridBase/1%20Configuration/dataSource.md '/Documentation/ApiReference/UI_Widgets/dxTreeList/Configuration/#dataSource').

##### field(e.value): any
The cell's raw value. Available if the **rowType** is *'data'*.

##### field(e.displayValue): string
The cell's displayed value. Available if the **rowType** is *'data'*.      
Differs from the **value** field only when the cell belongs to the [lookup](/api-reference/10%20UI%20Widgets/GridBase/1%20Configuration/columns/lookup '/Documentation/ApiReference/UI_Widgets/dxTreeList/Configuration/columns/lookup/') column.

##### field(e.text): string
The cell's [formatted](/api-reference/10%20UI%20Widgets/GridBase/1%20Configuration/columns/format.md '/Documentation/ApiReference/UI_Widgets/dxTreeList/Configuration/columns/#format') value converted to a string. Available if the **rowType** is *'data'*.

##### field(e.columnIndex): number
The index of the column to which the cell belongs.

##### field(e.column): object
This column's [configuration](/api-reference/10%20UI%20Widgets/dxTreeList/1%20Configuration/columns '/Documentation/ApiReference/UI_Widgets/dxTreeList/Configuration/columns/').

##### field(e.rowIndex): number
The visible index of the row to which the cell belongs.

##### field(e.rowType): string
The row's [type](/api-reference/10%20UI%20Widgets/dxTreeList/6%20Row/rowType.md '/Documentation/ApiReference/UI_Widgets/dxTreeList/Row/#rowType').

##### field(e.cellElement): dxElement
The cell's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.row): dxTreeListRowObject
The row [properties](/api-reference/10%20UI%20Widgets/dxTreeList/6%20Row '/Documentation/ApiReference/UI_Widgets/dxTreeList/Row/'). Available if the **rowType** is *'data'*, *'detail'* or *'detailAdaptive'*.

---
Main article: [onCellClick](/api-reference/10%20UI%20Widgets/dxTreeList/1%20Configuration/onCellClick.md '/Documentation/ApiReference/UI_Widgets/dxTreeList/Configuration/#onCellClick')

#####See Also#####
#include common-link-handleevents