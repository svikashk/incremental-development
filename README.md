# Incremental Development

> "Nearly all Agile teams favor an incremental development strategy;
in an Agile context, this means that each successive version of the product is usable,
and each builds upon the previous version by adding user-visible functionality."
> - [agile alliance](https://www.agilealliance.org/glossary/incremental-development)

_Incremental Development_ is a strategy for developing software.  In this strategy you start with the simplest code you can possibly write to get things started.  Often this is just empty files with the right names, in the right folders! Then in small steps you add more code so that each little step _works_, builds on top of the last step, and is a little closer to the end goal.

This strategy is sooooo important to learn because **programming is hard**.  All developers (even your coaches!) make mistakes all the time.   The best way to manage mistakes is to work in small, understandable steps and making sure that each step works before moving on.

Incremental Development is more about discipline than talent. Every minute you spend practicing this now will save you hours of debugging and make collaboration a breeze!

### Contents

- [Module Projects](#module-projects)
- [Learning Objectives](#learning-objectives)
- [Suggested Study](#suggested-study)
- Weekly Details:
  - [Week 1](#week-1)
  - [Week 2](#week-2)
  - [Week 3](#week-3)
- [Class Recordings](#class-recordings)
- [study.hackyourfuture.be](https://study.hackyourfuture.be)
- [home.hackyourfuture.be](https://home.hackyourfuture.be/)

---

## Module Projects

In the first weeks it's likely that you'll spend as much time figuring out how to publish and turn in your projects as you will spend building them.  _This is totally normal and OK!_  Working like a developer takes time and practice to get good at, and at this point in your learning it's even more important than mastering HTML & CSS!

So on days when you find yourself spending a couple hours struggling with branches, trying to push your homework or create an issue, remind yourself that it's all time well spent. Mastering these skills _now_ will free your time _later_ to focus on studying the more interesting and challenging skills in this course.

Developing a working web site is not enough!  You will be expected to submit a development strategy and complete repository, cleanly developed with one branch per step. The goal of these projects is to practice planning and building clean projects in a structured way.  The goal of these projects _is not_ to build the fanciest most beautiful website, to use all the latest CSS tricks, or to use cool libraries.

Your repository will also need a README file explaining your project to new users.  You will be assessed not only on your working website, but also on the quality of your code, the correctness of your branches, and the completeness of your README.

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

[TOP](#incremental-development)

---

## Learning Objectives

Skills and concepts you will learn in this module

<details>
<summary>more info</summary>

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

1. __Source Code__: HTML & CSS files you edit in VSC
1. __Document Object Model__: What you see in the DevTools inspector
1. __Rendered Page__: What you see in the main browser window

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

[TOP](#incremental-development)

---

## Suggested Study

> [study.hackyourfuture.be](https://study.hackyourfuture.be)

References, Tutorials and exercises to help you through this module

<details>
<summary>more info</summary>

- Incremental Development
  - [What is this?](https://www.youtube.com/watch?v=GzzkpAOxHXs)
  - [Agile Development by Cartoon](https://www.youtube.com/watch?v=Z9QbYZh1YXY&list=PLBUu5aGDLKnbeEx8U-5r436bw6p9wv1rS)
  - [Atlassian](https://www.atlassian.com/team-playbook/plays), [Team Playbook](https://www.atlassian.com/team-playbook/plays)
  - [Splitting User Stories](https://www.youtube.com/watch?v=EDT0HMtDwYI)
  - [Three key parts](https://www.youtube.com/watch?v=ctFzjMygaRo)
  - [`development-strategy.md` files](https://home.hackyourfuture.be/students/development-strategy)
  - [example development strategies](./development-strategies)
  - [example group repo](https://github.com/HackYourFutureBelgium/team-branchies)
  - All About Trees: [in steps](./all-about-trees-stepped), [as a repo](https://github.com/hackyourfuturebelgium/built-with-branches)
- Git & GitHub
  - [learngitbranching](https://learngitbranching.js.org)
  - [git & github for poets](https://www.youtube.com/watch?v=BCQHnlnPusY&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV)
  - lab.github.com:
    - [First Day on GitHub](https://lab.github.com/githubtraining/first-day-on-github)
    - [First Week on GitHub](https://lab.github.com/githubtraining/first-week-on-github)
  - [The Net Ninja](https://www.youtube.com/watch?v=QV0kVNvkMxc&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR&index=8)
  - [git-it](https://github.com/jlord/git-it-electron/)
  - [Understand how to use Atomic Commits](https://curiousprogrammer.io/blog/how-to-craft-your-changes-into-small-atomic-commits-using-git)
- Command Line Interface
  - [Jesse Showalter](https://www.youtube.com/watch?v=5XgBd6rjuDQ)
  - CLI games:
    - [bashcrawl](https://gitlab.com/slackermedia/bashcrawl/) - clone & play
    - [Terminus](https://web.mit.edu/mprat/Public/web/Terminus/Web/main.html) - online
    - [iTerm](https://sr6033.github.io/lterm/) - online
  - [A huge cheat sheet](https://gist.github.com/LeCoupa/122b12050f5fb267e75f)
  - [study.hyf.be](https://study.hackyourfuture.be/cli)
- Wireframes
  - [What are these things?](https://www.youtube.com/results?search_query=what+are+wireframes)
  - [Why are these so great?](https://medium.com/@ray_vevaina/wireframing-a-front-end-developers-best-friend-c541df51ea65)
  - [wireframe.cc - online wireframes](https://wireframe.cc/)
- Writing READMEs
  - [makeareadme.com](https://www.makeareadme.com/)
  - [bulldogjob](https://bulldogjob.com/news/449-how-to-write-a-good-readme-for-your-github-project)
  - [meakaakka](https://medium.com/@meakaakka/a-beginners-guide-to-writing-a-kickass-readme-7ac01da88ab3)
- DevTools and the DOM
  - [How to inspect an element](https://www.lifewire.com/get-inspect-element-tool-for-browser-756549)
  - [inspecting-the-dom](https://hackyourfuture.be/inspecting-the-dom)
  - [Modify the DOM. (does the source change?)](https://zapier.com/blog/inspect-element-tutorial/)
- HTML & CSS
  - FCC, Responsive Web Design: [exercises](https://www.freecodecamp.org/learn), [video](https://www.youtube.com/watch?v=srvUrASNj0s)
  - [mmtuts: HTML & CSS](https://www.youtube.com/watch?v=TKYsuU86-DQ&list=PL0eyrZgxdwhwNC5ppZo_dYGVjerQY3xYU)
  - [CSS Games](https://study.hackyourfuture.be/html-css/css#games-to-learn-css)
  - :egg: [html-css-git-exercises](https://github.com/hackyourfuturebelgium/html-css-git-exercises)
  - :hatching_chick: [HTML-CSS-Practice-Problems](https://github.com/DevMountain/HTML-CSS-Practice-Problems)
  - :hatched_chick: [css-exercises](https://github.com/dangodev/css-exercises)
- Collaborating on GitHub
  - [about code reviews](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-request-reviews)
  - [requesting a code review](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)
  - [Git Workflow for 2](https://github.com/hackyourfuturebelgium/git-workflow-workshop-for-two)
  - [Pull Requests](https://www.youtube.com/watch?v=2M16faxEQsg)
  - Git & GitHub for Poets: [pull request & merge](https://www.youtube.com/watch?v=_NrSWLQsDL4&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV&t=0s), [resolving conflicts](https://www.youtube.com/watch?v=JtIX3HJKwfo)
  - The Net Ninja: [11](https://www.youtube.com/watch?v=MnUd31TvBoU&list=PL4cUxeGkcC9goXbgTDQ0n_4TBzOO0ocPR&index=11)
  - linking PRs to Issues: [reference 1](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue),  [reference 2](https://help.github.com/articles/autolinked-references-and-urls/)
  - [closing Issues using keywords](https://help.github.com/en/enterprise/2.16/user/github/managing-your-work-on-github/closing-issues-using-keywords)

</details>

[TOP](#incremental-development)

---

## Week 1

Learn a basic branching workflow:

0. set up your repository and clone it
1. write a development strategy
2. for each step
   1. create a new branch locally
   2. write your new code on that branch
   3. push the branch to your repository
   4. create a PR & merge the branch to `master`
   5. pull the new `master` branch to your computer
   6. continue to the next step

<details>
<summary>more info</summary>

### Prep Work

> before class

- Git
  - [Git & GitHub for Poets](https://www.youtube.com/watch?v=BCQHnlnPusY&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV): 1.1, 1.2, 1.3, 1.6 & 1.7
  - [learngitbranching](https://learngitbranching.js.org):
    - Main, Introduction Sequence: 1, 2, 3
    - Remotes, Pull & Push: 1 -> 6
  - [Understand how to use Atomic Commits](https://curiousprogrammer.io/blog/how-to-craft-your-changes-into-small-atomic-commits-using-git)
- Incremental Development
  - [`development-strategy.md` files](https://home.hackyourfuture.be/students/development-strategy)
  - [team branchies](https://github.com/HackYourFutureBelgium/team-branchies) (what you will build in class)

### Lesson Plan

> during class

**Before Break**

Build _another_ group intro repository?!  Your main focus this time will be understanding development strategies, and using git branches to turn the strategy into a reality.

While in your small groups each group member will create _their own_ repository.  You can help each other all you need to, but you will each need to work on a separate project. There is no need to use fork each other's repos.

By break time you should each have:

1. (GitHub) An empty repository
2. (your computer) A clone of your repository with:
   1. A development strategy ([a starter file](./development-strategies/1-individual-strategy.md))
   2. A main readme
   3. One branch per group member with an introduction file

**After Break**

Time to push and merge!  In this part of class you will practice pushing to GitHub, creating pull requests, and merging branches.  By the end of class each of you should be on your way to having something [like this repository](https://github.com/HackYourFutureBelgium/team-branchies).

No worries if you can't finish all at once.  You'll have the rest of the week to practice and finish ;)

### Project

> after class

This week's project is **_individual_**. You will study and reverse-engineer the [__acme-web-design__ tutorial from Traversy Media](https://www.youtube.com/watch?v=Wm6CUkswsNw).

Writing the same code as Mr. Traversy's code is not enough! You are expected to submit your code from his tutorial in a new repository on your GitHub account using [this starter repository](https://github.com/HackYourFutureBelgium/w3-validation-template).  Your repository should be named `acme-web-design` and should be cleanly developed with one branch per step.  It's up to you to decide what the steps are and in what order to build them.  When you have a plan for how to develop the site in steps you should write this into a development strategy!

Your workflow for this project should be the same workflow you practiced in class.  For each step in your development strategy you should develop on a new branch. After completing the code for one step (on one branch) you should push that branch to GitHub and merge to master using a Pull Request.

A good strategy to for completing this project is the __three-step__:

1. follow the tutorial studying the code and understanding the project.
2. look over your finished code and break it down into steps, write your development strategy.
3. study the tutorial a second time, following your strategy to build your repository one branch at a time

You will be assessed not only on your live demo, but also on the quality of your code, your development strategy, the correctness of your branches, and the completeness of your repository. Your repository must contain:

### Issue Checklist

Copy-paste this checklist into your individual issue to share your progress with coaches and classmates:

```md
- [ ] [repo](https://github.com/_/_) (with a complete README)
- [ ] [live demo](https://_.github.io/_)
- [ ] [development strategy](https://github.com/_/_/tree/master/development-strategy.md)
- [ ] [one branch per step](https://github.com/_/_/branches)
- [ ] [one closed PR per step](https://github.com/_/_/pulls)
```

</details>

[TOP](#incremental-development)

---

## Week 2

Learn to organize your progress with issues and a project board:

0. set up your repository and clone it
1. write a development strategy
2. set up a project board on your repo
3. create one issue per step, move them to the board
4. for each step
   1. move that issue into _in progress_
   2. create a new branch locally
   3. write your new code on that branch
   4. push the branch to your repository
   5. create a PR linked to this issue
   6. move the issue to _ready for review_
   7. merge the PR, closing this step's issue
   8. move the issue into _done_
   9. pull the new `master` branch to your computer
   10. continue to the next step

<details>
<summary>more info</summary>

### Prep Work

> before class

- [Git & GitHub for Poets](https://www.youtube.com/watch?v=BCQHnlnPusY&list=PLRqwX-V7Uu6ZF9C0YMKuns9sLDzK6zoiV): 1.4
- GitHub
  - [Pull Requests](https://www.youtube.com/watch?v=2M16faxEQsg)
  - linking PRs to Issues: [reference 1](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue),  [reference 2](https://help.github.com/articles/autolinked-references-and-urls/)
  - [closing Issues using keywords](https://help.github.com/en/enterprise/2.16/user/github/managing-your-work-on-github/closing-issues-using-keywords)
- [from-strategy-to-issues](https://github.com/hackyourfuturebelgium/from-strategy-to-issues) (example repository)

### Lesson Plan

> during class

**Before Break**

This week you will build _another_ group repository, this time learning how to use issues, labels and project boards to track your progress like in the [from-strategy-to-issues](https://github.com/hackyourfuturebelgium/from-strategy-to-issues) repository (with all steps assigned to yourself).

By break time you should each have finished to step 4.4 in the week description, you should have:

1. (GitHub) A repository with:
   1. One labeled issue per step in your development strategy
   2. One project board with a full _Ready for Review_ column
   3. Branch per step in the strategy
2. (your computer) A clone of your repository with:
   1. A development strategy ([a starter file](./development-strategies/1-individual-strategy.md))
   2. A main readme
   3. One branch per group member with an introduction file

**After Break**

Pull Requests and Merging!  In the second half of class you will practice creating and merging pull requests on GitHub, as well as linking issues to PRs and using the project boards.

For each branch on GitHub you will:

1. [create a _new_ pull request](https://www.youtube.com/watch?v=2M16faxEQsg)
2. [link the PR to it's issue](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue)
3. Review and merge the code, [closing the linked issue](https://help.github.com/en/enterprise/2.16/user/github/managing-your-work-on-github/closing-issues-using-keywords)
4. Move the closed issue to _done_ in your project board

By the end of class you should have a repository that resembles the [from-strategy-to-issues](https://github.com/hackyourfuturebelgium/from-strategy-to-issues) example (with all steps assigned to yourself).

### Project

> after class

This week's project is to study the [__app-theme__ tutorial from Traversy Media](https://www.youtube.com/watch?v=qlA7dputiNc).

Writing the same code as Mr. Traversy's code is not enough! You are expected to submit your code from his tutorial in a new repository on your GitHub account [forked](https://guides.github.com/activities/forking/) from [this starter template](https://github.com/HackYourFutureBelgium/w3-validation-template).  Your repository should be named `app-theme` and should be cleanly developed with one branch per step.  It's up to you to write the development strategy!

A good strategy to for completing this project is the __three-step__:
1. follow the tutorial studying the code and understanding the project.
2. look over your finished code and break it down into steps, write your development strategy.
3. study the tutorial a second time, following your strategy to build your repository one branch at a time

You will be assessed not only on your live demo, but also on the quality of your code, your development strategy, the correctness of your branches, and the completeness of your repository. Your repository must contain:

### Issue Checklist

Copy-paste this checklist into your individual issue to share your progress with coaches and classmates:

```md
- [ ] [repo](https://github.com/_/_) (with a complete README)
- [ ] [live demo](https://_.github.io/_)
- [ ] [development strategy](https://github.com/_/_/tree/master/development-strategy.md)
- [ ] [project board w/ labeled issues](https://github.com/_/_/projects/1)
- [ ] [issues closed by PRs](https://github.com/_/_/issues)
- [ ] [one branch per step](https://github.com/_/_/branches)
- [ ] [one closed PR per step](https://github.com/_/_/pulls)
```

</details>

[TOP](#incremental-development)

---

## Week 3

Learn to collaborate on one repository:

1. set up your repository and clone it
2. write a development strategy
3. set up a project board on your repo
4. create one issue per step, move them to the board
5. assign each issue to one group member
6. each group member codes their assigned issue
   1. move their issue into _in progress_
   2. creates a new branch locally
   3. writes their new code on that branch
   4. pushes their branch to the group repository
   5. create a PR linked to this issue
   6. assigns team mates to review their PR
   7. waits for the review
7. the group merges each others' pull requests one at a time
   1. review & correct the code
   2. merge the PR after review, closing that issue
   3. move the issue into _done_
   4. everyone pulls the updated `master` branch
   5. repeat

<details>
<summary>more info</summary>

### Prep Work

> before class

- [Git Workflow for Two](https://github.com/hackyourfuturebelgium/git-workflow-workshop-for-two)
- [about code reviews](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-request-reviews)
- [requesting a code review](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)
- [from-strategy-to-issues](https://github.com/hackyourfuturebelgium/from-strategy-to-issues) (example repo)

### Lesson Plan

> during class

**Before Break**

Build one last group intro repository (promise ;)

Before break your will:

1. Choose one of you to be the repository owner, they will complete _step 0_ of the development strategy.
    - When they have finished the group repo should look something like [this example repo](https://github.com/hackyourfuturebelgium/from-strategy-to-issues)
    - Your repo should have: a `development-strategy`, one issue per step, each issue assigned to someone, and a project board for the issues
2. Using the same workflow as last week, each member of the team will complete their assigned issues:
    - Move your issue into "In Progress"
    - Complete your task on a separate branch on your local machine
    - When you have checked all the boxes, push your branch to GitHub
    - Open a Pull Request and [request a review from your team mates](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/requesting-a-pull-request-review)
    - link your PR to your issue ([reference 1](https://help.github.com/en/github/managing-your-work-on-github/linking-a-pull-request-to-an-issue),  [reference 2](https://help.github.com/articles/autolinked-references-and-urls/))
    - Move your issue into "Ready for Review"

**After Break**

Finish what you started before break, merge everyone's branches and close off your work in the project board:

3. Once everyone has created their PRs, review each PR as a group
    - If changes need to be made, request the changes and move the issue to "Needs Revision"
    - If everything is OK: [close te Issue using keywords](https://help.github.com/en/enterprise/2.16/user/github/managing-your-work-on-github/closing-issues-using-keywords), and move the issue to "Done"
4. Discuss!
    - How was this process?
    - Did you get conflicts?  which conflicts and how did you fix them?

### Project

> after class

This week's _**group**_ project is to build your own accessible & responsive clone of the [DuckDuckGo home page](https://duckduckgo.com/?va=z&t=hr) (long version).  We don't expect your DOM to be identical to DuckDuckGo's, but the rendered site should be visually as close as possible.  If you would like to use a CSS framework, go for it! Just be sure everyone in your team uses it ;)

Unlike the last two weeks, this project does not have a video tutorial for you to follow. This week you will also expected to do your best at writing _accessible_ HTML including correct Semantic HTML and ARIA. Pay special attention to points of user interaction like the search field and submit button.

You are expected to submit your code from his tutorial in a new repository [generated](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/) from [the w3-validation-starter repo](https://github.com/HackYourFutureBelgium/w3-validation-template).  Your repository should be named `duck-duck-clone` and should be collaboratively developed following the same workflow you practiced in class this Sunday.  It's up to you to write the development strategy!

### Issue Checklist

Your group will create 1 issue using the _group_ template in your class repo.  Place this issue on the _Incremental Development_ project board and track your progress there so your classmates can study your work and help you when you're stuck.

Copy-Paste this checklist in your group issue:

```md
- [ ] [repo](https://github.com/_/_) (with a complete README)
- [ ] [live demo](https://_.github.io/_)
- [ ] [development strategy](https://github.com/_/_/tree/master/development-strategy.md)
- [ ] [project board w/ labeled & assigned issues](https://github.com/_/_/projects/1)
- [ ] [issues closed by PRs](https://github.com/_/_/issues)
- [ ] [one branch per step](https://github.com/_/_/branches)
- [ ] [one closed PR per step](https://github.com/_/_/pulls)
- [ ] [multiple contributors](https://github.com/_/_/contributors)
```


</details>

[TOP](#incremental-development)

---

# Class Recordings

- **Students**: Here you can find recordings of this module from past classes.  Enjoy!
- **Coaches**: When sending your PR's with links please ...
  - Indicate which class you were teaching
  - Which week it was (if the module is more than 1 week)
  - Give your name
  - and a helpful description

## [Class 9 & 10](https://hackyourfuture.be/class-9-10)

> Stéphane, Tiago, Louise, Dirk, Kevin

- Week 1
  - [Part 1](https://vimeo.com/419992403) - Isolation
  - [Part 2](https://vimeo.com/419993111) - Integration
  - [Part 3](https://vimeo.com/419991575) - Homework explanation
- Week 2
  - [Part 1](https://vimeo.com/422148962)
  - [Part 2](https://vimeo.com/422149182)
  - [Part 3](https://vimeo.com/422347127) - Homework explanation
- Week 3
  - [Part 1](https://vimeo.com/424498862)
  - [Part 2](https://vimeo.com/424519483)
  - [Part 3](https://vimeo.com/424525176)

---

## [Class 11 & 12](https://hackyourfuture.be/class-11-12)

> Stéphane, Tiago, Marie, Unmesh



[TOP](#incremental-development)
