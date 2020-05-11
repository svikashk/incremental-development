# Incremental Development

> "Nearly all Agile teams favor an incremental development strategy;
in an Agile context, this means that each successive version of the product is usable,
and each builds upon the previous version by adding user-visible functionality."

> * [agile alliance](https://www.agilealliance.org/glossary/incremental-development)

### Contents

* [Module Summary](#module-summary)
* [Learning Objectives](#learning-objectives)
* [Module Projects](#module-projects)
* Weekly Details:
  * [Week 1](./week-1/README.md)
  * [Week 2](./week-2/README.md)
  * [Week 3](./week-3/README.md)
* Study Materials:
  * [Isolate](./isolate/README.md) - examples and exercises
  * [Integrate](./integrate/README.md) - projects to study
  * [Class Recordings](./class-recordings.md)
  * [Study Links](https://study.hackyourfuture.be) (external)
* [Curriculum](https://home.hackyourfuture.be/curriculum) (external)
* [HYF Home](https://home.hackyourfuture.be/) (external)

---

## Module Summary

_Incremental Development_ is a strategy for developing software.  In this strategy you start with the simplest code you can possibly write to get things started.  Often this is just empty files with the right names, in the right folders! Then in small steps you more code so that each little step _works_, builds on top of the last step, and is a little closer to the end goal.

This strategy is sooooo important to learn because PROGRAMMING IS HARD.  All developers (even your coaches!) make mistakes all the time.  Software projects are difficult to understand, and mistakes are easy to make.  The best way to manage mistakes is to work in small, understandable steps and making sure that each step works before moving on.

Incremental Development is not so difficult when you're given the steps to complete in order, but it will take discipline to do it correctly and a lot of practice to plan the steps on your own. However, every minute you spend practicing this now will save you hours of debugging later on and make collaboration a breeze!

[TOP](#contents)

---

## Learning Objectives

### Development Workflow

* Disciplines, organized, incremental development
* Breaking large web-sites into small, manageable steps
* Reading and writing `development-strategy.md` files
* Managing many files and folders

### Git, GitHub & GitKraken

* Sending Pull Requests on GitHub
* Turning on GitHub Pages for live websites
* Using Project Boards to track projects
* Using Issues to start a conversation about a specific lines of code
* Pulling & pushing specific branches
* Atomic commits with meaningful messages
* Branching and merging locally
* Disciplined development, building one feature per branch

### Command Line Interface

* Navigating directories
* Creating & removing files and directories
* Running basic Git commands from CLI
* ... fill this out
* `cd`, `ls`, `pwd`, `cat`, ...

### Visual Studio Code

* Installing and enabling plugins
* Opening folders in the side bars
* Adding, deleting and modifying files in a project folder
* Using liveServer to develop your web sites
* Using linters & code formatters (plugins)

### DOM: Basic Life-cycle

1. __Source Code__: HTML & CSS files you edit in VSC
1. __Document Object Model__: What you see in the DevTools
1. __Rendered Page__: What you see in the main browser window

### Browser DevTools

* Finding the source for a website
* Inspecting a specific DOM Element
* Finding the styles for a given element
* Modifying a live web page
* Replicating styles and layout

### HTML & CSS

* Use clear and consistent code formatting
* Write your HTML & CSS in separate files
* Meaningful names for classes & id's
* Correct usage of CSS selectors
* Responsive, mobile first development
* Accessible Rich Internet Applications (ARIA)

[TOP](#contents)

---

## Module Projects

In the first weeks it's very likely that you'll spend as much time figuring out how to publish and turn in your projects as you will spend building them.  _This is totally normal and OK!_  Working like a developer takes time and practice to get good at, and at this point in your learning it's even more important than mastering HTML & CSS!

So on days when you find yourself spending a couple hours strugging with branches, trying to push your homework or create an issue, remind yourself that it's all time well spent. Mastering these skills _now_ will free your time _later_ to focus on studying the more interesting and challenging skills in this course.

Developing a working web site is not enough!  You will be expected to turn in a complete repository, cleanly developed with one branch per step.  It's up to you to decide what the steps are.  Take a look through [this example project](https://github.com/HackYourFutureBelgium/built-with-branches) to get an idea of what an incrementally developed project looks like.  Cloning this repository and studying it with GitKraken/VSC/Browser will help to visualize how Git branches can be used to organize project steps.

Your repository will also need a  README containing a report on what you struggled with, what you learned, and what skills you now need to work.   You will be assessed not only on your working website, but also on the quality of your code, the correctness of your branches, and the completeness of your learning notes in the README.

The goal of these projects is to practice planning and building projects in a methodical and structured way, and to write the cleanest and most correct code possible.  The goal of these projects _is not_ to build the fanciest most beautiful website, to use all the latest CSS tricks, or to use cool libraries.

Here's a short list of do's and don'ts that can help you stay on track:

### Do

* ... use only plain HTML & CSS (no CSS frameworks like Bootstrap or Material!)
* ... pay as much attention to your branches as your code
* ... completely finish one step of the project before moving on to the next
* ... be very careful about your CSS classes, selectors and id's
* ... Properly indent your code
* ... find the simplest solution to each step of the project
* ... start each step of the project by copy-pasting the last step

### Don't

* ... forget to work on separate branches
* ... think that your site can be pretty enough to make up for messy code
* ... use any CSS libraries or frameworks
* ... make the any steps of your project do less _or more_ than is assigned
* ... move on to the next step before the previous one is finished
* ... include any JavaScript

[TOP](#overview)
