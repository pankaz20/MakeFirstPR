<h1 align="center">Make First PR</h1>
<p align="center"> <img src="./images/makepr.png" alt="hello" width="90" /></p>

[![Issues](https://img.shields.io/github/issues/CodeTrophs/MakeFirstPR)](https://github.com/CodeTrophs/MakeFirstPR/issues)
![Forks](https://img.shields.io/github/forks/CodeTrophs/MakeFirstPR)
![Stars](https://img.shields.io/github/stars/CodeTrophs/MakeFirstPR)
[![Licenses](https://img.shields.io/github/license/CodeTrophs/MakeFirstPR)](https://github.com/CodeTrophs/MakeFirstPR/blob/main/LICENSE)

### ✨ Feel free to submit a pull request with your suggestions of Make First PR 🚀

## First Contributions

### Before you start READ [Instructions](./instructions.md)

This project aims to simplify and guide the way beginners make their first contribution. If you are looking to make your first contribution, follow the steps below.

#### If you don't have git on your machine, [install it](https://help.github.com/articles/set-up-git/).

## Fork this repository.

Fork this repository by clicking the fork button at the top of this page.
This will create a copy of this repository in your account.

<p align="center"> <img src="./images/fork.png" alt="hello" /> </p>


## Clone the repository!

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

<p align="center"> <img src="./images/code.png" alt="hello" /> </p>

Open a terminal and run the following git command:

```
git clone https://github.com/put_your_username_here/MakeFirstPR.git
```

<p align="center"> <img src="./images/copy.png" alt="hello" /> </p>

## Create a branch

Change to the repository directory on your computer (if you are not already there):

```
cd MakeFirstPR
```

Now create a branch using the `git checkout` command:

```
git checkout -b username
```

For example:

```
git checkout -b aryasoni98
```

(The name of the branch does not need to have the word _add_ in it, but it's a reasonable thing to include because the purpose of this branch is to add your name to a list.)

## Make necessary changes and commit those changes

If you go to the project directory and execute the command `git status`, you'll see there are changes.

Add those changes to the branch you just created using the `git add` command:

```
git add file-name
```

Now commit those changes using the `git commit` command:

```
git commit -m "Add <file-name>"
```

replacing `<file-name>` with your name.

## Push changes to GitHub

Push your changes using the command `git push`:

```
git push origin <add-your-branch-name>
```

replacing `<add-your-branch-name>` with the name of the branch you created earlier.


## Submit your changes for review

If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.

<img style="float: right;" src="./images/pull-request.png" alt="create a pull request" />

Now submit the pull request.

<img style="float: right;" src="./images/open-pr.png" alt="submit pull request" />

Soon I'll be merging all your changes into the master branch of this project. You will get a notification email once the changes have been merged.
