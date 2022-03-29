[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)

# Close My First Issue

Don't feel confident using GitHub in a team (yet)?

Practice the open source contribution workflow by closing your very first issue, step by step 💪.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

## Step 1. Get assigned a practice issue

1. [<img align="left" width="150" src="https://i.imgur.com/0Cdusgy.png">](https://discord.com/invite/jnMj34qPAg)
<br/><br/>
2. Enter `/join-github-org YOUR-EMAIL-ADDRESS YOUR-GITHUB-USERNAME` in the #get-started message field
3. Accept the invite GitHub emails you to join *The Fast Tracked Programmer* organization

After you've accepted the invite, a mentor will

1. open and assign you a practice issue to close in this project, which will appear under [open issues assigned to you](https://github.com/the-fast-tracked-programmer/close-my-first-issue/issues?q=is%3Aopen+assignee%3A%40me)
2. reach out to offer guidance and support in our awesome discord [#community](https://discord.com/channels/815407176734212126/894788853045530624). See the [trello board](https://trello.com/b/WFrU7822/close-my-first-issue) for details.


## Step 2. Fork this repository

Fork this repository by clicking on the fork button on the top of this page.

This will create a copy of this repository in your GitHub account, that you can publish your local changes to.

## Step 3. Clone your forked repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine.

Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

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

PS. If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Step 4. Create and checkout a local branch

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

## Step 5. Add, stage and commit local changes

Now create `profiles/<your-github-username>.md` in your editor, add `## Hi, I'm <your-github-username>` to the file and then save it.

Upon executing the command `git status`, you'll see there are changes.

Stage those changes with the `git add` command:

```
git add profiles/<your-github-username>.md
```

And commit those changes using the `git commit` command:

```
git commit -m "add <your-github-username>"
```

## Step 6. Push local commits to remote branch

Push your changes using the command `git push`:

```
git push origin add-<your-github-username>
```

## Step 7. Open a pull request

<img align="right" width="200" src="https://i.imgur.com/XdpuEWB.jpg" alt="create a pull request" />

If you go to your repository on GitHub, you'll see a `Compare & pull request` button.

Click on that button to start creating a pull request.

<img align="right" width="200" src="https://i.imgur.com/4rgWAKC.jpg" alt="submit pull request" />
<br/>

Our mentors will then be notified of your pull request and either approve and merge your updates, or request changes.

You will get a notification in either case.

## Credits

Special thanks to [firstcontributions](https://github.com/firstcontributions) for inspiring us to build upon their incredible work. We both share a vision of wanting to help beginners to contribute to open source projects, and used their [first-contribution](https://github.com/firstcontributions/first-contributions) repository as a base.

We have not forked their repository or preserved commit history because we wanted to keep things as simple as possible for our community of aspiring contributors. For reference, the original MIT licence can be found in our repository [here](https://github.com/the-fast-tracked-programmer/first-contributions/blob/main/LICENSE).


## Where to go from here?

Congratulations!

You've just completed the standard _fork -> clone -> branch -> commit -> push -> open pull request_ workflow that is used to power up to 190 million GitHub repositories.

If you're wondering what to do next, be sure to introduce yourself and share your programming journey in our super friendly [#community](https://discord.com/channels/815407176734212126/894788853045530624).

Experienced mentors check this channel regularly and routinely offer guidance based on what you plan to achieve.
