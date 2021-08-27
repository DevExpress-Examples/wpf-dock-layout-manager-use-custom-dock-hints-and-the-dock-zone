<!-- default badges list -->
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1781)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Hints.xaml](./CS/CustomTheme/Hints.xaml) (VB: [Hints.xaml](./VB/CustomTheme/Hints.xaml))
* [Window1.xaml](./CS/CustomTheme/Window1.xaml) (VB: [Window1.xaml](./VB/CustomTheme/Window1.xaml))
* [Window1.xaml.cs](./CS/CustomTheme/Window1.xaml.cs) (VB: [Window1.xaml.vb](./VB/CustomTheme/Window1.xaml.vb))
<!-- default file list end -->
# How to use custom dock hints and the dock zone in the DockManager


<p>It's necessary to respecify templates corresponding to the defined resource keys. The dock zone and dock hint elements are placed in the DockVisualizerThemeKey. The resource keys for the dock zone and the left dock hint are DockZone and Left keys respectively. These are the keys you should respecify:</p><p><ControlTemplate x:Key="{dxt:DockVisualizerThemeKey ResourceKey=Left}"><br />
<ControlTemplate x:Key="{dxt:DockVisualizerThemeKey ResourceKey=DockZone}"></p>

<br/>


