---
layout: project_list
title: Hackathon projects
menu_title: Projects
menu_icon: briefcase
---

Start by reviewing the topics below.

## Topics

While a list of topics is provided, we are open to new ideas. If you have a project in mind that doesn't fit into one of the topics below, you are welcome and encouraged to submit a project proposal for it.

### Applying Algorithms to Benchmark Tasks

We will provide a set of benchmark tasks and instructions, and your job will be to choose a package or algorithm and apply it to task(s) of your choice. The tasks will cover a broad range of both optimization complexity and application domains.

#### Benchmark Tasks

We are still refining the list of benchmark tasks. Please contact us if you have suggestions for existing optimization benchmark datasets or tasks that you would like to see included.

##### Domain

- [Analytical functions]()
- [Molecule Optimization]()
- [Materials Optimization]()

##### Optimization features

- [Multi-fidelity Optimization]()
- [Constrained Optimization]()
- [Multi-objective Optimization]()
- [Real-world noise]()

#### Judging Criteria

### Developing New Benchmarks

Ideally, these tasks will be representative of real-world problems in chemistry and materials science. While remotely accessible automated experiments would be the gold standard, the more pragmatic benchmark tasks typically include surrogate modeling. The new benchmark tasks should lean towards real-world conditions in terms of optimization problem type (objectives, fidelities, constraints) and/or relevance towards chemistry and materials applications (e.g., molecules, materials, reactions, etc.).

#### Judging Criteria

### Creating Instructional Tutorials

We will provide a set of topics in Bayesian optimization, and your job will be to create a tutorial that introduces the topic conceptually and provides a hands-on example. These are meant to be "gentle introduction" tutorials which assume beginner Python knowledge and Bayesian optimization knowledge (see [resources](_/../resources.md) for more details).

#### Judging Criteria

### Real-world Chemistry and Materials Tasks

The hackathon is also open to proposals for real-world optimization tasks in chemistry and materials science. This will involve providing beginner-friendly background knowledge on the impact of the application, existing solutions, and the science behind it. It will also involve providing rigorous details around the optimization problem, including search space (tunable parameters + constraints), objectives, experimental equipment, reagants, and standard operating procedures. These should be well-defined problems that *can* and *should* be tackled with Bayesian optimization, but have not yet.

## Project initialization

As a teamleader, to initialize your project(s)[<sup>(?)</sup>][faq]{:title="Can I participate in multiple projects?"}, please follow these steps:
1. Accept the GitHub Classroom invitation to a topic above
2. Create a new file in a fork of the hackathon repository named `project-<your-team-name>.md`. For example, if your team name is "Bayes Bandits", the file should be named `project-bayes-bandits.md`.
3. Copy the following contents into the file and fill in the corresponding details. Replace `<your-repo-name>` wit the GitHub repository that was created by GitHub Classroom for you. For example, if your team name is "Bayes Bandits", the repository will be named `bayes-bandits`, and the `github` field should be `AC-BO-Hackathon/bayes-bandits`.

```markdown
---
number: 1 <!-- leave as-is, maintainers will adjust -->
title: Project 1 title
pis:
  - Project lead 1 (Institution 1)
  - Project lead 2 (Institution 2)

# Comment these lines to hide these elements
contributors:
  - Contributor 1 (Institution 1)
  - Contributor 2 (Institution 2)
github: AC-BO-Hackathon/<your-repo-name>
<!-- youtube_video: lIanN0DI9R8 -->
---

Project 1 description

- References here
- ...
```

[faq]: {{ site.baseurl }}{% link faq.md %}