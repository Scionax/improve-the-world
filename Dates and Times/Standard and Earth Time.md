
### Standard Time
Since the unit of one second has a very solid and accurate scientific definition, it should remain the base unit for time tracking.

Standard Time is a value that just keeps incrementing by one second, forever, just like Unix Time. Unix Time can be considered an acceptable Standard Time, although it would be a rather unusual definition to start at.

### Earth Time
Earth Time solves the issues with the legacy time-keeping systems, and creates one more suitable to our modern requirements. It has taken some inspiration from Swatch time and is abbreviated as ET.

1. ET records the time within each earth day, and is calibrated using Standard Time. Every ET second interval ticks at the same tick of Standard Time. Each day begins with 0 ET, and ends when 95 ET ends.

2. ET is always the same for everyone, everywhere. It ignores the concept of timezones completely, eliminating all complications that come with involving timezones.

3. ET has exactly 96 "hours" in each day, making them exactly 15 minutes each (or 900 seconds each) in current time. Any amount of time (generally microsecond) that occur after the 86400 seconds has been reached is ignored and considered part of the calibration time between days.

4. The hours are recorded between 0 and 95, not between 1 and 96.

5. "Minutes" are considered 1/10th of an hour, and are recorded between 0 and 9. This keeps them consistent with computer counting and gives them a consistent number of digits. A minute in ET is equal to 90 seconds in current time.

6. "Ticks" are considered 1/100th of an hour or 1/10th of a minute, and are recorded between 0 and 99. This keeps them consistent with computer counting and gives them a consistent number of digits. A tick in ET is equal to 9 seconds in current time.

7. Minutes and ticks can be measured and recorded very easily as decimal values of an hour. For example, .34 is 3 minutes and 4 ticks (or 34 ticks).

8. ET is formatted as an integer if only the hour need to be identified. For example: 0 ET, 15 ET, 73 ET, etc.

9. ET is formatted as a decimal if the minutes and/or ticks need to be identified. For example: 3.2 ET, 81.76 ET, etc.

10. ET is formatted as hours.ticks:seconds with seconds ranging from 0 to 9 (within that minute's range) if seconds need to be identified. For example: 3.40:6 ET, 73.23:3 ET.

11. Seconds range from 0 to 8, not from 1 to 9. This keeps them consistent with computer counting and gives them a consistent number of digits.
