# Theme-WPF
Help

<Application x:Class="Backup.App"
             xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
             xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
             xmlns:local="clr-namespace:Backup"
             StartupUri="Views/MainView.xaml">
    <Application.Resources>
    
        <ResourceDictionary>
            <ResourceDictionary.MergedDictionaries>
                <ResourceDictionary Source="/Themes/ColourfulDarkTheme.xaml"/>
                // ...
            </ResourceDictionary.MergedDictionaries>
        </ResourceDictionary>
        
    </Application.Resources>
</Application>
