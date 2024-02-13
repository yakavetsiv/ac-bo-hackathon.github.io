---
title: Hackathon registration
menu_title: Registration
menu_icon: clipboard-check
event_status:
 - soon
---

{:.lead}
Participation is FREE and open. We can't wait to see what you build!

{% if site.registration_status == "soon" or site.registration_status == "demo" %}
Registration opens on {{ site.registration_opens_date }}.
{% endif %}
The closing date for applications is {{ site.registration_closes_date }}.

<div class="aside" markdown="1">
This virtual event will require some commitment prior to and including the
Hackathon Event which will take part from {{ site.event_date }}.

{% if site.registration_status == "soon" or site.registration_status == "demo" %}
  <a class="btn disabled">Registration opens soon</a>
{% endif %}
{% if site.registration_status == "open" or site.registration_status == "demo" %}
  [Register now](https://www.eventbrite.ca/e/837748407037){:.btn target="_blank"}
{% endif %}
{% if site.registration_status == "closed" or site.registration_status == "demo" %}
  <a class="btn disabled">Registration has closed</a>
{% endif %}

The closing date for applications is {{ site.registration_closes_date }}.
</div>

The hackathon is open to everyone, regardless of background or experience. To ensure a smooth and enjoyable experience, please see the [<sup>(?)</sup>][faq]{:title="Am I eligible to participate in the hackathon?"}.
Prior to the hackathon, this event will require that you think about the packages, algorithms, and benchmark tasks you will use or develop. You may choose to either work solo or form a team. During the hackathon, the organizers will be available to support you. After the hackathon, if you choose, you can contribute to the scholarly article[<sup>(?)</sup>][faq]{:title="What is required for me to participate in the scholarly article?"}.
