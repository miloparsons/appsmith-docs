---
description: >-
  Datepicker is used to capture the date and time input by a user. It can be
  used to filter data based on the input date range as well as to capture
  personal information such as date of birth.
---

# Datepicker

![](../.gitbook/assets/date-picker.gif)

## Properties

| Internal Property | Description |
| :--- | :--- |
| **selectedDate** | This is the ISO date string selected in the date widget. This value changes if the default value is updated or the user inputs a value. |
| **formattedDate** | This is the date value displayed to the user in the date widget. This value changes if the default value is updated or the user inputs a value.  |

| Property | Description |
| :--- | :--- |
| **Label** | Sets the label of the Datepicker. |
| **Default Date** | Sets a default date that will be captured as user input unless it is changed by the user. The default date must be an ISO string and can be populated using a moment object **{{ moment\(\) }}** |
| **Date Format** | The format of the date selected by the date picker |
| **Required** | When turned on, it makes a user input required and disables any form submission until an input is made. |
| **Visible** | Controls widget's visibility on the page. When turned off, the widget will not be visible when the app is published |
| **Disabled** | Disables input to the widget. The widget will remain visible to the user but user input will not be allowed. |

| Action. | Description |
| :--- | :--- |
| **onDateSelected** | Sets the action to be run when the user selects a date. See a list of [supported actions](../core-concepts/writing-code/appsmith-framework.md) |

