# EJ2 JavaScript

A sample application demonstrating dynamic date format customization within quick popup components using the EJ2 JavaScript library.

## Overview

This sample showcases how to implement and configure different date formats in a quick popup interface. It provides practical examples of customizing date display formats to meet localization requirements and demonstrates best practices for date manipulation in web applications using EJ2 components.

## Features

- Dynamic date format customization in popup components
- Support for multiple date format patterns
- Quick popup with date controls
- Real-time format switching
- Responsive interface

## Prerequisites

- Node.js (v12.0 or higher)
- npm (v6.0 or higher)
- Modern web browser
- EJ2 JavaScript library

## Installation

1. Clone or download the sample repository
2. Navigate to the project directory
3. Install dependencies:
   ```
   npm install
   ```
4. Install EJ2 dependencies:
   ```
   npm install @syncfusion/ej2-base @syncfusion/ej2-calendars
   ```

## Usage

1. Open the project in your code editor
2. Run a local development server:
   ```
   npm start
   ```
3. Open your browser to the local development URL
4. Interact with the quick popup to select dates and customize the format

## Configuration

Configure date formats by modifying the format property:

```javascript
dateFormat: 'dd/MM/yyyy'   // US format
dateFormat: 'yyyy-MM-dd'   // ISO format
dateFormat: 'MMM dd, yyyy' // Text-based format
```

You can also customize popup position, initial date selection, and format conversion options based on your requirements.

## License

This sample is provided as part of the EJ2 JavaScript library documentation and examples.
