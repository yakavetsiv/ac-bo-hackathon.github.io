---
title: Hackathon agenda 🗓️
menu_title: Agenda
menu_icon: clock
---
{% assign current_date = 'now' | date: "%Y-%m-%d" %}
{% assign event_start_date = site.event_start_date | date: "%Y-%m-%d" %}
{% assign event_close_date = site.event_close_date | date: "%Y-%m-%d" %}
{% assign registration_opens_date = site.registration_opens_date | date: "%Y-%m-%d" %}
{% assign registration_closes_date = site.registration_closes_date | date: "%Y-%m-%d" %}

{% if current_date < registration_opens_date %}
    {% assign registration_status = 'soon' %}
{% elsif current_date >= registration_opens_date and current_date <= registration_closes_date %}
    {% assign registration_status = 'open' %}
{% else %}
    {% assign registration_status = 'closed' %}
{% endif %}

{% if current_date < event_start_date %}
    {% assign event_status = 'soon' %}
{% elsif current_date >= event_start_date and current_date <= event_close_date %}
    {% assign event_status = 'now' %}
{% else %}
    {% assign event_status = 'over' %}
{% endif %}

## Schedule
{% if event_status != "over" %}
The anticipated schedule is as follows, with all times listed in Eastern Time (ET):
{% else %}
The schedule for the event was as follows, with all times listed in Eastern Time (ET):
{% endif %}

## Now - Mar 27

Brainstorm, build, team up.

### Day 1: Mar 27

| Time  | Activity |
|-------|----------|
| 09:00 | Welcome - Day 1 |
| 09:10 | Keynote |
| 09:50 | Orientation |
| 10:00 | Breakout |
| 13:00 | End of Day 1 |

### Day 2: Mar 28

| Time  | Activity |
|-------|----------|
| 09:00 | Welcome - Day 2 |
| 09:10 | Breakout |
| 12:45 | Closing Remarks |
| 13:00 | End of Event |

### Mar 29

Submissions due by [March 29 at 10:00 AM Eastern Time (ET)](https://everytimezone.com/s/d5b5871b).

## Day 1: Mar 27

Live Hackathon Day! 💻 Teams will be coordinating and there will be centrally run live sessions. Video submissions due!

<!-- {:.agenda} -->

<!-- {:.agenda} -->
<!-- Time (BST)    | Activity | Where to go
------------- | -------- | -----------
09:15 – 09:30 | Zoom meeting opens for informal networking | Zoom main room
09:30 – 10:00 | **Welcome talk**<br>Speaker name | Zoom main room
10:00 – 11:55 | **Breakout groups**<br>Recap and continue working on projects | Zoom breakout rooms
12:00 – 12:30 | **Yoga**<br>Take some time away from your keyboard | Zoom main room
12:30 – 13:30 | Lunch break |
13:30 – 16:30 | **Breakout groups**<br>Continue working on projects | Zoom breakout rooms
16:30 – 17:00 | **End of day tidy-up**<br>Write up<br>Commit your changes to GitHub<br>Tidy Group Workspace | Zoom breakout rooms
17:00 – 17:25 | **Group updates**<br>90 seconds per group<br>Zero or one slide 😊<br>How things are going; what problems you have faced | Zoom main room
17:25 – 17:30 | **Close of day** | Zoom main room -->


<!-- ## Day 2: Mar 28

Live session to announce prizes. -->