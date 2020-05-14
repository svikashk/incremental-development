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

- Creating responsive designs
- Using Pull Requests for collaboration

---
---

## Prep Work

### Git & GitHub

- [Pull Requests](https://www.youtube.com/watch?v=2M16faxEQsg)
- [Git & GitHub for Poets](https://www.youtube.com/watch?v=_NrSWLQsDL4&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV&t=0s)
- The Net Ninja: [11](https://www.youtube.com/watch?v=MnUd31TvBoU&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR&index=11), [12](https://www.youtube.com/watch?v=MnUd31TvBoU&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR&index=12)

---
---

## Lesson Plan

> [Lesson Plan Slides](https://hackyourfuture.be/incremental-development/week-2)

Incrementally develop a simple responsive web page.

### Isolate

Step-by-step collaboration practice:

- [Git Workflow for Two](https://github.com/foundersandcoders/git-workflow-workshop-for-two) (main exercise)
- [Pull Request & Merge](https://github.com/HackYourFutureBelgium/git-github-practice/blob/master/pull-request-and-merge.md) (extra exercise)

### Integrate

Revisit the project you built last week, but with collaboration!

In groups of ~3, choose one team member to be the main repository owner.  They will generate a new repo from the [w3-validation-starter](https://github.com/hackyourfuturebelgium/w3-validation-starter) & copy-paste [this development strategy](./development-strategy.md) and [this wireframe](./wireframe.gif)) into the new repo.

Next, divide the different user stories between team members and fill in their names on the copied `development-strategy` file.  Team members will now fork the main group repository.  Each member will now work independently on their own fork to develop their user story, sending a pull request to the main repo when they have finished.

After everyone has sent their pull requests, get back together and review each pull request together.  Did you have many conflicts? Were you able to resolve the conflicts into a working web page?

---
---

## Assignments

### Suggested Study

#### Git & GitHub

- [git & github for poets](https://www.youtube.com/watch?v=BCQHnlnPusY&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)
- [git-it](https://github.com/jlord/git-it-electron/)

#### HTML & CSS

- [What is Responsive Design?](https://www.youtube.com/watch?v=5KGah8bW8GE)
- [CSS Games](https://study.hackyourfuture.be/html-css/css#games-to-learn-css)
- FCC, Responsive Web Design: [exercises](https://www.freecodecamp.org/learn/responsive-web-design), [video](https://www.youtube.com/watch?v=srvUrASNj0s)
- [mmtuts: HTML & CSS](https://www.youtube.com/watch?v=TKYsuU86-DQ&list=PL0eyrZgxdwhwNC5ppZo_dYGVjerQY3xYU)

---

### Exercises

- :egg: [html-css-git-exercises](https://github.com/CodeYourFuture/html-css-git-exercises) - Week 2
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
- A file called `development-strategy.md` in which you explain how you broke the project into user stories, describe each user story, and describe what code you wrote to implement this user story.  Check out the [tomato timer code-along](https://github.com/HackYourFutureBelgium/tomato-timer-code-along/blob/master/development-strategy.md) for an example.

There are two general paths you can take to get this finished repo, neither is better or worse.  And if you find another way go for it!

- __Two-Stepping__: First - follow the tutorial studying the code and understanding the project.  Second - go through the tutorial another time, this time around focusing on using branches to create a finished repository.
- __One-Stepping__: Follow the tutorial once more slowly, carefully building your finished repository as you go.
