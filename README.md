# Timezone Converter

A React-based web application for converting and managing time across different time zones. The Timezone Converter allows users to easily add, remove, and reorder time zones, as well as adjust times and dates to view their equivalent in different zones. The app supports dark mode and provides sharing options for generated time links.

## Features

- **Timezone Management**: Add and remove time zones dynamically.
- **Time Adjustment**: Use a slider or dropdown to adjust times within different time zones.
- **Date Selection**: Pick a specific date to see its equivalent in selected time zones.
- **Dark Mode**: Toggle between light and dark themes.
- **Drag and Drop**: Reorder time zones using drag-and-drop functionality.
- **Link Sharing**: Generate shareable links with optional time and date inclusions.
- **Google Calendar Integration**: Open Google Calendar to create events.

## Technologies Used

- **React**: Front-end library for building the user interface.
- **moment-timezone**: Handling and formatting of time zones.
- **react-slider**: Slider component for time adjustment.
- **react-select**: Dropdown select component for time zone and time selection.
- **react-datepicker**: Date picker component.
- **@dnd-kit/core** and **@dnd-kit/sortable**: Drag-and-drop functionality.
- **react-icons**: Icons for UI components.

## Installation

1. **Clone the repository**:

    ```bash
    git clone https://github.com/dev-akhilesh/playpowerlabs-SDE-assignment
    ```

2. **Navigate to the project directory**:

    ```bash
    cd playpowerlabs-SDE-assignment
    ```

3. **Install dependencies**:

    ```bash
    npm install
    ```

4. **Run the development server**:

    ```bash
    npm start
    ```


## Usage

1. **Adding Time Zones**: Use the dropdown to search for and add time zones. Each added time zone will display its local time, which you can adjust.

2. **Adjusting Time**: Use the slider or dropdown within each time zone container to adjust the time and see the updated time in other zones.

3. **Date Selection**: Choose a date using the date picker to update the displayed times for all time zones.

4. **Reordering Time Zones**: Drag and drop time zones to reorder them as desired.

5. **Dark Mode**: Toggle dark mode using the moon/sun icon.

6. **Sharing Links**: Click the link icon to generate a shareable link with optional time and date information.

7. **Google Calendar**: Click the calendar-minus icon to open Google Calendar in a new tab for creating events.


## Acknowledgements

- **Moment.js** for time and date manipulation.
- **React Icons** for convenient icon usage.
- **@dnd-kit** for drag-and-drop functionality.
