<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/500857088/22.1.2%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/T1094069)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
[![](https://img.shields.io/badge/💬_Leave_Feedback-feecdd?style=flat-square)](#does-this-example-address-your-development-requirementsobjectives)
<!-- default badges end -->
# Form Layout for Blazor - Tabbed Wizard

This example demonstrates how to use the [DxFormLayout](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayout) component to create a responsive tabbed wizard. 

![Tabbed Wizard](https://user-images.githubusercontent.com/80813840/172582855-3ca4166d-8e82-4bba-9f08-6d875e198bfc.png)

The Form Layout contains several tab groups ([DxFormLayoutTabPage](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutTabPage) component). Each tab group consists of several [items](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutItem) with editors. The standard Blazor [EditForm](https://docs.microsoft.com/en-us/dotnet/api/microsoft.aspnetcore.components.forms.editform?view=aspnetcore-6.0) component validates user input. 

A user can click the **Previous** and **Next** buttons to navigate between tabs. If validation fails on the **Submit** button click, the wizard navigates to the first tab that contains invalid editor values. Use the [DxFormLayoutTabPages.ActiveTabIndex](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutTabPages.ActiveTabIndex) property to implement this functionality. 
    

## Files to Look At

[Index.razor](https://github.com/DevExpress-Examples/Form-Layout-for-Blazor-Tabbed-Wizard/blob/22.1.2%2B/CS/TabbedLayout/Pages/Index.razor)

## Documentation

* [DxFormLayout](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayout)
* [ActiveTabIndexChanged](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutTabPages.ActiveTabIndexChanged)
* [DxFormLayoutTabPages.ActiveTabIndex](https://docs.devexpress.com/Blazor/DevExpress.Blazor.DxFormLayoutTabPages.ActiveTabIndex)

<!-- feedback -->
## Does this example address your development requirements/objectives?

[<img src="https://www.devexpress.com/support/examples/i/yes-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=Form-Layout-for-Blazor-Tabbed-Wizard&~~~was_helpful=yes) [<img src="https://www.devexpress.com/support/examples/i/no-button.svg"/>](https://www.devexpress.com/support/examples/survey.xml?utm_source=github&utm_campaign=Form-Layout-for-Blazor-Tabbed-Wizard&~~~was_helpful=no)

(you will be redirected to DevExpress.com to submit your response)
<!-- feedback end -->
