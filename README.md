
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
### Name: Set Alarm
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

Alarm set -> Alarm goes off -> Set alarm to snooze

Alarm set -> Alarm goes off -> Turn alarm off

Alarm set -> Alarm goes off -> Automatic turn off

### Exceptional Flows
None.
### Post Conditions
None.
