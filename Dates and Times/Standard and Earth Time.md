
### Standard Time
Since the unit of one second has a very solid and accurate scientific definition, it should remain the base unit for time tracking.

Standard Time is a value that just keeps incrementing by one second, forever, just like Unix Time. Unix Time can be considered an acceptable Standard Time, although it would be a rather unusual definition to start at.

### Earth Time
Earth Time solves the issues with the legacy time-keeping systems, and creates one more suitable to our modern requirements. It has taken some inspiration from Swatch time and is abbreviated as ET.

1. ET records the time within each earth day, and is calibrated using Standard Time. Every ET second interval ticks at the same tick of Standard Time. Each day begins with 000 ET, and ends after 999 ET. Any calibrations that occur must account for this.

2. ET is always the same for everyone, everywhere. It ignores the concept of timezones completely, eliminating all complications that come with involving timezones.

3. ET has exactly 100 "hours" in each day, making them exactly 864 seconds each (14.4 minutes in current time). Any amount of time (generally microsecond) that occur after the 86400 seconds has been reached is ignored and considered part of the calibration time between days.

4. The hours are recorded between 0 and 99, not between 1 and 100. Similarly, minutes are recorded between 0 and 9. This keeps them consistent with computer counting and gives them a consistent number of digits.

5. Every 1/10th of an hour is a "minute" (86.4 seconds, 1.44 minutes in current time). This means time can be measured in minutes very easily by just adding the minute number.

6. ET is formatted as two digits if only the hour need to be identified. For example: 00 ET, 01 ET, 02 ET, 03 ET, etc.

7. ET is formatted with three digits if the minute needs to be identified. For example: 005 ET, 223 ET, 715 ET, etc.

8. ET is formatted as total minutes:seconds with seconds ranging from 0 to 86 (within that minute's range) if seconds need to be identified. For example: 334:26 ET, 186:71 ET. In this format, the 86th and 0th second may self-calibrate between minutes since ET seconds tick at the same intervals as Standard Time.

9. If an exact second count is needed, a second-specific timestamp can be used "ETS" (Earth Time in Seconds) format. For example: 16473 ETS, 77438 ETS.
