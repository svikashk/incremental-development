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

> before Sunday class:
> - [Review the Weekly Assignments guide](https://home.hackyourfuture.be/students/weekly-assignments)
> - [Create your Homework Issue](https://home.hackyourfuture.be/students/homework-issues)
> - this week's issue should have 17 check-boxes

### GitHub Code Review

- [about code reviews](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-request-reviews)
- [requesting a code review](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)
- linking PRs to Issues: [reference 1](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue),  [reference 2](https://help.github.com/articles/autolinked-references-and-urls/)
- [closing Issues using keywords](https://help.github.com/en/enterprise/2.16/user/github/managing-your-work-on-github/closing-issues-using-keywords)

---
---

## Lesson Plan

> during Sunday class
> - [Lesson Plan Slides](https://hackyourfuture.be/incremental-development/week-3)

Coordinate your collaboration with Issues, Project Boards & Pull Requests.  If you've submitted a homework assignment in the last few weeks this workflow should feel familiar :)

### Isolate

Build _another_ group intro repository (this is the last time, promise :).

This time you will be working as a group to develop a single team repo:

- [following this development strategy](../isolate/development-strategy-to-issues.md)
- [in a repo that looks like this](https://github.com/hackyourfuturebelgium/from-strategy-to-issues)

The group workflow will be like this:

1. Choose one of you to be the repository owner, they will complete _step 0_ of the development strategy.
    - When they have finished the group repo should look something like [this example repo](https://github.com/hackyourfuturebelgium/from-strategy-to-issues)
    - Your repo should have: a `development-strategy`, one issue per step, each issue assigned to someone, and a project board for the issues
1. Using the same workflow as last week, each member of the team will complete their assigned issues:
    - Move your issue into "In Progress"
    - Complete your task on a separate branch on your local machine
    - When you have checked all the boxes, push your branch to GitHub
    - Open a Pull Request and [request a review from your team mates](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)
    - link your PR to your issue ([reference 1](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue),  [reference 2](https://help.github.com/articles/autolinked-references-and-urls/))
    - Move your issue into "Ready for Review"
1. Once everyone has created their PRs, review each PR as a group
    - If changes need to be made, request the changes and move the issue to "Needs Revision"
    - If everything is OK: [close te Issue using keywords](https://help.github.com/en/enterprise/2.16/user/github/managing-your-work-on-github/closing-issues-using-keywords), and move the issue to "Done"
1. Discuss!
    - How was this process?
    - Did you get conflicts?  which conflicts and how did you fix them?

### Integrate

You will be building one last website matching the _semantic layout_ wireframe.  This time your entire small group will practice collaborating on one repository, exactly like in the _Isolate_ exercise just with HTML/CSS instead of Markdown:

- Create your group repo from the [w3-validation-template](https://github.com/hackyourfuturebelgium/w3-validation-template)
- Use the [complete development strategy](../integrate/complete-development-strategy.md) to guide your team's work

---
---

## Assignments

> after Sunday class

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

#### Checklist

```md
- [ ] [repo](https://github.com/user-name/project-name)
- [ ] [live](https://user-name.github.io/project-name)
- [ ] [development-strategy](https://github.com/user-name/project-name/tree/master/development-strategy.md)
- [ ] [One branch per step in `development-strategy.md`](https://github.com/user-name/repo-name/network)
- [ ] [One closed Issue per step in `development-strategy.md`](https://github.com/user-name/repo-name/issues?q=is%3Aissue+is%3Aclosed)
- [ ] [One closed PR per step in `development-strategy.md`](https://github.com/user-name/repo-name/pulls?q=is%3Apr+is%3Aclosed)
- [ ] [A project board](https://github.com/user-name/repo-name/projects/X) with all issues moved to "Done"
- [ ] A complete README
```

#### `duck-duck-clone`

> [Open-Ended](https://home.hackyourfuture.be/students/weekly-assignments#projects)

> Collaboration!  This project should be completed in groups of 2-3.

This week's project is to build your own accessible & responsive clone of the [DuckDuckGo home page](https://duckduckgo.com/?va=z&t=hr) (long version).  We don't expect your DOM to be identical to DuckDuckGo's, but the rendered site should be visually as close as possible.  If you would like to use a CSS framework, go for it! Just be sure everyone in your team uses it ;)

Unlike the last two weeks, this project does not have a video tutorial for you to follow. This week you will also expected to do your best at writing _accessible_ HTML including correct Semantic HTML and ARIA. Pay special attention to points of user interaction like the search field and submit button.

You are expected to submit your code from his tutorial in a new repository [generated](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/) from [the w3-validation-starter repo](https://github.com/HackYourFutureBelgium/w3-validation-template).  Your repository should be named `duck-duck-clone` and should be collaboratively developed following the same workflow you practiced in class this Sunday.  It's up to you to write the development strategy!

We will be checking for:

- A README describing your project in detail.  Check out these articles to learn more about writing good README's: [makeareadme.com](https://www.makeareadme.com/), [bulldogjob](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project), [meakaakka](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3)
- One well-named branch per user story. If we check out any branch, it should contain _only_ the code necessary to make that step work. and it should work!
- A file called `development-strategy.md` including how you broke the project into steps, what code you wrote for each step, and who was responsible for each step.
- A project board with one issue per step, each assigned to a team mate & linked to a pull request for review


