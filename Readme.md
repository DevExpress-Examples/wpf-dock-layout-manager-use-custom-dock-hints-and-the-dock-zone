
# WPF Dock Layout Manager - Use Custom Dock Hints and The Dock Zone 

This example customizes the left dock hint's colors.

To do this, override templates corresponding to the defined resource keys. The `DockVisualizerThemeKey` includes keys that specify the dock zone and dock hint element appearance. 

<img src="https://user-images.githubusercontent.com/12169834/175379492-9fa69de8-34e9-4b77-8e82-1434a52e5785.png" width=400px/>

This example overrides the following keys:

`<ControlTemplate x:Key="{dxt:DockVisualizerThemeKey ResourceKey=Left}">`
  
`<ControlTemplate x:Key="{dxt:DockVisualizerThemeKey ResourceKey=DockZone}">`

<!-- default file list -->
## Files to Look At

* [Hints.xaml](./CS/CustomTheme/Hints.xaml) (VB: [Hints.xaml](./VB/CustomTheme/Hints.xaml))
* [Window1.xaml](./CS/CustomTheme/Window1.xaml) (VB: [Window1.xaml](./VB/CustomTheme/Window1.xaml))
<!-- default file list end -->

## Documentation

* [Visual Elements: Dock Guides and Hints](https://docs.devexpress.com/WPF/6827/controls-and-libraries/layout-management/dock-windows/visual-elements#dock-guides-and-hints)
