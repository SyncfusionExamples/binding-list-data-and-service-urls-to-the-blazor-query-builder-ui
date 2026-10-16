# Binding List Data and Service URLs to the Blazor Query Builder UI

## Overview

This sample demonstrates how to bind data to the Syncfusion [Blazor Query Builder](https://www.syncfusion.com/blazor-components/blazor-query-builder) component in a hosted Blazor WebAssembly application. The implementation shows how Query Builder fields and rule definitions can be populated from both local collection data and data returned from remote service endpoints. This approach is useful when building filtering interfaces that must work with dynamically retrieved business data while maintaining a consistent query-building experience.

## Key Features

- Demonstrates binding local list data to the Query Builder component.
- Demonstrates loading Query Builder data through remote service URLs.
- Uses a hosted Blazor WebAssembly architecture with separate Client, Server, and Shared projects.
- Shows how filtering conditions can be built dynamically using data provided by API endpoints.
- Demonstrates integration between Syncfusion Query Builder and ASP.NET Core Web APIs.
- Provides examples of using hierarchical project structure for client and server data access.
- Illustrates Query Builder field generation from bound data sources rather than hard-coded field definitions.
- Supports remote data retrieval scenarios commonly used in enterprise filtering applications.

## Prerequisites

- Visual Studio 2022 or Visual Studio Code
- .NET SDK compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open the solution file:

   `BindingListDataSample.sln`

3. Restore all NuGet packages.
4. Set the startup project 
5. Build the solution.
6. Run the application using `Ctrl+F5`.
7. Verify that the Query Builder loads fields from local data and remote service endpoints.

**Visual Studio Code**

1. Open the repository folder in Visual Studio Code.
2. Open the integrated terminal.
3. Navigate to the repository root.

```bash
cd binding-list-data-and-service-urls-to-the-blazor-query-builder-ui
```

4. Restore packages.

```bash
dotnet restore
```

5. Run the application.

```bash
dotnet run
```

6. Open the local URL displayed in the terminal and verify Query Builder functionality.


## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official Query Builder documentation: https://blazor.syncfusion.com/documentation/query-builder/data-binding

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components.
