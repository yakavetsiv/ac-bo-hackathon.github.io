---
title: Hackathon registration
menu_title: Registration
menu_icon: clipboard-check
event_status:
 - soon
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


{:.lead}
Participation is FREE and open. We can't wait to see what you build!

{% if registration_status == "soon" or registration_status == "demo" %}
Registration opens on {{ site.registration_opens_date }}.
{% endif %}
The closing date for applications is {{ site.registration_closes_date }}.

<div class="aside" markdown="1">
This virtual event will require some commitment prior to and including the
hackathon event which will take part from {{ site.event_date }}.

{% if registration_status == "soon" or registration_status == "demo" %}
  <a class="btn disabled">Registration opens soon</a>
{% endif %}
{% if registration_status == "open" or registration_status == "demo" %}
  [Register now](https://www.eventbrite.ca/e/bo-hackathon-for-chemistry-and-materials-tickets-837748407037){:.btn target="_blank"}
{% endif %}
{% if registration_status == "closed" or registration_status == "demo" %}
  <a class="btn disabled">Registration has closed</a>
{% endif %}

The closing date for applications is {{ site.registration_closes_date }}.
</div>

The hackathon is open to everyone, regardless of background or experience; however, we recommend prior programming experience[<sup>(?)</sup>][faq]{:title="Am I eligible to participate in the hackathon?"}. Prior to the hackathon, this event will require that you think about the packages, algorithms, and benchmark tasks you will use or develop. You may choose to either work solo or form a team. During the hackathon, the organizers will be available to support you. After the hackathon, if you choose, you can contribute to the scholarly article[<sup>(?)</sup>][faq]{:title="What is required for me to participate in the scholarly article?"}.
