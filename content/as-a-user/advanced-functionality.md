---
title: Advanced Functionality
weight: -10
---

Commands that have a more specific use, or are part of a specific feature set, are put in this section.

<!--more-->

{{< toc >}}

## Color of The Day

These commands only work if Color of The Day has been configured by the server admins.

- `cotd`<br>
Displays the current Color of The Day.

- `voteskip`<br>
Votes to skip the current Color of The Day by moving the roll time an hour earlier.

## Information

- `dump`/`d` [case ID or "l"]{(- or ..)case ID or "l"}<br>
Dumps user IDs from the public moderation log.

- `info` [user (yourself)]<br>
Gets information on a user.

- `info server` [server (current)]<br>
Gets information on a server.

- `info role` [role ID or name (`@everyone`)]<br>
Gets information on a role.

- `joinscore` {joinscore or mention}<br>
Posts your (or someone else's) joinscore for the current server.

- `joingraph`<br>
Posts a graph of times people have joined.

- `mylogs`<br>
Lists actions taken on you by server Staff.

## Reminders

- `remind` [time] [text]<br>
Reminds you about something in Direct Messages.<br>
Use "number then unit" format, such as *5s*, which is the minimum.

- `reminders`<br>
Lists your reminders.

- `reminders remove` [index]<br>
Removes a reminder using the index from the `reminders` command.<br>

## Timezones

- `timezone`/`tz` [timezone]<br>
Sets your timezone. You can use [this list](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones) as a reference.

- `timefor`/`tf` [user] {time in "12AM", "12 AM", "12:00 AM", or "00:00"}<br>
Shows the timezone for you, or someone else.

## Erasure

- `erase`<br>
Erases all of your messages from the Discord server, and sends you links to all of the files you have sent.
