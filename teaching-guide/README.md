# Teaching Guide

> A little guide for who ever is teaching this module, and for curious students.

This Incremental Development module is a module about how to break down and plan projects, first alone and then as a team. Students will be learning about responsive design and accessibility but that happens as self-study. Class time will be spent talking about project planning and collaboration.

The two main focuses of this module should be:

- writing and interpreting development strategy files
- using issues, labels, PRs and project boards to carry out the development strategy

When you give feedback on projects you should focus more on the students' strategy and process than on the finished code.

- [Before this Module](#before-this-module)
- [During this Module](#during-this-module)
  - [common confusions](#common-confusions)
  - [week 1](#week-1)
  - [week 2](#week-2)
  - [week 3](#week-3)
- [After this Module](#after-this-module)
- [helpful links](#helpful-links)

---

## Before this Module

In the previous module ([precourse](https://github.com/HackYourFutureBelgium/precourse/)) students set up all the softwares they should need for this module and learned how to:

- write and lint markdown using VSCode extensions
- develop an HTML/CSS project locally with LiveServer
- commit, push & pull changes between local and github
- a first taste of issues and project boards when they submitted their precourse assignments

[TOP](#teaching-guide)

---

---

## During this Module

Projects in this module will be basic HTML/CSS websites so students can focus on the development process. The first two projects don't even ask students to write their own code from scratch, they will be reverse-engineering the finished code from tutorials. This helps to put the focus on planning and collaborating since the code is not a challenge.

### Common Confusions

Students will have confusions about HTML/CSS but those are not the biggest priority in this module. In an ideal world there would be time to cover everything but as things are you will want to focus students' attention to organized development and project management workflows. That said, here are some common confusions about Git, GitHub, incremental development, and collaboration:

- The difference between Git and GitHub
- The difference between a step in the development strategy and a task within a step
- Branches: pushing to them, and sending PRs
- > there's always something missing on this list! Send us a PR if you know what it is

### Week 1

This week is about development strategy files and GitHub project management (issues, PRs & labels/milestones). This will feel quite abstract and confusing for students at first. But we've found that with the limited time available it's better to start with the big picture and rehearse it for 3 weeks than to build up from a simpler workflow.

Remind students that the workflows they're encountering this week are the same workflows they will use for all projects at HYF and are a good prep for professional collaboration. They don't need to master this in the 3 weeks of this module, just get the big idea. The details can fill in with time

#### In Class

An introduction development strategy files and to project management features on GitHub. After you present the big picture and exploring some examples as a full class, students will break into their small groups to build an ice-breaker repository consisting of a README and one file introducing each group member (they have already built one of these in the precourse so they should have the files ready). The goal is to get some hands-on practice with project management:

- beginning from a development strategy file
- create one milestone for each step in the dev-strategy
- create one issue for each task in the dev-strategy (attach milestones & labels)
- create a new branch for each issue, do the work
- send a pull requests that closes each task's issue
- two examples to get the idea:
  - strategy to issues (coming soon)
  - [group intro example](https://github.com/HackYourFutureBelgium/group-intro-example) (product)

Here are some tips and starter material to make the group time as helpful as possible:

- students can do all of the work on GitHub directly, no need to push & pull
- students can copy-paste the markdown they wrote for the precourse
- each student should create their own repository, this exercise will be individual (but completed all together)
- share your screen to fill out the dev-strategy and set up the issues for each task, students can follow along on their computers
- have the students take turn sharing their screens, each person completing one issue->branch->PR in their repo with the group's support

#### Homework Project

> - finished code: provided
> - strategy: provided
> - project management: not provided

This week's project is individual, students will reverse-engineer the code from an HTML/CS tutorial video using all the proper workflows. Students will be given a development strategy and the tutorial, the rest is up to them. They should be encouraged to modify the dev-strat and tutorial code if they are comfortable.

When reviewing projects you will be looking more at the quality of their branches and project management than at their live demo. The project checklist in the main README will have an overview of what to look for.

---

### Week 2

This week is about collaboration on a shared repository. Following the same workflow as last week, but keeping track of issues on a project board.

#### In Class

This class session is for getting students ready to work in groups. Answer any questions from laste week then take some time to share your personal experience and to prepare them for the challenges they will have collaborating on a project this week. For simple things like this week's HTML/CSS site, it will be more work to collaborate than to just building it alone.

After this discussion, break into small groups and practice collaboration by building another group markdown repository. This time everyone will be contributors in the same repository and they will practice pushing & pulling their work:

- (remind your group that this is the workflow they will follow for this week's group project)
- beginning from a development strategy file
- create one milestone for each step in the dev-strategy
- create one issue for each task in the dev-strategy (attach milestones & labels)
- place the issues in the `todo` column of a new project board (in the repo)
- then each student takes turns sharing their screen
  - move an issue into "in progress"
  - create a new branch for the issue
  - locally: pull from master, create a branch, do the work, push the branch
  - send a pull request to merge their branch on GitHub
  - review the PR & merge
- you probably won't get through every issue/student, encourage them to finish this as a group over the week

#### Homework Project

> - finished code: provided
> - strategy: not provided
> - project management: not provided

Students will be reverse-engineering a Traversy tutorial like last week, but as a group on a shared repository. This week they will need to write their own development strategy based on the tutorial.

When reviewing projects you will be looking more at the quality of their branches and project management than at their live demo. The project checklist in the main README will have an overview of what to look for.

[TOP](#teaching-guide)

---

### Week 3

The main objective this week is to learn about reverse-engineering a website. Given a live web-page, students will need to create a wireframe, inspect to find colors, and . In class this will be a very very simple HTML/CSS web page, in the week's project it will be duckduckgo.com.

#### In Class

The activity in class is to walk students through how you would reverse-engineer a simple HTML/CSS website using the planning and workflows they've learned so far. The code should be very simple and you shouldn't put so much time into preparing it, even using the final step of a `/stepped` example project is okay. Depending on how well your groups work together, and how comfortable you are presenting, this week you may not want to split into small groups.

The reverse-engineering process should look something like this:

0. Create an empty directory where you will rebuild the project.
1. Open the finished website and look at it without the devtools open. What are the key parts of the website?
1. Create a wireframe for this website (wireframe.cc is good enough). Download the wireframe and save it in your project folder for later.
1. Set up a development strategy, include: title, description, wireframe
1. Write the steps of your strategy: in what order will you develop each piece of your wireframe?
1. Once the steps are written, open the devtools and inspect the finished site. what elements are used to create each part of the site? what styling is used? Use these questions as a guide to fill out the tasks in each step of the strategy.
   - you can take this one step further by downloading site assets, measuring site colors, and inspecting the site's font.

After completing this workflow together, you could do a few things depending on your class:

- start writing the HTML/CSS described in this strategy
- guide the class through converting this strategy to a repo with issues & a project board
- split into groups and have each group practice this workflow with a different web site

#### Homework Project

> - finished code: not provided
> - strategy: not provided
> - project management: not provided

Working in a team, students will reverse-engineer duckduckgo.com (visually, not the functionality). They will be expected to write their own development strategy and collaborate on a shared repo using the workflows covered in this module.

[TOP](#teaching-guide)

---

---

## After this Module

In the next module ([ux-ui-design](https://github.com/HackYourFutureBelgium/ux-ui-design), 1 week) students will learn more about User Flows and learn to use Figma to design web pages. Along the way they will learn more about project planning, including backlogs and a first taste of agile.

The project will be to design and build a personal home page.

[TOP](#teaching-guide)

---

## helpful links

- HYF Be Guidebooks
  - [coaches](https://home.hackyourfuture.be/coaches)
  - [students](https://home.hackyourfuture.be/students)
- About Teaching:
  - https://teachtogether.tech/
  - https://teachertraining.codeyourfuture.io/
  - https://teach.hackyourfuture.be
