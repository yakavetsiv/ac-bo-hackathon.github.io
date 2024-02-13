---
layout: page
title: BO Hackathon for Chemistry and Materials
menu_title: Home
menu_icon: house-door
---

{:.secondary}
# {{ site.event_date }}, in association with the Acceleration Consortium

<div class="aside">
    <h2><i class="bi bi-calendar3"></i> Event timeline</h2>
    <dl>
        {% if site.registration_status == "soon" or site.registration_status == "open" or site.registration_status == "demo" %}
            <dt>{{ site.registration_opens_date }}</dt>
            <dd>
                Applications open for participants<br>
                {% if site.registration_status == 'open' %}
                    <a href="{{ site.baseurl }}{% link registration.md %}" class="btn">Register now</a>
                {% elsif site.registration_status == 'closed' %}
                    <a class="btn disabled">Registration has closed</a>
                {% elsif site.registration_status == 'soon' %}
                    <a class="btn disabled">Registration opens soon</a>
                {% endif %}
            </dd>
        {% endif %}

        <dt>{{ site.registration_closes_date }}</dt>
        <dd>Applications close</dd>

        <dt>{{ site.event_date }}</dt>
        <dd>Hackathon date</dd>
    </dl>
</div>

{% if site.event_status != "over" %}

With the emergence of new [Bayesian optimization](https://chat.openai.com/share/ac610758-2ac8-4b38-8dd5-25e6c46ad2a6) tools applied or geared towards the physical sciences, it is important to understand their strengths and weaknesses relative to the state of the art. In this hackathon, we will put these tools to the test! Scientists from the Acceleration Consortium @ University of Toronto and Merck KGaA are hosting a 2-day hackathon on
{{ site.event_date }}, open to researchers, to select or develop Bayesian optimization algorithms and apply them to benchmarking tasks. After the hackathon, results will be collated and presented in a scholarly article.[<sup>(?)</sup>][faq]{:title="What is required for me to participate in the scholarly article?"} Come join us to explore, collaborate, innovate, and contribute to the advancement of Bayesian optimization for the physical sciences.

Researchers can sign up to [topics ranging from]({{ site.baseurl }}{% link projects.md %})
application of algorithms to development of new benchmark tasks, and creating instructional tutorials. [This opportunity]({{ site.baseurl }}{% link registration.md %})
is open to researchers at all levels who are interested in applying Bayesian optimization[<sup>(?)</sup>][faq]{:title="Are algorithms other than Bayesian optimization allowed?"} for accelerated discovery in chemistry and materials science. At minimum, we recommend beginner-to-intermediate Python programming experience and basic familiarity with git and GitHub.[<sup>(?)</sup>][faq]{:title="What are the recommended prerequisites for participation?"}.

## Logistics

The event will take place virtually, using a combination of **video
conferencing** (Zoom) for meetings and seminars, and **discussion forums**
(Slack, Discord) for ongoing comms. 

## Outputs

By the end of the event, in addition to applying and developing algorithms, benchmarks, and tutorials, we hope you will have formed new connections, learned new skills, and been inspired with new ideas! We will also be working towards a scholarly article, and we hope you will be able to contribute to this effort.

[faq]: {{ site.baseurl }}{% link faq.md %}

{% else %}

With the completion of a 2-day virtual hackathon hosted by scientists from the Acceleration Consortium @ University of Toronto and Merck KGaA on {{ site.event_date }}, we thank participants for exploring, collaborating, innovating, and contributing to the advancement of Bayesian optimization for the physical sciences.

During the hackathon, researchers had the opportunity to select or develop Bayesian optimization algorithms and apply them to benchmarking tasks. The results of this collaborative effort will be collated and presented in a scholarly article.

Although the event has concluded, the outputs from the hackathon, including applied and developed algorithms, benchmarks, and tutorials, will continue to serve as valuable resources for the research community. Outputs from all teams have been made publicly available at https://github.com/AC-BO-Hackathon. We believe that through this event, new connections have been formed, new skills have been acquired, and new ideas have been inspired.

We want to express our gratitude to all the participants for their contributions, and we look forward to future collaborations in advancing Bayesian optimization in chemistry and materials science.

[faq]: {{ site.baseurl }}{% link faq.md %}

## Prize Winners

We'd like to congratulate the following teams for their outstanding contributions to the hackathon:

```{todo}
- **Best Overall**: Team 1 (500 CAD awarded)
- **Best Benchmark**: Team 2 (200 CAD awarded)
- **Best Algorithm**: Team 3 (200 CAD awarded)
- **Best Tutorial**: Team 4 (200 CAD awarded)
- **Best Presentation**: Team 5 (100 CAD awarded)
- **Best Collaboration**: Team 6 (100 CAD awarded)
- **Best Newcomers**: Team 7 (100 CAD awarded)
- **Best Team Name**: Team 8 (50 CAD awarded)
- **Best Team Spirit**: Team 9 (50 CAD awarded)
```

{% endif %}

## Sponsors 

- [The Acceleration Consortium @ University of Toronto](https://acceleration.utoronto.ca/)
- [Merck KGaA](https://www.emdgroup.com/en)

<footer class="lead">
*The progress of a scientific field is both tracked and propelled through robust benchmarks.*
</footer>