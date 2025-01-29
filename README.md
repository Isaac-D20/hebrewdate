# hebrewdate
Python module for handling Hebrew dates

This module provides classes and functions for handling Hebrew calendar dates and conversions.

It offers two main classes:
- ``HebrewDate``: Represents a specific date in the Hebrew calendar, with support for conversions
  to/from Gregorian dates, manipulation of dates (e.g., adding or subtracting days, months, or years),
  and various date-related attributes such as day, month, year, and weekday in the Hebrew calendar.
- ``HebrewYear``: Represents a Hebrew year, managing leap year calculations, month lengths, and
  determining the first weekday of the year.

Key Features:
- Conversion between Hebrew and Gregorian dates.
- Computation of weekdays, month lengths, and leap year statuses for Hebrew dates.
- Operations for date arithmetic such as addition and subtraction of days, months, and years.
- Classmethods for obtaining today's Hebrew date or constructing a Hebrew date from a Gregorian date.
- Handling of historical edge cases and adjustments within the Hebrew calendar system.

Note:
This module supports accurate conversions for Hebrew dates corresponding to Gregorian dates on or after the year 1752.
For earlier dates, calculations may have inaccuracies due to historical and calendar system variations.

Author: Isaac Dovolsky
Created: 2025
