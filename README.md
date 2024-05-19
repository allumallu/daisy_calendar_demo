# Daycare Schedule to Calendar Converter

This project provides an HTML tool that allows parents to convert their children's daycare schedules into a downloadable iCalendar (.ics) file. The generated .ics file can then be imported into any standard calendar application, such as Outlook or Google Calendar, ensuring parents have up-to-date schedules for their children.

## Features

- **Data Extraction**: Extracts children's schedules from a text input.
- **Event Formatting**: Converts the extracted schedule data into iCalendar format.
- **File Generation**: Generates an iCalendar (.ics) file containing all relevant events.
- **User-Friendly Interface**: Simple web interface for generating and downloading the calendar file.

## How It Works

1. **Paste Schedule Data**: Paste your children's schedule into the provided text area in the HTML tool.
2. **Generate Calendar**: Click the "Generate Calendar" button to process the schedule data.
3. **Download .ics File**: Click the "Download Calendar" link to download the generated .ics file.
4. **Import to Calendar**: Import the .ics file into your preferred calendar application.

## Getting Started

### Prerequisites

- A web browser to open the HTML file.

### Usage

1. Clone the repository or download the HTML file.
    ```bash
    git clone https://github.com/your-username/daycare-schedule-to-calendar.git
    cd daycare-schedule-to-calendar
    ```
2. Open the `calendar_extractor.html` file in your web browser.
3. Paste the daycare schedule into the text area.
4. Click the "Generate Calendar" button.
5. Download the generated `.ics` file by clicking the "Download Calendar" link.
6. Import the `.ics` file into your preferred calendar application.

## Example Schedule Format

27.05.
ma
vko.22
Child1
08:0016:00
Child2
Poissa
28.05.
ti
vko.22
Child1
08:0016:00
Child2
Poissa
29.05.
ke
vko.22
Child1
08:3016:15
Child2
08:4516:15
30.05.
to
vko.22
Child1
08:3016:15
Child2
08:4516:00
31.05.
pe
vko.22
Child1
08:0015:30
Child2
07:4515:15
