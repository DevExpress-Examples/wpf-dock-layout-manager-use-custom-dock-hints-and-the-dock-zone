<!-- default file list -->
*Files to look at*:

* [CustomTheme.xaml](./CS/CustomThemeApp/CustomTheme.xaml) (VB: [CustomTheme.xaml](./VB/CustomThemeApp/CustomTheme.xaml))
* [Window1.xaml](./CS/CustomThemeApp/Window1.xaml) (VB: [Window1.xaml](./VB/CustomThemeApp/Window1.xaml))
* [Window1.xaml.cs](./CS/CustomThemeApp/Window1.xaml.cs) (VB: [Window1.xaml.vb](./VB/CustomThemeApp/Window1.xaml.vb))
<!-- default file list end -->
# How to use custom dock hints and the dock zone in the DockManager


<p>It's necessary to respecify templates corresponding to the defined resource keys. The dock zone and dock hint elements are placed in the DockVisualizerThemeKey. The resource keys for the dock zone and the left dock hint are DockZone and Left keys respectively. These are the keys you should respecify:</p><p><ControlTemplate x:Key="{dxt:DockVisualizerThemeKey ResourceKey=Left}"><br />
<ControlTemplate x:Key="{dxt:DockVisualizerThemeKey ResourceKey=DockZone}"></p>

<br/>


