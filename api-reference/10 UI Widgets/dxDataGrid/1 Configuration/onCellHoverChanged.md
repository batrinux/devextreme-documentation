---
EventForAction: ..\4 Events\cellHoverChanged.md
default: null
type: function(e)
---
---
##### shortDescription
A handler for the [cellHoverChanged](/api-reference/10%20UI%20Widgets/dxDataGrid/4%20Events/cellHoverChanged.md '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Events/#cellHoverChanged') event.

##### param(e): Object
Information about the event.

##### field(e.component): DOMComponent
The widget's instance.

##### field(e.element): dxElement
The widget's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.model): Object
The model data. Available only if you use Knockout.

##### field(e.eventType): String
Indicates whether the pointer entered or left the cell. Can be either *'mouseover'* or *'mouseout'*.

##### field(e.data): Object
The data of the row to which the cell belongs.

##### field(e.key): any
The row's key. If a field providing keys is not specified in the [data source](/api-reference/10%20UI%20Widgets/GridBase/1%20Configuration/dataSource.md '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/#dataSource'), the whole data object is considered the key.

##### field(e.value): any
The cell's raw value.

##### field(e.text): String
The cell's [formatted](/api-reference/10%20UI%20Widgets/GridBase/1%20Configuration/columns/format.md '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/columns/#format') value converted to a string.

##### field(e.displayValue): String
The cell's displayed value. Differs from the **value** field only when the column to which the current cell belongs uses [lookup](/api-reference/10%20UI%20Widgets/dxDataGrid/1%20Configuration/columns/lookup '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/columns/lookup/').

##### field(e.columnIndex): Number
The index of the column to which the cell belongs. For details on indexes, see the [Column and Row Indexes](/concepts/05%20Widgets/DataGrid/15%20Columns/12%20Column%20and%20Row%20Indexes.md '/Documentation/Guide/Widgets/DataGrid/Columns/Column_and_Row_Indexes/') topic.

##### field(e.rowIndex): Number
The row's visible index. For details on indexes, see the [Column and Row Indexes](/concepts/05%20Widgets/DataGrid/15%20Columns/12%20Column%20and%20Row%20Indexes.md '/Documentation/Guide/Widgets/DataGrid/Columns/Column_and_Row_Indexes/') topic.

##### field(e.column): dxDataGridColumn
This column's [configuration](/api-reference/10%20UI%20Widgets/dxDataGrid/1%20Configuration/columns '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Configuration/columns/').

##### field(e.rowType): String
The row's type. This field equals *'data'* for data rows or *'group'* for group rows.

##### field(e.cellElement): dxElement
The cell's container. It is an [HTML Element](https://developer.mozilla.org/en-US/docs/Web/API/HTMLElement) or a [jQuery Element](https://api.jquery.com/Types/#jQuery) when you use jQuery.

##### field(e.row): dxDataGridRowObject
The row [properties](/api-reference/10%20UI%20Widgets/dxDataGrid/6%20Row '/Documentation/ApiReference/UI_Widgets/dxDataGrid/Row/').

---
The **cellHoverChanged** event fires when the hover state of a grid cell is changed. When implementing a handling function for this event, use the object passed to this function as its parameter. Among the fields of this object, you can find data relating to the cell whose hover state has been changed. For example, to identify whether a cell has been hovered over or hovered out, check the value of the **eventType** field.