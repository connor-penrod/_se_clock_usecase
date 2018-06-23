Connor Penrod

*The clock shows the time of day. Using buttons, the user can set the hours and minutes fields individually, and choose between 12 and 24-hour display.*

*It is possible to set one or two alarms. When an alarm fires, it will sound some noise. The user can turn it off, or choose to “snooze”. If the user does not respond at all, the alarm will turn off itself after 2 minutes. “Snoozing” means to turn off the sound, but the alarm will fire again after some minutes of delay. This “snoozing time” is pre-adjustable.*


![image not found](https://github.com/connor-penrod/_se_clock_usecase/blob/master/00UseCaseDiagram.png "Use Case Diagram")

# View Time Use Case
### Name
View Time
### Description
View the current time of day on the alarm clock display.
### Actors
User
### Preconditions
No preconditions.
### Basic Flow
User presses appropriate button -> Display time
### Alternate Flows
Display time -> User can set time fields

Display time -> Switch between 12 and 24 hour display
### Exceptional Flows
None.
### Post Conditions
12/24 hour display may have been changed (see alternate flows)

# Set Alarm(s) Use Case
### Name
Set Alarm
### Description
Set an alarm (or optionally, two) and perform various related functions.
### Actors
User
### Preconditions
2 alarms have not already been set.
### Basic Flow
User presses appropriate button -> User sets alarm
### Alternate Flows
Alarm set -> Switch between 12 and 24 hour display

Alarm set -> Another alarm can be set

Alarm set -> Set snooze time

### Exceptional Flows
None.
### Post Conditions
1 or 2 alarms have been set.

# Alarm Rings Use Case
### Name
Alarm Goes Off
### Description
Alarm that has been set reaches its time limit and begins ringing.
### Actors
User
### Preconditions
At least 1 alarm has been set.
### Basic Flow
Alarm goes off -> Alarm is turned off manually
### Alternate Flows
Alarm goes off -> Alarm is set to snooze

### Exceptional Flows
Alarm goes off -> User does not input a command for 2 minutes -> Alarm automatically turns off
### Post Conditions
1 or 2 alarms have been turned off.
