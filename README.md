
# mark-your-calendar
A jQuery plugin to used to pick available time in a day.

![Single selection demo](https://media.giphy.com/media/IxFbZYK5lVRCWurF5K/giphy.gif)

## Usage
$('#picker').markyourcalendar(options);

## 
- **availability**
An array that contains seven arrays (one for each day) that contains the time (string). 
E.g. 
[['1:00'], ['2:00', '3:00','4:00'], ['4:30'], ['22:00'], ['2:20', '2:40'], ['8:30'], ['9:00']]

- **isMultiple**
If set to true you can select multiple choices. Default value is false

- **months**
A list of months in a year. Default set to ['jan', 'feb', 'mar', 'apr', 'may', 'jun', 'jul', 'aug', 'sep', 'oct', 'nov', 'dec']

- **prevHtml**
The previous week button

- **nextHtml**
The next week button

- **startDate**
Set the first date on the picker. The current date is the default

- **weekdays**
- A list of days. Default set to ['sun', 'mon', 'tue', 'wed', 'thurs', 'fri', 'sat']

## Events
- **onClick**
Triggers when you make a selection. Returns the selected date(s)

- **onClickNavigator**
- Triggers when you click on the prev/next week buttons. See demo.

## Methods
- **setAvailability**
Sets the available options for each day of the week. See demo.
