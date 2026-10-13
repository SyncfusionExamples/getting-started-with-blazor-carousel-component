# Getting Started with the Blazor Carousel Component

## Overview

This sample demonstrates how to use the Syncfusion [Blazor Carousel](https://www.syncfusion.com/blazor-components/blazor-carousel) component in a Blazor WebAssembly application. The application showcases carousel-based presentation of images and content arranged in a rotating interface that helps users navigate featured information efficiently.

The sample also demonstrates binding a data source to carousel items, enabling developers to generate slides dynamically instead of defining every item manually. This approach is useful for banners, product showcases, announcements, image galleries, and other content-driven experiences.

## Key Features

- Uses the Syncfusion [Blazor Carousel](https://www.syncfusion.com/blazor-components/blazor-carousel) component to display content in a rotating Generates carousel slides dynamically using a `foreach` loop that iterates through a strongly typed `List<CarouselDataModel>` collection.
- Demonstrates data-driven carousel item rendering with custom fields including `Title`, `ImageName`, and `Content`.
- Displays images within carousel items using locally hosted assets from the `images/carousel` folder.
- Combines images, headings, and descriptive text within each `CarouselItem` to create rich content slides.
- Defines a custom `CarouselDataModel` class to represent carousel item data.
- Binds multiple carousel items from a collection representing featured city information.
- Applies custom styling through the `CssClass="carousel-control"` property and CSS customization of carousel indicators.
- Demonstrates a reusable approach for populating carousel content from a data source instead of manually defining individual carousel items.

## Prerequisites

- [Visual Studio 2022](https://visualstudio.microsoft.com/vs/) or [Visual Studio Code](https://code.visualstudio.com/)
- [.NET SDK](https://dotnet.microsoft.com/en-us/download/dotnet) compatible with the project's target framework

## How to Run the Project

**Visual Studio 2022**

1. Clone or download the repository.
2. Open the `GettingStarted.sln` solution file.
3. Restore all NuGet packages.
4. Build the solution.
5. Run the application using `Ctrl+F5`.

**Visual Studio Code**

1. Clone or download the repository.
2. Open the repository folder in Visual Studio Code.
3. Navigate to the repository root.

```bash
dotnet restore
dotnet run
```

4. Open the URL displayed in the console after the application starts.

## Project Structure

`Client/Pages/Index.razor` - Main sample page that renders the Syncfusion Carousel component, defines the `CarouselDataModel` class, creates the data collection, generates carousel items dynamically, and customizes indicator styling.

`Client/wwwroot/images/carousel/san-francisco.png` - Image displayed for the San Francisco carousel item.

`Client/wwwroot/images/carousel/london.png` - Image displayed for the London carousel item.

`Client/wwwroot/images/carousel/tokyo.png` - Image displayed for the Tokyo carousel item.

`Client/wwwroot/images/carousel/moscow.png` - Image displayed for the Moscow carousel item.

## Support and Feedback

- For general product questions, visit the [Syncfusion Community Forum](https://www.syncfusion.com/forums) or [Syncfusion Support](https://www.syncfusion.com/support).
- To report an issue specific to this sample, open a GitHub issue in this repository.
- Official Carousel documentation: https://blazor.syncfusion.com/documentation/carousel/getting-started
- Online demo: https://blazor.syncfusion.com/demos/carousel/default-functionalities

## License

This is a Syncfusion sample project provided to demonstrate product usage. Review the [Syncfusion license terms](https://www.syncfusion.com/sales/pricing?category=ui-components) before using Syncfusion components in your own applications.
