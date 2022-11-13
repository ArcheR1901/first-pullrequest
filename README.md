# Contribution to open source
[![Open Source Love](https://firstcontributions.github.io/open-source-badges/badges/open-source-v1/open-source.svg)](https://github.com/firstcontributions/open-source-badges)

This repository has been created to simply the process of open source contribution on github using git. At the end, you will learn how to contribute by adding your own projects in any technology or documentation on any technology. If you have no projects, basic programs or documantation, don't worry. Just follow till the end and you will know why.

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/fork.png" alt="fork this repository" />

### To install git, [install it](https://help.github.com/articles/set-up-git/).

## Fork the repository
Fork the repository by clicking on fork button as shown in the image and then name it according to you.
This will create a copy of this repository in you account.

### Clone the repository

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/clone.png" alt="clone this repository" />

Now clone the forked repository to your machine. Go to your GitHub account, open the forked repository, click on the code button and then click the _copy to clipboard_ icon.

Open the file location, where you want to copy this repository. Right click, and then click Git bash here.
This will open a terminal. 

Type in-
```
git clone "url you just copied"
```
where "url you just copied" (without the quotation marks) is the url to this repository (your fork of this project that you saved according to your choice of name).

<img align="right" width="300" src="https://firstcontributions.github.io/assets/Readme/copy-to-clipboard.png" alt="copy URL to clipboard" />

For example:

```
git clone https://github.com/username/first-pullrequest.git
```

where `username` is your GitHub username. Here you're copying the contents of the first-pullrequest repository on GitHub to your computer.

## Create a branch

As you cannot directly commit changes to the main branch, create your own branch.

Open the file location where you cloned the repository, open `first-pullrequest` folder.
Right click and click on git bash here.

Once the terminal opens, type in - 

```
git checkout -b your-new-branch-name
```
Instead of your-new-branch-name, type whatever name you want to, without space. And if there are multiple names, use the above given format and use `-` in between two names.

## Committing

To add your work, create new folder in the `first-pullrequest` folder and name them according to either technologies used like Java, CSS, etc. Categorize it further by creating more folders that states whats inside of this folder like documentation, code, Readme, etc.

If you just started with Git and GitHub and have no basic project or documentation, don't worry. 
There is `Contributors.md` file in the main `first-pullrequest` folder.
Open it any text editor and add you name followed by your Github Url. Don't add it on top or at the end, add it in the middle and save the file before closing it.

If you open the already opened git terminal and type in - `git status` you will find some changes made.
Add those changes to you branch by typing - `git add .` or `git add filename.txt`, here filename is the name by which it is in the folder and .txt is the extenion of the actual file(it can be other than .txt).

```
git add .
```

Commit those changes by typing -
```
git commit -m "Add a message here that states your change"
```
Add an actual message in side those " "

Push the changes made by you to the main branch by typing -
```
git push origin branchname
```
Here, add your specified branchname after origin.

## Submit changes for review

Open your Github repositorym you will find a `compare & pull request button`. Click it.

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/compare-and-pull.png" alt="create a pull request" />

Click on `submit` button as shown in the image below;

<img style="float: right;" src="https://firstcontributions.github.io/assets/Readme/submit-pull-request.png" alt="submit pull request" />

I will check all your pull requests, notify you with some changes if any and I'll merge them. You will get an email notifying anything regarding your pull request. 

## Thing to look for
`1. Always copy the url form the forked repository.
 2. While forking, make sure you are forking the original repository and not someone else's fork.
 3. Once forked, cannot be forked again until the fork is deleted.
 4. If you want to contribute again while the old pull request is till under check, either create a new branch
    and make the changes and create another pull request or, make changes on the same branch and create a pull request. But, in the second case, you won't be able to see the compare and pull button, it will directly go into the older request from the same branch, and once the owner of the repository accepts it, both the requests will be accepted at once.

And done.....! You've just opened your first pull request on Github. 

