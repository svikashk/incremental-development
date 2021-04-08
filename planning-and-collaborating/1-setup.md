# Setup

Before diving into your project make sure your team has all the practical things in place. This step isn't very hard and will be basically the same for every project, it will become habit.

## Create and Share a Repository

As a team you will choose the name for your project's repository and select someone from your team to be the repo owner. They will create a new repository:

- The Basics
  - Use the name your team decided on
  - Initialize with an empty README
  - Chose a LICENSE (MIT is good)
  - Turn on GitHub Pages and set your live URL as the Website in your repository's About section
  - Turn on Discussions in your repository
- Collaboration Settings
  - Add everyone in your team as a contributor with _Admin_ access
  - Require a code review for PRs to `main`/`master` ([owanateamachree](https://owanateamachree.medium.com/how-to-protect-the-master-branch-on-github-ab85e9b6b03), [github docs](https://docs.github.com/en/github/collaborating-with-issues-and-pull-requests/approving-a-pull-request-with-required-reviews))
    - You will need to type `main` or `master` into the _Branch name pattern_ input box (depending on which on what your repo's default branch is named)
    - Select _Dismiss stale pull request approvals when new commits are pushed_
- Create your group project issue in the Class Repository and assign all your team members

---

## Milestones

Create 5 milestones in your repository:

- **planning**
- **must-have**, **should-have**, **could-have**
- **retrospective**

---

## Planning Folder

> [example planning folder](./example-all-about-trees/planning)

Create a folder called `/planning` with the empty documents your team will need for Planning and Collaborating:

- **`/planning/README.md`**: for your communication plan
- **`/planning/backlog.md`**: for writing and prioritize your user stories
- **`/planning/constraints.md`**: for clarifying your group's limitations
- **`/planning/development-strategy.md`**: for breaking your _must-have_ user stories into tasks
- **`/planning/retrospective.md`**: for recapping what went well and what went less well
- **`/planning/wireframe.md`**: for displaying your wireframe and explaining your design decisions

---

## Boilerplate Code

> example boilerplate: [html](./example-all-about-trees/index.html), [css](./example-all-about-trees/style.css)

[Boilerplate code](https://brandlitic.com/what-is-boilerplate-code/) is files of code that you will need for your project but that do not have anything specific in them yet. For projects in Incremental Development, it will mean just a starter HTML file and an empty CSS file.

The boilerplate you use will grow as you move through the HYF modules. Most projects will have a starter repository containing the boilerplate code you need, but for now you will be need to create it yourself.

[daily-dev-tips](https://daily-dev-tips.com/posts/html5-starting-boilerplate-template/) has a good HTML boilerplate file you can use (remove the `<script>` tag for now, there will be no JS in your projects yet)
