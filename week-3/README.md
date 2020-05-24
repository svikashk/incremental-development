# Incremental Development

[<< Week 2](../week-2/README.md) | [Main Page](../README.md)

## Week 3

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

- Using GitHub Issues, Project Boards, and Pull Requests to manage your projects

---
---

## Prep Work

> First things first:
> - [Review the Weekly Assignments guide](https://home.hackyourfuture.be/students/weekly-assignments)
> - [Create your Homework Issue](https://home.hackyourfuture.be/students/homework-issues)

### GitHub Code Review

- [about them](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-request-reviews)
- [requesting one](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)

---
---

## Lesson Plan

<!-- > [Lesson Plan Slides](https://hackyourfuture.be/incremental-development/week-3) -->

Coordinate your collaboration with Issues, Project Boards & Pull Requests.  If you've submitted a homework assignment in the last few weeks this workflow should feel familiar :)

### Isolate

Build _another_ group intro repository (this is the last time, promise :).

This time you will be doing pair programming, taking turns to develop the next branch on your local machines following the collaboration workflow you learned last week.  Split your small group into pairs and begin:

1. Choose one of you to be the repository owner, they will:
    - Create a new repository
    - Create a new project board with four columns: "To Do", "In Progress", "Ready for Review", "Done"
    - Add your partner as a collaborator in your repository
1. Together as pair you should:
    - Write a development strategy & assign each step
    - Create one issue per step in the development strategy & assign the issue
    - Move all new issues to the "To Do" column of the project board
1. Develop the steps in your strategy file using [the same workflow as last week](https://github.com/hackyourfuturebelgium/git-workflow-workshop-for-two). For each step change who is driver and who is navigator. If you are the driver:
    - Move the correct issue into "In Progress"
    - Pull the most recent changes to your computer
    - Follow your navigator's instructions to write the next step
    - When you are finished, commit and push your branch
    - On GitHub, open a pull request to `master` from your new branch
    - Move your issue into "Ready for Review" & link your PR to your issue ([reference 1]](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue),  [reference 2](https://help.github.com/articles/autolinked-references-and-urls/))
    - Review the code as a pair then merge the changes to `master`
    - Move on to the next step!
1. When each pair has finished, return to your small groups and discuss:
    - What went well? What was challenging?
    - What conflicts did you have? How did you resolve them?
    - What was challenging about using only CLI? What was nice about it?

### Integrate

You will be building one last website matching the _semantic layout_ wireframe.  This time your entire small group will practice collaborating on one repository:

1. Choose one person to be repository owner, they will manage the team repo but will not write any code:
    - generate a new repository using the [w3-validation-template](https://github.com/hackyourfuturebelgium/w3-validation-template)
    - paste in [this development strategy](../integrate/development-strategy-collaborative.md) & fill out the details
    - paste in [the semantic wireframe](../integrate/wireframe.gif)
    - create a new project board with four columns: "To Do", "In Progress", "Ready for Review", "Done"
    - add your group members as collaborators in your repository
1. Repository Owner will create one issue for each step of the development strategy:
    - give each one a helpful title and description
    - assign each issue to a team member
1. Each team member develops their piece of the project following [the same workflow as last week](https://github.com/hackyourfuturebelgium/git-workflow-workshop-for-two) with one small change.  Instead of directly merging your pull request you will:
    - [link your PR to your issue](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue)
    - [request a review from your team's repo owner](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)
    - move your issue to "Ready for Review"
    - wait for the rest of your group to be "Ready for Review"
1. Once all the of the issues are in "Ready for Review", review and merge them as a team before merging:
    - are there any merge conflicts?
    - does each pull request contain _only_ the required code. No more, no less?
1. Finally, turn on GitHub pages and check the results!  Did your team manage to make a recognizable website?

---
---

## Assignments

### Suggested Study

### Collaboration

- [Code Review](https://study.hackyourfuture.be/collaborating/code-review)


### Web Accessibility

- [study.hackyourfuture.be](https://study.hackyourfuture.be/html-css/accessibility)

### CLI

- [Jesse Showalter](https://www.youtube.com/watch?v=5XgBd6rjuDQ)
- CLI games:
  - [bashcrawl](https://gitlab.com/slackermedia/bashcrawl/) - clone & play
  - [Terminus](https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html) - online
  - [iTerm](https://sr6033.github.io/lterm/) - online
- [A huge cheat sheet](https://gist.github.com/LeCoupa/122b12050f5fb267e75f)

---

### Exercises

- :egg: [html-css-git-exercises](https://github.com/hackyourfuturebelgium/html-css-git-exercises) - Week 3
  - Complete the exercises in `week-3`
  - Push your work regularly to GitHub
- :egg: [HTML-CSS-Practice-Problems](https://github.com/DevMountain/HTML-CSS-Practice-Problems)
- :hatching_chick: [css-exercises](https://github.com/dangodev/css-exercises)

---

### Project

#### `duck-duck-clone`

> [Open-Ended](http://hackyourfuture.be/homework-submission/#projects)

> Collaboration!  This project should be completed in groups of 2-3.

This week's project is to build your own accessible & responsive clone of the [DuckDuckGo home page](https://duckduckgo.com).  We don't expect your DOM to be identical to DuckDuckGo's, but the rendered site should be visually as close as possible. Unlike the last two weeks, this project does not have a video tutorial for you to follow. This week you will also expected to do your best at writing _accessible_ HTML including correct Semantic HTML and ARIA. Pay special attention to points of user interaction like the search field and submit button.

You are expected to submit your code from his tutorial in a new repository [generated](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/) from [the w3-validation-starter repo](https://github.com/HackYourFutureBelgium/w3-validation-template).  Your repository should be named `duck-duck-clone` and should be collaboratively developed following the same workflow you practiced in class this Sunday.  It's up to you to write the development strategy!

We will be checking for:

- A README describing your project in detail.  Check out these articles to learn more about writing good README's: [makeareadme.com](https://www.makeareadme.com/), [bulldogjob](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project), [meakaakka](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3)
- One well-named branch per user story. If we check out any branch, it should contain _only_ the code necessary to make that step work. and it should work!
- A file called `development-strategy.md` including how you broke the project into steps, what code you wrote for each step, and who was responsible for each step.
- A project board with one issue per step, each assigned to a team mate & linked to a pull request for review

> Please add one more check-box to your weekly homework issue for your project board.
