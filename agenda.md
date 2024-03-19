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
The anticipated schedule is as follows, with all times listed in Eastern Time (ET). Be sure to add the events to your calendar using the [Gather links](https://app.gather.town/events/aWWEyxSfRJGgvVwT3rSA).
{% else %}
The schedule for the event was as follows, with all times listed in Eastern Time (ET):
{% endif %}

## Now - Mar 27

Brainstorm, build, team up.

1. Add the events to your calendar using the [links from the Gather Town event page](https://app.gather.town/events/aWWEyxSfRJGgvVwT3rSA)
1. Join the [Slack channel](https://join.slack.com/share/enQtNjc5MjI1NTI3MDUzMy1lNjZlZWZlMGYxNzA3MTY2N2Q2MDA2ZjNlMDQxZmIyMmZkMmNhZmYyMjhhYWQyODM1NDI0Yjg0MGE4NjI3YTBl) (if the link is expired, contact us so we can provide a new link). UPDATE: If you aren't able to join due to Slack Pro plan limitations, we can add you as a guest manually. Please send a request to [sterling.baird@utoronto.ca](mailto:sterling.baird@utoronto.ca) with subject line "Slack guest invite request". The message body can be blank.
2. Brainstorm project ideas and form teams
   3. Browse [the existing project proposals](_/../projects.md)
   1. If you'd like to solicit team members or get feedback, post your project idea in the slack channel. You may also consider using social media
   2. If you would like to join a team, use the slack channel to express your interest and describe your background
   3. Submit your [project proposal](_/../submission.md) (multiple allowed)
4. For coding-related projects, [complete the orientation modules](_/../resources.md)

<!-- 4. If you plan to join an existing project, use the GitHub Classroom link corresponding to the project topic and select the appropriate team on the GitHub Classroom interface (see [submission](_/../submission.md)). Reach out to [sterling.baird@utoronto.ca](mailto:sterling.baird@utoronto.ca) if you have trouble getting added to your team -->

### Day 1: Mar 27

| Time  | Activity |
|-------|----------|
| 09:00 | Welcome |
| 09:15 | Speaker: Dr. Taylor Sparks, University of Utah. Title: TBD |
| 09:30 | Speaker: Dr. Martin Fitzner, Merck KGaA. Title: Industrial view on BO – a perfect match for the low- to no-data regime |
| 09:45 | Speaker: Max Balandat, Meta Adaptive Experimentation. Talk: TBD |
| 10:00 | Orientation |
| 10:10 | Breakout |
| 13:00 | End of Day 1 |

### Day 2: Mar 28

| Time  | Activity |
|-------|----------|
| 09:00 | Welcome |
| 09:10 | Breakout |
| 12:00 | Project showcase and judging |
| 12:50 | Closing remarks and takeaways |
| 13:00 | End of Day 2 |

### Mar 29

[Submissions](_/../submission.md) due by {{ site.submissions_due }}.

Prizes to be announced March 29 at 1:00 PM Eastern Time (ET).

### Post-hackathon

Preparation of scholarly article.[<sup>(?)</sup>][faq]{:title="What is required for me to participate in the scholarly article?"}


[faq]: {{ site.baseurl }}{% link faq.md %}

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
