# Project Setup

Follow these instructions to fork a project to your personal GitHub account, open a workspace, and get automated feedback with `rake grade`.

## Quick links

Please read the lesson below. But, for future reference, here are some quick links:

* [Setup a Codespace environment](https://learn.firstdraft.com/lessons/47-codespaces-setup)
* [Git commit and push to save your work](https://learn.firstdraft.com/lessons/50-git-commit-and-push)
* [Get automated `rake grade` feedback](https://learn.firstdraft.com/lessons/125-using-rake-grade)

## Fork the project

When you load a Grades project, you'll arrive at a page with several links.

Your first step will be to open the link that looks like `appdev-projects/<project-name>` in a new tab:

<!-- ![](/assets/launch-hello-world-fork.png) -->
![](https://res.cloudinary.com/dmxgp9oq2/image/upload/v1689100920/launch-hello-world-fork_c8kapv.png)

This will take you to my copy of the project, containing any starter code, on GitHub.com. "Repository" is Git's term for "a folder containing code". We also often say "repo", for short.

The next step is to create your own copy of the starter code, so that you can save your work and have it forever. GitHub calls these copies "forks".

On my repo's page (i.e. `github.com/appdev-projects/<project-name>`), click on the "Fork" button in the top-right:

<!-- ![](/assets/launch-grades-project-2.png) -->
![](https://res.cloudinary.com/dmxgp9oq2/image/upload/v1686701065/launch-grades-project-2_hduxmk.png)

On the "Create a new fork" page, make sure that your personal GitHub username is set as the "Owner" and that your copy's name is the same as mine. 

Now click "Create fork":

<!-- ![](/assets/launch-grades-project-3.png) -->
![](https://res.cloudinary.com/dmxgp9oq2/image/upload/v1686701280/launch-grades-project-3_tnau3z.png)

It will take a few seconds to make a copy, and then you should end up on a page for your own fork of the repository.

If all went well, you should see `github.com/<your-username>/<project-name>` in your address bar, and a note "forked from `appdev-projects/<project-name>`":

<!-- ![](/assets/launch-grades-project-4.png) -->
![](https://res.cloudinary.com/dmxgp9oq2/image/upload/v1686701561/launch-grades-project-4_zpnslw.png)

## GitHub Codespaces

One of the most painful parts of learning how to program, in the old days, was simply setting up your computer to be able to write and run code. At a minimum, we needed to install:

  - An application to write your code with. Something like Microsoft Word is not be ideal for writing code, since code needs to be _plain text_ (just a series of characters in a file, nothing else) for the computer to understand it. Word is designed to write _rich text_ (for humans) with fonts, colors, sizes, margins, layouts, etc.

<aside markdown="1">
Computers come bundled with some plain text editors (Notepad, TextEdit, etc) but they are very basic. We would instead prefer to use powerful tools specifically designed for writing code with like Microsoft's VSCode or JetBrains' RubyMine.
</aside>

  - Ruby itself. Writing code is not useful on its own if we don't have something to run it with; just like we need a browser installed to interpret `.html` files we need Excel installed to interpret `.xls` files, and we need Photoshop installed to interpret `.ps` files, we need Ruby installed in order to interpret the `.rb` files that we write.

<aside markdown="1">
Not only do we need Ruby, we need the correct _version_ installed. If your computer happened to come with an older version, upgrading to a newer version could be complicated — especially if some other application you use depends on the older version.
</aside>

There are so many different combinations of hardware, operating systems, previously installed software, permission levels (for example if you are using a work-owned computer), that just getting these things installed would often stop you before you started writing your first program. We can't allow that!

Instead, we're going to use a write our code using a _cloud_ computer. "Cloud" just means that it's a computer that's sitting in someone's warehouse somewhere, and we rent it from them. It already has all of the software that we need installed on it, and we access it through our browsers. No muss, no fuss!

<aside markdown="1">
A warehouse full of computers that people rent and connect to via the internet is called a "data center". Some data centers have their own power plants, and some are even earthquake-proofed.
</aside>

GitHub happens to have an excellent cloud editor integrated into it: [GitHub Codespaces](https://github.com/codespaces).

GitHub Codespaces is a great new service that provides instantaneous, full-fledged cloud development environments from any codebase that is on GitHub.com — which is great, because we (and 98% of other teams) use GitHub to store all of our projects, homeworks, etc. The text editor they provide is based on Microsoft's VSCode — my editor of choice. It will have the exact right version of Ruby, Rails, and everything else we need. And they have a very generous free tier. Great!

### Getting started With Codespaces

To setup a Codespaces environment, all you need to do is follow [these instructions to open and manage your Codespace environment](https://learn.firstdraft.com/lessons/47-codespaces-setup).

Importantly, whenever you are working on any project, **don't forget to commit and push using our Git workflow so that your work is saved on GitHub**. [Follow these instructions for those steps](https://learn.firstdraft.com/lessons/50-git-commit-and-push).

## Getting automated feedback

For many projects, we have automated tests built in. Your first job is always to make your app work as described and test it manually yourself. If there is a target app, use that for reference. Debug your live app preview by Reading The Error Messages. You should not rely exclusively on the automated tests; they are a terrible way to debug.

When you're ready for feedback visit our [`rake grade` lesson for detailed instructions on getting automated feedback](https://learn.firstdraft.com/lessons/125-using-rake-grade)

## Alternative workspace environments

We recommend sticking to Codespaces, since that is what we use in the course. But there are other options for running our projects or your own personal projects.

### Gitpod cloud editor

[Gitpod.io](https://www.gitpod.io) is another great service that provides instantaneous, full-fledged cloud development environments from any codebase on GitHub. There is also a free tier that will likely be sufficient for the first phase of AppDev, but you will need to pay if you use the service a lot. Instructions for [running Gitpod projects can be found here](https://learn.firstdraft.com/lessons/48-gitpod-setup).

### Local setup

If you are comfortable digging into the command-line and setting up your own development environment, the classic approach is to setup VSCode and all of the Ruby and Rails dependencies on your local laptop. This has the benefit of unlimited free hours of coding, including when you are not connected to the internet. However, you may face challenges that we do not cover in our documentation, requiring you to research solutions on your own or with the help of an instructor. We only recommend [these instructions if you are prepared to face these challenges](https://learn.firstdraft.com/lessons/49-local-setup).
