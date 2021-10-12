[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)
[<img align="right" width="150" src="https://i.imgur.com/0Cdusgy.png">](https://discord.com/invite/WA3h4TRfMe)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

# Close My First Issue

Want to practice using GitHub in a team, but are scared or worried about making a mistake?

Let us guide you through the entire progress step by step, in a safe and supportive environment.

## Prerequisites

If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

## 1. Fork this repository

Fork this repository by clicking on the fork button on the top of this page.
This will create a copy of this repository in your account.

## 2. Clone the forked repository

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
git clone https://github.com/<your-github-username>/close-my-first-issue.git
```

Here you're copying the contents of the close-my-first-issue repository on GitHub to your computer.

## 3. Create a local branch

Change to the repository directory on your computer (if you are not already there):

```
cd close-my-first-issue
```

Now create a branch using the `git checkout` command:

```
git checkout -b new-branch-name
```

For example:

```
git checkout -b add-<your-github-username>
```

## 4. Add, stage and commit local changes

Now create `profiles/<your-github-username>.md` in your editor, add `## Hi, I'm <your-ghithub-username>` to the file and then save it.

If you go to the project directory and execute the command `git status`, you'll see there are changes.

<img style="float: right;" src="https://i.imgur.com/78XMI8f.png" alt="check status of working directory" />

Add those changes to the branch you just created using the `git add` command:

```
git add close-my-first-issue/<your-github-username>.md
```

Now commit those changes using the `git commit` command:

```
git commit -m "add <your-github-username>"
```

## 5. Push local commits to remote branch

Push your changes using the command `git push`:

```
git push origin add-<your-github-username>
```

## 6. Open a pull request

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="https://i.imgur.com/XdpuEWB.jpg" alt="create a pull request" />

Now create the pull request.

<img style="float: right;" src="https://i.imgur.com/4rgWAKC.jpg" alt="submit pull request" />

Our mentors will then be notified of your pull request and either approve and merge your changes, or request changes.

You will get a notification in either case.

## Credits

Special thanks to [firstcontributions](https://github.com/firstcontributions) for inspiring us to build upon their incredible work. We both share a vision of wanting to help beginners to contribute to open source projects, and used their [first-contribution](https://github.com/firstcontributions/first-contributions) repository as a base.

We have not forked their repository or preserved commit history because we wanted to keep things as simple as possible for our community of aspiring contributors. For reference, the original MIT licence can be found in our repository [here](https://github.com/the-fast-tracked-programmer/first-contributions/blob/main/LICENSE).


## Where to go from here?

Congratulations!

You have just completed the standard _fork -> clone -> branch -> commit -> push -> open pull request_ workflow that is used to power up to 190 million repositories.

Be sure to [join our discord server](https://discord.com/invite/WA3h4TRfMe) if you haven't already.
