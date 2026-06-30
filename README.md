# How to Customize the Time Format Without Locale Option

This example repository demonstrates how to customize the time format in [JavaScript Scheduler](https://www.syncfusion.com/javascript-ui-controls/js-scheduler) without using locale options. It showcases using Internationalization to format time in the scheduler's time scale, providing a practical approach for displaying custom time formats in scheduling components.

## Features

- Custom time format customization in Scheduler quick popup without locale options
- Uses Internationalization API for time formatting
- Dynamic day name display (wide format)
- Support for all-day events with appropriate time display
- Multi-day event handling with start and end time details
- Responsive Scheduler interface

## Installation

1. Clone or download the sample repository
2. Navigate to the project directory

## Usage

1. Open `Sample.html` directly in your web browser, or
2. Run a local development server:
   ```
   npm start
   ```
3. Navigate to the local server URL in your browser
4. Click on events in the Scheduler to see the quick popup with custom-formatted time details

## Configuration

Customize time formatting in the quick popup using the Internationalization `formatDate` method:

```javascript
// Format time with short skeleton
var instance = new ej.base.Internationalization();
var formattedTime = instance.formatDate(date, { type: 'time', skeleton: 'short' });

// For custom formatting without locale, modify the skeleton option:
// 'short'   - e.g., 10:30 AM
// 'medium'  - e.g., 10:30:45 AM
// 'long'    - e.g., 10:30:45 AM GMT+5:30
```

You can customize the time format by modifying the `skeleton` property in the `formatDate` method within the `popupOpen` event handler. The Internationalization class handles the formatting based on the specified skeleton and locale.

## License

This sample is provided as part of the EJ2 JavaScript library documentation and examples.
