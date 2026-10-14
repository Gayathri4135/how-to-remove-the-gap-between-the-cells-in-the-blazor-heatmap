# Remove Gaps Between Cells in the Syncfusion Blazor HeatMap

## Overview

This sample demonstrates how to remove the visual spacing that can appear between adjacent cells in a Syncfusion [Blazor HeatMap](https://www.syncfusion.com/blazor-components/blazor-heatmap-chart) configures cell border settings and applies SVG rendering behavior that produces seamless cell boundaries. This approach is useful when displaying dense matrix based visualizations where continuous color regions improve readability and presentation quality.

The sample focuses on achieving a fully connected HeatMap appearance without unwanted gaps caused by border rendering or SVG anti-aliasing behavior.

## Key Features

- Uses the `SfHeatMap` component to render HeatMap data.
- Configures `HeatMapCellBorder`.
- Sets the `Width` property of `HeatMapCellBorder` to `0`.
- Applies SVG `shape-rendering: crispEdges` styling to eliminate residual gaps that may remain even when border width is zero.
- Demonstrates rendering adjacent HeatMap cells with a seamless appearance.
- Uses Syncfusion Blazor HeatMap visualization APIs to control cell presentation.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download this repository.
2. Open `SampleBlaz.sln`.
3. Restore all NuGet packages.
4. Build the solution.
5. Press `Ctrl+F5` to run the application.

**Visual Studio Code**

1. Clone or download this repository.
2. Open the repository folder in Visual Studio Code.
3. Open the integrated terminal.
4. Navigate to the project directory.

```bash
cd .
dotnet restore
dotnet run
```

5. Open the URL displayed in the terminal after successful startup.

## Project Structure

- `SampleBlaz.sln` — Visual Studio solution file containing the sample projects.

- `Pages/Index.razor` — Main sample page containing the SfHeatMap implementation, data initialization logic, border configuration, and SVG styling.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- For implementation details, see the [relevant official Syncfusion documentation](https://blazor.syncfusion.com/documentation/heatmap-chart/getting-started).

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.