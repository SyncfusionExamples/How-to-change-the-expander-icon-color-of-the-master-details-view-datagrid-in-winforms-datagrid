# How to change the expander icon color of the Master-Details View in WinForms DataGrid (SfDataGrid)?

## About the sample

This sample illustrates how to change the expander icon color of the Master-Details View in WinForms DataGrid.

In SfDataGrid, You can change the color of the expander icon of the master details view as shown in the following code example.  

```c#
typeof(DataGridStyle).GetProperty("DetailsViewExpanderColor", System.Reflection.BindingFlags.NonPublic | System.Reflection.BindingFlags.Instance).SetValue(this.sfDataGrid1.Style, Color.Red);
```
![MasterDetailsView_ExpanderIcon](image.png)

## Requirements to run the demo
Visual Studio 2015 and above versions

