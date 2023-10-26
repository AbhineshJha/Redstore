# Redstore - Trending Clothes for Men and Women
>Welcome to Redstore, your go-to destination for the latest and greatest in trending fashion for both men and women! This repository hosts the HTML and CSS codebase for the Redstore website.

![Redstore Banner](img\logo.png)

# Contributing

Thanks for your interest in contributing! Please read carefully through our guidelines below to ensure that your contribution adheres to our project's standards.

We welcome and encourage contributions from the community! Here's how you can start contributing to Redstore:

1. **Create an Issue:** If you find a bug, have a suggestion, or want to request a new feature, please create an issue on this repository. Make sure to provide as much detail as possible.

2. **Pull Requests:** We appreciate your contributions. If you want to fix a bug or add a new feature, fork the repository, make your changes, and submit a pull request. We'll review it as soon as we can.



## Code of Conduct

To hold a safe space for all contributors, we expect all project participants to adhere to our Code of Conduct. Please read the [full text](CODE_OF_CONDUCT.md) so that you can understand what actions will and will not be tolerated.

## Issue Tracking

We use [GitHub Issues](https://github.com/AbhineshJha/Redstore/issues) to track all tasks related to this project.

To help you get your feet wet and get you familiar with our contribution process, we have [a list of friendly issues](https://github.com/AbhineshJha/Redstore/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) that contain tasks which are fairly easy to fix. This is a great place to get started.


## Build the project locally

In order to contribute to a project on GitHub, you must first get a copy of the project running locally on your computer. This process is sometimes called a "build process", and every project's process will have different requirements. Some requirements are due to the project being hosted on GitHub, some are due to the programming language used, some are due to the project's dependencies.

There are five steps to building this project:

1. [Set up Git](#set-up-git-and-install-nodejs)
1. [Fork the repository](#fork-the-repository)
1. [Clone your fork](#clone-your-fork)
1. [Install dependencies](#install-dependencies)
1. [Run the project](#run-the-project)

### Set up Git

All GitHub projects are backed by a version control software called *Git*. You'll need to [set up Git](https://github.com/danthareja/contribute-to-open-source/wiki/Setting-up-Git) in order to contribute to *any* project on GitHub.

### Fork the repository

A *fork* is a copy of a repository. Forking a repository lets you to make changes to your copy without affecting any of the original code.

Click **Fork** (in the top-right corner of the page) to copy this repository to your GitHub account.

### Clone your fork

A *clone* is a downloaded version of a repository. Cloning our fork lets you download a copy of the repository to your computer.

Use `git` to clone your fork

```
$ git clone https://github.com/YOUR-USERNAME/Redstore.git
```

### Install dependencies

Did you know that the author usually does not write all of the code in a project?

The beauty of open source is that you can install and use code that other people have written, allowing you to focus on the unique requirements of your project. Third-party code that your project installs is called a *dependency* because it is required to work.

First, navigate into the project's directory

```
$ cd Redstore
```

>It's recommended to create a branch naming the issue you solve: Like you are **fixing screen bug**

```
git checkout -b "branch_name_realted_to_bug
```

### Run the project

Run the project locally and see if you can solve some issues.

## Submit a Pull Request

Remember how making changes on a *fork* doesn't affect the original code? Well, in order to fix an issue in the main project, you *want* to change the original code. A *pull request* is a GitHub feature that lets you do just that!

There are three steps to submitting a pull request:
1. [Save your changes locally](#save-your-changes-locally)
2. [Send your changes to your fork](#send-your-changes-to-your-fork)
3. [Open a Pull Request](#open-a-pull-request)

These instructions are designed to explain the bare minimum steps in a beginner-friendly way. If you find yourself hungry for more details (or get stuck), I applaud and encourage you to continue research on your own. You'll find no lack of amazing articles on this topic.

### Save your changes locally

First, get a list of all the files you have changed.
```
$ git status
```

Next, *stage* the file you want to save. This will add the file to a new list that is ready to be saved.
```
$ git add src/filename_abc
```

Next, verify that the file has been staged correctly. Notice that the text color has changed, and your file is now in a list that says "Changes to be committed" instead of "Changes not staged for commit"
```
$ git status
```

Finally, save your staged files.
```
$ git commit -m "solve_issue/you_like"
```

You'll often hear this process called *committing* changes. It's the exact same thing.

### Send your changes to your fork

With one simple `git` command, you can send the changes you just committed locally to your *fork* on GitHub.

```
$ git push origin "branch_name"
```

### Open a Pull Request

1. Find the [New Pull Request](https://github.com/AbhineshJha/Redstore/compare) button
2. Select the option to **compare across forks**
3. Select **your username** in the `head fork` option
4. Select **author** in the `base` option
5. Click **Create Pull Request**

Now wait for someont to response, remember that open-source community is so much helpful, they are also human having family, hobbies, work so wait before directly reaching on them.