<!-- default badges list -->
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1781)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# WPF Dock Layout Manager - Use Custom Dock Hints and The Dock Zone 

This example customizes left dock hint's colors.

To do this, override templates corresponding to the defined resource keys. The `DockVisualizerThemeKey` includes keys that specify the dock zone and dock hint element appearance. 

<img src="https://user-images.githubusercontent.com/12169834/175379492-9fa69de8-34e9-4b77-8e82-1434a52e5785.png" width=400px/>

This example overrides the following keys:

`<ControlTemplate x:Key="{dxt:DockVisualizerThemeKey ResourceKey=Left}">`
  
`<ControlTemplate x:Key="{dxt:DockVisualizerThemeKey ResourceKey=DockZone}">`

<!-- default file list -->
## Files to Look At

* [Hints.xaml](./CS/CustomTheme/Hints.xaml) (VB: [Hints.xaml](./VB/CustomTheme/Hints.xaml))
* [Window1.xaml](./CS/CustomTheme/Window1.xaml) (VB: [Window1.xaml](./VB/CustomTheme/Window1.xaml))
* [Window1.xaml.cs](./CS/CustomTheme/Window1.xaml.cs) (VB: [Window1.xaml.vb](./VB/CustomTheme/Window1.xaml.vb))
<!-- default file list end -->
