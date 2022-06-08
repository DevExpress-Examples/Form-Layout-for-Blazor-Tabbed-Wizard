# Form Layout for Blazor - Tabbed Wizard

This example demonstrates how to use the [DxFormLayout](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayout) component to create a responsive tabbed wizard. 

The Form Layout contains several tab groups ([DxFormLayoutTabPage](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutTabPage) component). Each tab group consists of several [items](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutItem) with editors. The standard Blazor [EditForm](https://docs.microsoft.com/en-us/dotnet/api/microsoft.aspnetcore.components.forms.editform?view=aspnetcore-6.0) component validates user input. 

A user can click the **Previous** and **Next** buttons to navigate between tabs. If validation fails on the **Submit** button click, the wizard navigates to the first tab that contains invalid editor values. Use the [DxFormLayoutTabPages.ActiveTabIndex](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutTabPages.ActiveTabIndex) property to implement this functionality. 
    

## Files to Look At

Index.razor

## Documentation

* [DxFormLayout](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayout)
* [ActiveTabIndexChanged](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutTabPages.ActiveTabIndexChanged)
* [DxFormLayoutTabPages.ActiveTabIndex](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutTabPages.ActiveTabIndex)

