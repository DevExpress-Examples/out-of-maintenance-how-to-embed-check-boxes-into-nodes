<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/166012610/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T830479)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# How to Embed Check Boxes into Nodes

You can embed check boxes into nodes to allow an end user to [check/uncheck nodes](https://docs.devexpress.com/WPF/13796/controls-and-libraries/data-grid/grid-view-data-layout/nodes/check-nodes?v=19.1). 

![](/images/checking-nodes.png)


To embed check boxes into nodes:

1. Specify the [TreeListView.CheckBoxFieldName](https://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.TreeListView.CheckBoxFieldName.property?v=19.1) property to bound check boxes to a boolean field in the grid's data source.
2. Set the [TreeListView.ShowCheckboxes](https://docs.devexpress.com/WPF/DevExpress.Xpf.Grid.TreeListView.ShowCheckboxes.property?v=19.1) property to **true** to display check boxes embedded into nodes.
