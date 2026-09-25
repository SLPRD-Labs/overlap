# Features
## 1. Availability Calendar

A calendar where users enter which dates and which part of the day they are available (morning / afternoon / evening / full day). This calendar is private: each user only sees their own. There are three states: **available** (green), **unsure** (orange, default), and **unavailable** (red). Full-day availability means being available in the morning **and** the afternoon. Recurring rules can be defined (e.g. "never available on Wednesday evenings").

## 2. Activity list

Any user can add activities, specifying when the activity takes place (e.g. a bar in the evening, or an event spanning several days) along with general information: estimated price per person, organizer(s) (the creator by default), location, capacity (optional, for information only), and a "do before" deadline (optional). An activity can be flagged as **recurring** (restaurant, bar...).

Each user can mark themselves as interested, and a list of interested users is visible to everyone. When a user marks interest, the app automatically pre-fills an activity-specific availability calendar, which the user can then edit. Changes made to the general calendar (Feature 1) are propagated to activity-specific calendars, except for slots that were manually edited in the specific calendar.

To find a date, the required availability depends on the activity's time period. A full-day activity requires "full day" availability, or both "morning" and "afternoon". A multi-day activity requires "full day" availability on each day.

The organizer can then create an activity proposal and is shown a list of candidate dates before the "do before" deadline. Each date displays the number of people who are available and "unsure", anonymously (counts only). The organizer picks a date.

### Polls

Each activity has a **Polls** section. Organizers can create polls to settle organizational questions: duration, location, budget, logistics, etc. A poll can be single-choice, multiple-choice, or free-text, with an optional closing date. Interested users are notified, and votes are public. Once a poll is closed, the organizer can copy the result into the activity details. The section remains available after the date has been chosen for practical matters such as carpooling or who brings what.

## 3. Scheduled events calendar

Once the organizer picks a date, the event appears in the calendar of every interested user and they receive a notification. They indicate whether they will attend: **yes**, **no** or **maybe**. Choosing "maybe" opens a popup encouraging them to make a decision. A "yes" automatically blocks the slot in the general calendar and in the activity-specific calendars. The event can be added to an external calendar in one click. Reminder notifications are sent to users who haven't responded.

If a user changes their availability on a slot where they have confirmed attendance, a popup warns them and asks whether they want to withdraw.

The organizer can cancel an event or move it back from "confirmed" to "planning", for instance to change the date. In both cases, participants are notified and the blocked slots are released. For a recurring activity, once the event has passed, the activity stays in the list along with the interested users, and the activity-specific calendars are reset.

## 4. Administration

An **Admin** role manages the app. Registration is closed: every new account is created with a "pending" status. The admin receives a notification and manually approves or rejects the request. The admin can view the user list and deactivate or delete accounts, and can moderate content by editing or deleting activities, events, or polls. On the maintenance side, the admin can enable maintenance mode, broadcast an announcement to all users, and view error logs.

## Future work

- The app currently assumes a single group. Eventually, it could support multiple separate groups, each with its own members, admin(s), activities and events.
- A messaging feature could be added.
- Connection with exterior calendars could be considered, both to import busy times and to export an activity.