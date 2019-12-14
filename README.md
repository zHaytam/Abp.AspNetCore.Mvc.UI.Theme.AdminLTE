# Abp.AspNetCore.Mvc.UI.Theme.AdminLTE

An [ABP](http://abp.io) theme module based on [AdminLTE](https://adminlte.io/)

![demo](doc/images/demo.png)

Although this module is in development stage, it works. You can see the sample project in the `src` folder.

# How to use

1. Install nuget packages
    
    * Web project:

        `Install-Package Abp.AspNetCore.Mvc.UI.Theme.AdminLTE`

1. Add `DependsOn` attribute

    * Web project:

        ``` csharp
        ...
        [DependsOn(typeof(AbpAspNetCoreMvcUiAdminLTEThemeModule))]
        public class YourWebModule : AbpModule
        {
            ...
        }
        ```

1. Enjoy
