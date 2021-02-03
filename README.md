# Incremental Development

[<< Precourse](https://github.com/hackyourfuturebelgium/precourse) | [Home](https://home.hackyourfuture.be) | [UX/UI Design >>](https://github.com/ux-ui-design)

---

> "Nearly all Agile teams favor an incremental development strategy;
> in an Agile context, this means that each successive version of the product is usable,
> and each builds upon the previous version by adding user-visible functionality."
>
> - [agile alliance](https://www.agilealliance.org/glossary/incremental-development)

_Incremental Development_ is a strategy for developing software. In this strategy you start with the simplest code you can possibly write to get things started. Often this is just empty files with the right names, in the right folders! Then in small steps you add more code so that each little step _works_, builds on top of the last step, and is a little closer to the end goal.

This strategy is sooooo important to learn because **programming is hard**. All developers (even your coaches!) make mistakes all the time. The best way to manage mistakes is to work in small, understandable steps and making sure that each step works before moving on.

Incremental Development is more about discipline than talent. Every minute you spend practicing this now will save you hours of debugging and make collaboration a breeze!

### Contents

- [Module Projects](#module-projects)
- [Learning Objectives](#learning-objectives)
- [Suggested Study](#suggested-study)
- Weekly Details:
  - [Week 1](#week-1)
  - [Week 2](#week-2)
- [Class Recordings](#class-recordings)

---

## Module Projects

Projects in Incremental Development will all have a `development-strategy.md` and be developed collaboratively.

<details>
<summary>expand/collapse</summary>
<br>

In the first weeks it's likely that you'll spend as much time figuring out how to publish and turn in your projects as you will spend building them. _This is totally normal and OK!_ Working like a developer takes time and practice to get good at, and at this point in your learning it's even more important than mastering HTML & CSS!

So on days when you find yourself spending a couple hours struggling with branches, trying to push your homework or create an issue, remind yourself that it's all time well spent. Mastering these skills _now_ will free your time _later_ to focus on studying the more interesting and challenging skills in this course.

Developing a working web site is not enough! You will be expected to submit a development strategy and complete repository, cleanly developed with one branch per step. The goal of these projects is to practice planning and building clean projects in a structured way. The goal of these projects _is not_ to build the fanciest most beautiful website, to use all the latest CSS tricks, or to use cool libraries.

Your repository will also need a README file explaining your project to new users. You will be assessed not only on your working website, but also on the quality of your code, the correctness of your branches, and the completeness of your README.

Here's a short list of do's and don'ts that can help you stay on track:

### Do

- ... pay as much attention to your branches & repository as your code
- ... completely finish one step of the project before moving on to the next
- ... be very careful about your CSS classes, selectors and id's
- ... properly format your code
- ... find the simplest solution to each step of the project

### Don't

- ... think that your site can be pretty enough to make up for messy code
- ... make any steps of your project do less _or more_ than is described in the strategy
- ... move on to the next step before the previous one is finished

</details>
<br>

[TOP](#incremental-development)

---

## Learning Objectives

Skills and concepts you will learn in this module

<details>
<summary>expand/collapse</summary>

### Incremental Development

- Breaking large web-sites into small, manageable steps
- Reading and writing `development-strategy.md` files

### Git

- Pulling & pushing specific branches
- Atomic commits with meaningful messages
- Branching and merging

### GitHub

- Using Pull Requests for code review
- Using Project Boards to track projects
- Using Issues to organize and discuss tasks

### Command Line Interface

- Navigating directories: `cd`, `ls`, `pwd`
- Creating & removing files and directories

### Visual Studio Code

- Using plugins for efficient development
- Using linters & code formatters (plugins)
- Using the integrated terminal

### DOM: Basic Life-cycle

1. **Source Code**: HTML & CSS files you edit in VSC
1. **Document Object Model**: What you see in the DevTools inspector
1. **Rendered Page**: What you see in the main browser window

### Browser DevTools

- Finding the source for a website
- Inspecting a specific DOM Element
- Replicating styles and layout

### HTML & CSS

- Use clear and consistent code formatting
- Meaningful names for classes & id's
- Correct usage of CSS selectors
- Responsive, mobile first development
- Accessible Rich Internet Applications (ARIA)

</details>
<br>

[TOP](#incremental-development)

---

## Suggested Study

> [hackyourfuture.github.io/study](https://hackyourfuture.github.io/study)

References, Tutorials and exercises to help you through this module

<details>
<summary>expand/collapse</summary>
<br>

> https://htmlpreview.github.io/ - see a live demo of any branch

### Incremental Development

- [What is this?](https://www.youtube.com/watch?v=GzzkpAOxHXs)
- [Agile Development by Cartoon](https://www.youtube.com/watch?v=Z9QbYZh1YXY&list=PLBUu5aGDLKnbeEx8U-5r436bw6p9wv1rS)
- [Atlassian](https://www.atlassian.com/team-playbook/plays), [Team Playbook](https://www.atlassian.com/team-playbook/plays)
- [Splitting User Stories](https://www.youtube.com/watch?v=EDT0HMtDwYI)
- [Three key parts](https://www.youtube.com/watch?v=ctFzjMygaRo)
- [`development-strategy.md` files](https://home.hackyourfuture.be/students/development-strategy)
- [example development strategies](./development-strategies)
- [example group repo](https://github.com/HackYourFutureBelgium/team-branchies)
- All About Trees: [in steps](./all-about-trees-stepped), [as a repo](https://github.com/hackyourfuturebelgium/built-with-branches)

### Git & GitHub

- [learngitbranching](https://learngitbranching.js.org)
- [git & github for poets](https://www.youtube.com/watch?v=BCQHnlnPusY&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)
- lab.github.com:
  - [First Day on GitHub](https://lab.github.com/githubtraining/first-day-on-github)
  - [First Week on GitHub](https://lab.github.com/githubtraining/first-week-on-github)
- [The Net Ninja](https://www.youtube.com/watch?v=QV0kVNvkMxc&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR&index=8)
- [git-it](https://github.com/jlord/git-it-electron/)
- [Understand how to use Atomic Commits](https://curiousprogrammer.io/blog/how-to-craft-your-changes-into-small-atomic-commits-using-git)

### Command Line Interface

- [Jesse Showalter](https://www.youtube.com/watch?v=5XgBd6rjuDQ)
- CLI games:
  - [bashcrawl](https://gitlab.com/slackermedia/bashcrawl/) - clone & play
  - [Terminus](https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html) - online
  - [iTerm](https://sr6033.github.io/lterm/) - online
- [A huge cheat sheet](https://gist.github.com/LeCoupa/122b12050f5fb267e75f)
- [study.hyf.be](https://study.hackyourfuture.be/cli)

### Writing READMEs

- [makeareadme.com](https://www.makeareadme.com/)
- [bulldogjob](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
- [meakaakka](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3)

### DevTools and the DOM

- [How to inspect an element](https://www.lifewire.com/get-inspect-element-tool-for-browser-756549)
- [inspecting-the-dom](https://hackyourfuturebelgium.github.io/inspecting-the-dom/)
- [Modify the DOM. (does the source change?)](https://zapier.com/blog/inspect-element-tutorial/)

### HTML & CSS

- FCC, Responsive Web Design: [exercises](https://www.freecodecamp.org/learn), [video](https://www.youtube.com/watch?v=srvUrASNj0s)
- [mmtuts: HTML & CSS](https://www.youtube.com/watch?v=TKYsuU86-DQ&list=PL0eyrZgxdwhwNC5ppZo_dYGVjerQY3xYU)
- [CSS Games](https://study.hackyourfuture.be/html-css/css#games-to-learn-css)
- :egg: [html-css-git-exercises](https://github.com/hackyourfuturebelgium/html-css-git-exercises)
- :hatching_chick: [HTML-CSS-Practice-Problems](https://github.com/DevMountain/HTML-CSS-Practice-Problems)
- :hatched_chick: [css-exercises](https://github.com/dangodev/css-exercises)

### Collaborating on GitHub

- [about code reviews](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-request-reviews)
- [requesting a code review](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)
- [Git Workflow for 2](https://github.com/hackyourfuturebelgium/git-workflow-workshop-for-two)
- [Pull Requests](https://www.youtube.com/watch?v=2M16faxEQsg)
- Git & GitHub for Poets: [pull request & merge](https://www.youtube.com/watch?v=_NrSWLQsDL4&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV&t=0s), [resolving conflicts](https://www.youtube.com/watch?v=JtIX3HJKwfo)
- The Net Ninja: [11](https://www.youtube.com/watch?v=MnUd31TvBoU&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR&index=11)
- linking PRs to Issues: [reference 1](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue), [reference 2](https://help.github.com/articles/autolinked-references-and-urls/)
- [closing Issues using keywords](https://help.github.com/en/enterprise/2.16/user/github/managing-your-work-on-github/closing-issues-using-keywords)

### User Stories

- [User Stories](https://www.youtube.com/watch?v=apOvF9NVguA)
- Acceptance Criteria
  - [Yodiz](https://www.yodiz.com/blog/user-stories-acceptance-definition-and-criteria-in-agile-methodologies/)
  - [Zepel](https://zepel.io/agile/acceptance-criteria-for-user-stories/)
  - [Ruby Garage](https://rubygarage.org/blog/clear-acceptance-criteria-and-why-its-important)
  - [The Infinity Project](https://www.youtube.com/watch?v=KYS0ptJ4JWc)
- Setting Priorities
  - [Many Strategies](https://zapier.com/blog/how-to-prioritize)
  - The Priority Quadrant
    - [The Quadrant](https://www.youtube.com/watch?v=NGvsxPOmWuw)
    - [Problems with this method](https://www.linkedin.com/pulse/why-prioritization-impacteffort-doesnt-work-itamar-gilad)
  - Other Perspectives
    - [Alex Ponomarev](https://medium.com/swlh/prioritizing-user-stories-in-agile-projects-d1dd8dd79165)
    - [Michael Lant](https://michaellant.com/2010/05/21/how-to-easily-prioritize-your-agile-stories/)

</details>
<br>

[TOP](#incremental-development)

---

## Week 1

This week will be a crash-course on how to plan, organize, and develop a software project. You will work individually to reverse-engineer a website, with finished code as a starting point.

<details>
<summary>expand/collapse</summary>

### Before Class

> Do you have any questions from last week? Add the `question` label to an issue in your class repo so your coaches know what to review!

[Planning and Collaboration](./planning-and-collaboration): This is the most important prep work, take your time to understand it!

GitHub Features:

- [Git & GitHub for Poets](https://www.youtube.com/watch?v=BCQHnlnPusY&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV): 1.4
- GitHub
  - [Pull Requests](https://www.youtube.com/watch?v=2M16faxEQsg)
  - [Adding collaborators to a repository](https://www.youtube.com/watch?v=p49LRx3hYI8)
- Linking PRs to Issues
  - [reference 1](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue)
  - [reference 2](https://help.github.com/articles/autolinked-references-and-urls/)
  - [closing Issues using keywords](https://help.github.com/en/enterprise/2.16/user/github/managing-your-work-on-github/closing-issues-using-keywords)
- Code Review
  - [about code reviews](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-request-reviews)
  - [requesting a code review](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)

### During Class

In class you will practice the entire Planning and Collaboration workflow by building a new markdown ice-breaker repository with your group.

#### Before Break

Guided by a coach, each study group will complete steps 1-4 of the [Planning and Collaboration](#planning-and-collaborating) workflow:

1. Understand the Project
2. Prepare your repo for collaboration
3. Write a Development Strategy
   1. You can use the [ice-breaker-strategy.md](./development-strategies/ice-breaker-strategy.md) as a starting point
4. Prepare your repo for development

#### After Break

Guided by a coach, each study group will practice step 5 of [Planning and Collaboration](#planning-and-collaborating). You will each take turns sharing your screen and practicing the Claim, Branch, Review, Merge workflow.

- Did you get conflicts? which conflicts and how did you fix them?
- What was confusing or frustrating about Code Review?

It's more important that you take the time to understand _why_ this workflow is important than that you close all of your issues. Take all the time you need to ask questions of your coach and discuss what you are doing. Your group can always organize a study session to finish the repo during the week.

### After Class

> individual project

This week's project is to study the [**acme-web-design** tutorial from Traversy Media](https://www.youtube.com/watch?v=Wm6CUkswsNw).

Writing the same code as Mr. Traversy's code is not enough! You are expected to submit your code from his tutorial in a new repository on your GitHub account [generated](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/) from [this starter template](https://github.com/HackYourFutureBelgium/w3-validation-template). Your repository should be named `acme-web-designn` and should be cleanly developed with one branch per step. It's up to you to write the development strategy!

A good strategy to for completing this project is the **three-step**:

1. follow the tutorial studying the code and understanding the finished project.
2. study the finished code and break it down into steps, write your development strategy and prepare your repo.
   1. it's ok if your strategy is not the same as the tutorial's!
3. build the project again following the Claim, Branch, Review, Merge workflow. you can refer back to the tutorial as much as you need
   1. this week you can merge your own issues without code review because it is an individual project

### Issue Checklist

Copy-paste this checklist into a new project issue and move your issue to the project board, your issue should have:

- `individual` label
- `project` label
- `week-1` label
- `incremental-developement` milestone

```md
- [ ] [repo](https://github.com/_/_) (with a complete README)
- [ ] [live demo](https://_.github.io/_)
- [ ] [development strategy](https://github.com/_/_/tree/master/development-strategy.md)
- [ ] [project board w/ labeled & assigned issues](https://github.com/_/_/projects/1)
- [ ] [issues closed by PRs](https://github.com/_/_/issues)
- [ ] [one branch per step](https://github.com/_/_/network)
- [ ] [one closed PR per step](https://github.com/_/_/pulls)
```

</details>
<br>

[TOP](#incremental-development)

---

## Week 2

Work as a group to reverse-engineer a website, with finished code as a starting point.

<details>
<summary>expand/collapse</summary>

### Before Class

> Do you have any questions from last week? Add the `question` label to an issue in your class repo so your coaches know what to review!

This Sunday you will be practicing the Planning and Collaboration workflow on a simple HTML/CSS project. To prepare for class you can take a look through this directory:

- `./development-strategies/all-about-trees`

It contains the code you will be reverse-engineering in small groups and the strategy you will use as a starting point.

### During Class

#### Before Break

Guided by a coach, each study group will complete steps 1-4 of the [Planning and Collaboration](#planning-and-collaborating) workflow, this time on an HTML/CSS project:

1. Understand the Project
   - Study the finished code & wireframe in the `./development-strategies/all-about-trees` folder
   - Changes are welcome! This strategy and website are just a starting point
2. Prepare your repo for collaboration
3. Write a Development Strategy
   - You can use the Development Strategy from `./development-strategies/all-about-trees` as a starting point
4. Prepare your repo for development

#### After Break

Guided by a coach, each study group will practice step 5 of [Planning and Collaboration](#planning-and-collaborating) to begin developing your HTML/CSS group project. You will each take turns sharing your screen and practicing the Claim, Branch, Review, Merge workflow.

This is exactly what you will be doing for the week's project! It's more important that your group is ready to work together this week than that you complete the All About Trees project, you can always finish it over the week for extra practice.

### After Class

> group project

This week's project is to study the [**app-theme** tutorial from Traversy Media](https://www.youtube.com/watch?v=qlA7dputiNc).

Writing the same code as Mr. Traversy's code is not enough! You are expected to submit your code from his tutorial in a new repository on your GitHub account [generated](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/) from [this starter template](https://github.com/HackYourFutureBelgium/w3-validation-template). Your repository should be named `app-theme` and should be cleanly developed with one branch per step. It's up to you to write the development strategy!

> You will need to use [Font Awesome 4.7](https://fontawesome.com/v4.7.0/get-started/) in your project

A good strategy to for completing this project is the **four-step**:

1. _individually_: follow the tutorial, studying the code and understanding the finished project.
2. _individually_: study the finished code and break it down into steps, write your development strategy and prepare your repo.
   - it's ok if your strategy is not the same as the tutorial's!
3. _as a group_: compare development strategies and combine the best parts of each to create a group strategy
   - prepare your group repository for development
4. _as a group_: build the project again following the Claim, Branch, Review, Merge workflow. you can refer back to the tutorial as much as you need

### Issue Checklist

Copy-paste this checklist into a new project issue and move your issue to the project board, your issue should have:

- `group` label
- `project` label
- `week-1` label
- `incremental-developement` milestone

```md
- [ ] [repo](https://github.com/_/_) (with a complete README)
- [ ] [live demo](https://_.github.io/_)
- [ ] [development strategy](https://github.com/_/_/tree/master/development-strategy.md)
- [ ] [project board w/ labeled & assigned issues](https://github.com/_/_/projects/1)
- [ ] [issues closed by PRs](https://github.com/_/_/issues)
- [ ] [one branch per step](https://github.com/_/_/network)
- [ ] [one closed PR per step](https://github.com/_/_/pulls)
- [ ] [multiple contributors](https://github.com/_/_/contributors)
```

</details>
<br>

[TOP](#incremental-development)

---

## Week 3

Work as a group to reverse-engineer a website, with no code provided. You're on your own!

<details>
<summary>expand/collapse</summary>

### Before Class

> Do you have any questions from last week? Add the `question` label to an issue in your class repo so your coaches know what to review!

Nothing new! Come ready to discuss what went well and what didn't in last week's project.

### During Class

#### Before Break

Each group will take ~15 minutes presenting their project repository and discussing what went well and what was challenging.

#### After Break

After hearing about each group's experience, you and your coaches will decide the best way to spend the second half of class. It may be practicing in small groups, coding along with your coaches, or anything else!

### After Class

> group project

This week's group project is to build your own accessible & responsive clone of the [DuckDuckGo home page](https://duckduckgo.com/?va=z&t=hr) (long version). We don't expect your DOM to be identical to DuckDuckGo's, or for all the buttons to have the same behavior, but visually your site should be identical to the real DuckDuckGo. If you would like to use a CSS framework, go for it! Just be sure everyone in your team agrees ;)

Unlike the last two weeks, this project does not have a video tutorial for you to follow. This week you will also expected to do your best at writing _accessible_ HTML including correct Semantic HTML and ARIA. Pay special attention to points of user interaction like the search field and submit button.

You are expected to submit your code from his tutorial in a new repository [generated](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/) from [the w3-validation-starter repo](https://github.com/HackYourFutureBelgium/w3-validation-template). Your repository should be named `duck-duck-clone` and should be collaboratively developed following the same workflow you practiced in class this Sunday. It's up to you to write the development strategy!

A good strategy to for completing this project is the **four-step**:

1. _individually_: study the DuckDuckGo website. Try to find all the fonts, colors and assets they used.
2. _individually_: write a development strategy to reverse-engineer DuckDuckGo
3. _as a group_: compare development strategies and combine the best parts of each to create a group strategy
   - prepare your group repository for development
4. _as a group_: build the project again following the Claim, Branch, Review, Merge workflow. you can refer back to the tutorial as much as you need

### Issue Checklist

Copy-paste this checklist into a new project issue and move your issue to the project board, your issue should have:

- `group` label
- `project` label
- `week-1` label
- `incremental-developement` milestone

```md
- [ ] [repo](https://github.com/_/_) (with a complete README)
- [ ] [live demo](https://_.github.io/_)
- [ ] [development strategy](https://github.com/_/_/tree/master/development-strategy.md)
- [ ] [project board w/ labeled & assigned issues](https://github.com/_/_/projects/1)
- [ ] [issues closed by PRs](https://github.com/_/_/issues)
- [ ] [one branch per step](https://github.com/_/_/network)
- [ ] [one closed PR per step](https://github.com/_/_/pulls)
- [ ] [multiple contributors](https://github.com/_/_/contributors)
```

</details>
<br>

[TOP](#incremental-development)

---

# Class Recordings

> note for students: HYF modules are constantly being improved, recordings from past classes may not be the same as what you did on Sunday

- **Students**: Here you can find recordings of this module from past classes. Enjoy!
- **Coaches**: When sending your PR's with links please ...
  - Indicate which class you were teaching
  - Which week it was (if the module is more than 1 week)
  - Give your name
  - and a helpful description

## [Class 9 & 10](https://hackyourfuturebelgium.github.io/class-9-10)

> Stéphane, Tiago, Louise, Dirk, Kevin

- Week 1
  - [Part 1](https://vimeo.com/419992403) - Isolation
  - [Part 2](https://vimeo.com/419993111) - Integration
  - [Part 3](https://vimeo.com/419991575) - Homework explanation
- Week 2
  - [Part 1](https://vimeo.com/422148962) - Resolving Git Conflicts
  - [Part 2](https://vimeo.com/422149182) - Development Strategies
  - [Part 3](https://vimeo.com/422347127) - Homework explanation
- Week 3
  - [Part 1](https://vimeo.com/424498862) - :+1: Collaborating with Git & GitHub ...
  - [Part 2](https://vimeo.com/424519483) - ... continued & _fast forward_ vs _merge_ commits
  - [Part 3](https://vimeo.com/424525176) - Homework explanation

---

## [Class 11 & 12](https://github.com/hackyourfuturebelgium/class-11-12)

> Stéphane, Tiago, Marie, Unmesh, Nawang, Tamer

- Week 1
  - [Part 1 - before break](https://vimeo.com/462552602)
  - [Part 2 - before break](https://vimeo.com/462554201)
  - [Part 3 - after break](https://vimeo.com/462555843)
- Week 2
  - [Part 1](https://vimeo.com/465288009)
  - [Part 2](https://vimeo.com/465288632)
- Week 3
  - Collaboration Workflows: [part 1](https://vimeo.com/manage/467646196/general), [part 2](https://vimeo.com/manage/467646011/general)

---

## [Class 13 & 14](https://github.com/hackyourfuturebelgium/class-13-14)

[TOP](#incremental-development)
