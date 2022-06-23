<!-- default badges list -->
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T326792)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# WPF Dock Layout Manager - Populate Tabs with Items


The DockLayoutManager allows you to display content in tabs in several approaches. To do this, you can use either of the following containers:

- A [LayoutGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutGroup) with [GroupBorderStyle](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutGroup.GroupBorderStyle) set to **Tabbed**;  
- A [TabbedGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.TabbedGroup);  
- A [DocumentGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DocumentGroup).

This example demonstrates all of available approaches.
  
Although all these groups allow displaying tabs, they are designed for use in different scenarios.  
A DocumentGroup will be the best choice if the task is to display dynamic content. It works similar to the document area in the Visual Studio.

![](https://raw.githubusercontent.com/DevExpress-Examples/how-to-display-items-in-tabs-t326792/15.1.3+/media/cdfa2c50-a7ba-11e5-80bf-00155d62480c.png)

A TabbedGroup is designed to display more static content like toolbars, service information, etc.  

![](https://raw.githubusercontent.com/DevExpress-Examples/how-to-display-items-in-tabs-t326792/15.1.3+/media/e2d07c56-a7ba-11e5-80bf-00155d62480c.png)

A LayoutGroup with the Tabbed style is intended to display a static set of elements. Unlike DocumentGroup and TabbedGroup, it supports moving tabs only in [customization mode](https://docs.devexpress.com/WPF/7222/controls-and-libraries/layout-management/dock-windows/layout-functionality/customization-mode).

<!-- default file list -->
## Files to Look At

* [MainWindow.xaml](./CS/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))
<!-- default file list end -->

## Documentation

## More Examples
