[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)
[<img align="right" width="150" src="https://i.imgur.com/0Cdusgy.png">](https://discord.com/invite/WA3h4TRfMe)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

# First Contributions

This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open a terminal and run the following git command:

```
git clone "url you just copied"
```

where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project). See the previous steps to obtain the url.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/<your-github-username>/first-contributions.git
```

<!-- example-: git clone https://github.com/sunil/first-contributions.git -->

Here you're copying the contents of the first-contributions repository on GitHub to your computer.

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd first-contributions
```

Now create a branch using the `git checkout` command:

```
git checkout -b new-branch-name
```

For example:

```
git checkout -b add-<your-github-username>
```

this above command will create branch and switched to it.

<!-- git branch branch_name
this above command only used for creating branch

git checkout branch_name
and this command will be used for branch switching
-->

## Make necessary changes and commit those changes

Now create `first-contributions/<your-github-username>.md` in your editor, add `## Hi, I'm <first name> <last name>` to the file and then save it.

If you go to the project directory and execute the command `git status`, you'll see there are changes.

<img style="float: right;" src="https://i.imgur.com/78XMI8f.png" alt="check status of working directory" />

Add those changes to the branch you just created using the `git add` command:

```
git add first-contributions/<your-github-username>.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "add <your-github-username>"
```

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin add-<your-github-username>
```

## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://i.imgur.com/XdpuEWB.jpg" alt="create a pull request" />

Now create the pull request.

<img style="float: right;" src="https://i.imgur.com/4rgWAKC.jpg" alt="submit pull request" />

Our mentors will then be notified of your pull request and either approve (and merge) your contribution, or request changes.

You will get a notification email in either case.

## Where to go from here?

Congratulations! You just completed the standard _fork -> clone -> edit -> pull request_ workflow that you'll encounter often as a contributor!

See our [list of projects](https://firstcontributions.github.io/#project-list) to help you continue your journey into open source.

And be sure to [join our discord server](https://discord.com/invite/WA3h4TRfMe) if you haven't already.
