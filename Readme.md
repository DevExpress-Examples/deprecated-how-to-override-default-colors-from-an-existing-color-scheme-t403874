<!-- default file list -->
*Files to look at*:

* [App.xaml](./CS/App.xaml) (VB: [App.xaml](./VB/App.xaml))
* **[OverrideColors.xaml](./CS/Themes/OverrideColors.xaml) (VB: [OverrideColors.xaml](./VB/Themes/OverrideColors.xaml))**
<!-- default file list end -->
# [Deprecated] How to override default colors from an existing Color Scheme


Starting with <strong>v17.1</strong>, we provide a more powerful and flexible way of overriding predefined colors. Refer to the updated <a href="https://www.devexpress.com/Support/Center/p/T505694">How to override default colors from an existing Color Scheme in Windows 10 XAML controls</a> example for more information.<br><br>
<p>This example illustrates how to override default colors from an existing color scheme in Windows 10 XAML controls. In the current implementation, the background of the <strong>RibbonControl</strong> header is overridden to <em>#FF217346</em> in the <strong>Generic</strong> scheme and to <em>#FF093467</em> in the <strong>Win8</strong> scheme.</p>
<p>Colors should be overridden within a separate ResourceDictionary file. Then, this dictionary should be used in the <strong>Source </strong>property of the <strong>GlobalColorSchemeOverrider</strong> class.</p>
<p><br>All colors available for overriding are listed in separate files within the installation folder with our controls: <DevExpress Installation Folder><strong><strong><u>\Components\System\UAP\ColorThemes</u></strong></strong></p>

<br/>


