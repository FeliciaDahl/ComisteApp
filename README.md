# Comiste App

A modern web application for a restaurant built with ASP.NET Core Razor Pages.

## Overview

Comiste App is a restaurant website featuring an intuitive interface for customers to explore the menu, make reservations, and get in touch with the restaurant.

## Features

- **Home Page**: Welcome screen with quick navigation to key sections
- **Menu**: View the restaurant's menu and drink selections
- **Booking**: Reserve a table or contact for group reservations (10+ people)
- **Contact**: Get in touch with the restaurant

## Technology Stack

- **Framework**: ASP.NET Core 9.0
- **UI**: Razor Pages
- **Language**: C#
- **Features**: Implicit usings, nullable reference types enabled

## Project Structure

```
ComisteApp/
├── WebAppRazor/
│   ├── Pages/              # Razor pages (Home, Menu, Booking, Contact)
│   ├── Partials/           # Reusable page components
│   ├── Shared/             # Shared layouts and utilities
│   ├── wwwroot/            # Static assets (images, CSS, JS)
│   ├── Properties/         # Project properties
│   ├── appsettings.json    # App configuration
│   └── Program.cs          # Application startup configuration
└── ComisteApp.sln          # Solution file
```

## Getting Started

### Prerequisites

- .NET 9.0 SDK or later
- Visual Studio 2022 or any compatible IDE

### Running the Application

1. Clone the repository
2. Open `ComisteApp.sln` in Visual Studio
3. Build the solution
4. Press F5 or click Run to start the application
5. Navigate to the local server address (typically `https://localhost`)

## Pages

- **Index** (`/`): Home page with navigation
- **Menu** (`/menu`): Restaurant menu with drink options
- **Booking** (`/booking`): Table reservation and group booking requests
- **Contact** (`/contact`): Contact information and form

## Development

The application uses ASP.NET Core Razor Pages for rapid development with server-side rendering. Configuration can be adjusted in `appsettings.json` and `appsettings.Development.json`.

## License

Not specified
