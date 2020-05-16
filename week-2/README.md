# Incremental Development

[<< Week 1](../week-1/README.md) | [Main Page](../README.md) | [Week 3 >>](../week-3/README.md)

## Week 2

- [Learning Objectives](#learning-objectives)
- [Prep Work](#prep-work)
- [Lesson Plan](#lesson-plan)
  - [Isolate](#isolate)
  - [Integrate](#integrate)
- [Assignments](#assignments)
  - [Suggested Study](#suggested-study)
  - [Exercises](#exercises)
  - [Project](#project)

---
---

## Learning Objectives

- Collaborating on one repository
- Using GitHub pull requests
- Assigning collaborators for code review

---
---

## Prep Work

> First things first:
> - [Review the Weekly Assignments guide](https://home.hackyourfuture.be/students/weekly-assignments)
> - [Create your Homework Issue](https://home.hackyourfuture.be/students/homework-submission#homework-issues)

### Collaborating on GitHub

- [Pull Requests](https://www.youtube.com/watch?v=2M16faxEQsg)
- Git & GitHub for Poets: [pull request & merge](https://www.youtube.com/watch?v=_NrSWLQsDL4&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV&t=0s), [resolving conflicts](https://www.youtube.com/watch?v=JtIX3HJKwfo)
- The Net Ninja: [11](https://www.youtube.com/watch?v=MnUd31TvBoU&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR&index=11), [12](https://www.youtube.com/watch?v=MnUd31TvBoU&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR&index=12)
- Pull Request Reviews: [about them](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-request-reviews), [requesting one](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)

---
---

## Lesson Plan

<!-- > [Lesson Plan Slides](https://hackyourfuture.be/incremental-development/week-2) -->

Incrementally develop a simple responsive web page.

### Isolate

Step-by-step collaboration practice for two people on one repository.  Split into pairs within your group and follow these steps:

- [Git Workflow for Two](https://github.com/foundersandcoders/git-workflow-workshop-for-two)

### Integrate

Revisit the project you built last week, but with collaboration!

1. In groups of 2-3, choose one team member to be the main repository owner.  They will generate a new repo from the [w3-validation-starter](https://github.com/hackyourfuturebelgium/w3-validation-starter) & copy-paste [this development strategy](../integrate/development-strategy-collaborative.md) and [this wireframe](../integrate/wireframe.gif)) into the new repo.
1. Divide the different development steps between team members and fill in their names on the copied `development-strategy` file.  Using the same workflow as before break, build a website to match the wireframe in your shared repository.
1. Return to your small group and discuss.
    - What went well? What was challenging?
    - What conflicts did you have? How did you resolve them?
    - Was it clear _exactly_ what code you needed to write?
    - Was it clear _exactly_ what code your team mates needed to write?

---
---

## Assignments

### Suggested Study

#### Git & GitHub

- [git & github for poets](https://www.youtube.com/watch?v=BCQHnlnPusY&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)
- [git-it](https://github.com/jlord/git-it-electron/)

#### HTML & CSS

- [study.hackyourfuture.be/html-css/html#responsive-design](https://study.hackyourfuture.be/html-css/html#responsive-design)
- [CSS Games](https://study.hackyourfuture.be/html-css/css#games-to-learn-css)
- FCC, Responsive Web Design: [exercises](https://www.freecodecamp.org/learn), [video](https://www.youtube.com/watch?v=srvUrASNj0s)
- [mmtuts: HTML & CSS](https://www.youtube.com/watch?v=TKYsuU86-DQ&list=PL0eyrZgxdwhwNC5ppZo_dYGVjerQY3xYU)

---

### Exercises

- :egg: [html-css-git-exercises](https://github.com/hackyourfuturebelgium/html-css-git-exercises) - Week 2
  - Complete the exercises in `week-2`
  - Push your work regularly to GitHub
- :hatching_chick: [HTML-CSS-Practice-Problems](https://github.com/DevMountain/HTML-CSS-Practice-Problems)
- :hatching_chick: [css-exercises](https://github.com/dangodev/css-exercises)

---

### Project

#### `app-theme`

> [Code-Along](http://hackyourfuture.be/homework-submission/#projects)

This week's project is to study the __app-theme__ tutorial from Traversy Media.

Writing the same code as Mr. Traversy's code is not enough!  You are expected to submit your code from his tutorial in a new repository [generated](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/) from [this starter template](https://github.com/HackYourFutureBelgium/w3-validation-template).  Your repository should be named `app-theme` and should be cleanly developed with one branch per step.  It's up to you to write the development strategy!

You will be assessed not only on your live demo, but also on the quality of your code, the correctness of your branches, and the completeness of your repository. Your repository must contain:

- A README describing your project in detail.  Check out these articles to learn more about writing good README's: [makeareadme.com](https://www.makeareadme.com/), [bulldogjob](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project), [meakaakka](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3)
- One well-named branch per user story. If we check out any branch, it should contain _only_ the code necessary to make that step work. and it should work!
- A file called `development-strategy.md` in which you explain how you broke the project into user stories, describe each user story, and describe what code you wrote to implement this user story.

There are two general paths you can take to get this finished repo, neither is better or worse.  And if you find another way go for it!

- __Two-Stepping__: First - follow the tutorial studying the code and understanding the project.  Second - go through the tutorial another time, this time around focusing on using branches to create a finished repository.
- __One-Stepping__: Follow the tutorial once more slowly, carefully building your finished repository as you go.
