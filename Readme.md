<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128643475/21.1.5%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T326792)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
# WPF Dock Layout Manager - Populate Tabs with Items

This example displays content in [DockLayoutManager](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DockLayoutManager)'s tabs.


<img src="https://user-images.githubusercontent.com/12169834/175351620-63365ade-c0a0-4bd0-ac6c-0907dd5a3647.png" width=525px/>

To do this, you can use any of the following containers:

- A [LayoutGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutGroup) with [GroupBorderStyle](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutGroup.GroupBorderStyle) set to `Tabbed`
- A [TabbedGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.TabbedGroup)
- A [DocumentGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DocumentGroup)

A [DocumentGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.DocumentGroup) allows you to display dynamic content. It works similarly to the document area in Visual Studio.

![](https://raw.githubusercontent.com/DevExpress-Examples/how-to-display-items-in-tabs-t326792/15.1.3+/media/cdfa2c50-a7ba-11e5-80bf-00155d62480c.png)

A [TabbedGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.TabbedGroup) displays static content such as toolbars, service information, and so on.

![](https://raw.githubusercontent.com/DevExpress-Examples/how-to-display-items-in-tabs-t326792/15.1.3+/media/e2d07c56-a7ba-11e5-80bf-00155d62480c.png)

A [LayoutGroup](https://docs.devexpress.com/WPF/DevExpress.Xpf.Docking.LayoutGroup) with the `Tabbed` style is created to display a static set of elements. It allows you to move tabs only in [customization mode](https://docs.devexpress.com/WPF/7223/controls-and-libraries/layout-management/dock-windows/layout-items#customization-mode).

<!-- default file list -->
## Files to Look At

* [MainWindow.xaml](./CS/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/MainWindow.xaml))
<!-- default file list end -->

## Documentation

- [Customization Mode](https://docs.devexpress.com/WPF/7223/controls-and-libraries/layout-management/dock-windows/layout-items#customization-mode)
