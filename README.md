Description:
This Python program converts a given time from one timezone to another, supporting any region or city worldwide.

The user enters a time in 24-hour HH:MM format.

The user can input partial or full names of the source and target timezones (e.g., "asia", "new_york", "europe", or "tokyo").

The program searches all timezones available in the pytz library that match the user's input (case-insensitive).

If multiple matching timezones are found, the program lists them and asks the user to select the desired timezone.

After selection, the program converts the input time from the source timezone to the target timezone.

The converted time is displayed in HH:MM AM/PM format.

This approach allows users to work with any timezone region or city worldwide, even if they only know part of the timezone name. It improves usability by guiding users through the selection when the input is ambiguous.

The program relies on the datetime module for time handling and the pytz library for timezone conversion.

