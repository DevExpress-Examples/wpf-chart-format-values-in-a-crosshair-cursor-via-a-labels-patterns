<!-- default badges list -->
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E4478)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->

# Chart for WPF -  How to Format Values in a Crosshair Cursor with Label Patterns

This example demonstrates how to change a text displayed in crosshair labels with crosshair patterns. 

![Chart](./images/Chart.png)

Specify a displayed pattern within a crosshair label with the following properties:

* [CrosshairAxisLabelOptions.Pattern](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.CrosshairAxisLabelOptions.Pattern)
* [XYSeries2D.CrosshairLabelPattern](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.XYSeries2D.CrosshairLabelPattern)
* [CrosshairOptions.GroupHeaderPattern](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.CrosshairOptions.GroupHeaderPattern)

You cab use standard and custom format specifiers are used together with the placeholders to format numeric and date/time values (e.g., {A:F0}). 

## Files to Review

* [MainWindow.xaml](./CS/UsingCrosshairLabelPattern/MainWindow.xaml) (VB: [MainWindow.xaml](./VB/UsingCrosshairLabelPattern/MainWindow.xaml))

## Documentation

* [Format Specifiers](http://documentation.devexpress.com/#WindowsForms/CustomDocument2141)
* [Crosshair Cursor](http://documentation.devexpress.com/#WPF/CustomDocument11974)


