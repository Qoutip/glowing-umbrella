Hello World 🌟🌟🌟
In this article
Introduction🚀
Creating a repository✅
Creating a branch✅
Making and committing changes✅
Opening a pull request✅
Merging your pull request✅
Next steps🆒
Follow this Hello World exercise to get started with GitHub.🚀

Introduction
GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

This tutorial teaches you GitHub essentials like repositories, branches, commits, and pull requests. You'll create your own Hello World repository and learn GitHub's pull request workflow, a popular way to create and review code.

In this quickstart guide, you will:

Create and use a repository
Start and manage a new branch
Make changes to a file and push them to GitHub as commits
Open and merge a pull request
To complete this tutorial, you need a GitHub account and Internet access. You don't need to know how to code, use the command line, or install Git (the version control software that GitHub is built on). If you have a question about any of the expressions used in this guide, head on over to the glossary to find out more about our terminology.

Creating a repository
A repository is usually used to organize a single project. Repositories can contain folders and files, images, videos, spreadsheets, and data sets -- anything your project needs. Often, repositories include a README file, a file with information about your project. README files are written in the plain text Markdown language. You can use this cheat sheet to get started with Markdown syntax. GitHub lets you add a README file at the same time you create your new repository. GitHub also offers other common options such as a license file, but you do not have to select any of them now.

Your hello-world repository can be a place where you store ideas, resources, or even share and discuss things with others.

In the upper-right corner of any page, use the  drop-down menu, and select New repository.

Screenshot of a GitHub dropdown menu showing options to create new items. The menu item "New repository" is outlined in dark orange.

In the "Repository name" box, type hello-world.

In the "Description" box, type a short description.

Select whether your repository will be Public or Private.

Select Add a README file.

Click Create repository.

Creating a branch
Branching lets you have different versions of a repository at one time.

By default, your repository has one branch named main that is considered to be the definitive branch. You can create additional branches off of main in your repository. You can use branches to have different versions of a project at one time. This is helpful when you want to add new features to a project without changing the main source of code. The work done on different branches will not show up on the main branch until you merge it, which we will cover later in this guide. You can use branches to experiment and make edits before committing them to main.

When you create a branch off the main branch, you're making a copy, or snapshot, of main as it was at that point in time. If someone else made changes to the main branch while you were working on your branch, you could pull in those updates.

This diagram shows:

The main branch
A new branch called feature
The journey that feature takes before it's merged into main
Diagram of the two branches. The "feature" branch diverges from the "main" branch, goes through stages for "Commit changes," "Submit pull request," and "Discuss proposed changes," and is then merged back into main.

Have you ever saved different versions of a file? Something like:

story.txt
story-edit.txt
story-edit-reviewed.txt
Branches accomplish similar goals in GitHub repositories.

Here at GitHub, our developers, writers, and designers use branches for keeping bug fixes and feature work separate from our main (production) branch. When a change is ready, they merge their branch into main.

Create a branch
Click the Code tab of your hello-world repository.

Above the file list, click the dropdown menu that says main.
Screenshot of the repository page. A dropdown menu, labeled with a branch icon and "main", is highlighted with an orange outline.

Type a branch name, readme-edits, into the text box.

Click Create branch: readme-edits from main.

Screenshot of the branch dropdown for a repository. "Create branch: readme-edits from 'main'" is outlined in dark orange.
Now you have two branches, main and readme-edits. Right now, they look exactly the same. Next you'll add changes to the new branch.

Making and committing changes
When you created a new branch in the previous step, GitHub brought you to the code page for your new readme-edits branch, which is a copy of main.

You can make and save changes to the files in your repository. On GitHub, saved changes are called commits. Each commit has an associated commit message, which is a description explaining why a particular change was made. Commit messages capture the history of your changes so that other contributors can understand what you’ve done and why.

Under the readme-edits branch you created, click the README.md file.

To edit the file, click .

In the editor, write a bit about yourself. Try using different Markdown elements.

Click Commit changes....

In the "Propose changes" box, write a commit message that describes your changes.

Click Propose changes.

These changes will be made only to the README file on your readme-edits branch, so now this branch contains content that's different from main.

Opening a pull request
Now that you have changes in a branch off of main, you can open a pull request.

Pull requests are the heart of collaboration on GitHub. When you open a pull request, you're proposing your changes and requesting that someone review and pull in your contribution and merge them into their branch. Pull requests show diffs, or differences, of the content from both branches. The changes, additions, and subtractions are shown in different colors.

As soon as you make a commit, you can open a pull request and start a discussion, even before the code is finished.

By using GitHub's @mention feature in your pull request message, you can ask for feedback from specific people or teams, whether they're down the hall or 10 time zones away.

You can even open pull requests in your own repository and merge them yourself. It's a great way to learn the GitHub flow before working on larger projects.

Click the Pull requests tab of your hello-world repository.

Click New pull request

In the Example Comparisons box, select the branch you made, readme-edits, to compare with main (the original).

Look over your changes in the diffs on the Compare page, make sure they're what you want to submit.

Screenshot of a diff for the README.md file. 3 red lines list the text that's being removed, and 3 green lines list the text being added.

Click Create pull request.

Give your pull request a title and write a brief description of your changes. You can include emojis and drag and drop images and gifs.

Optionally, to the right of your title and description, click the  next to Reviewers. Assignees, Labels, Projects, or Milestone to add any of these options to your pull request. You do not need to add any yet, but these options offer different ways to collaborate using pull requests. For more information, see "About pull requests."

Click Create pull request.

Your collaborators can now review your edits and make suggestions.

Merging your pull request
In this final step, you will merge your readme-edits branch into the main branch. After you merge your pull request, the changes on your readme-edits branch will be incorporated into main.

Sometimes, a pull request may introduce changes to code that conflict with the existing code on main. If there are any conflicts, GitHub will alert you about the conflicting code and prevent merging until the conflicts are resolved. You can make a commit that resolves the conflicts or use comments in the pull request to discuss the conflicts with your team members.

In this walk-through, you should not have any conflicts, so you are ready to merge your branch into the main branch.

At the bottom of the pull request, click Merge pull request to merge the changes into main.
Click Confirm merge. You will receive a message that the request was successfully merged and the request was closed.
Click Delete branch. Now that your pull request is merged and your changes are on main, you can safely delete the readme-edits branch. If you want to make more changes to your project, you can always create a new branch and repeat this process.
Next steps
By completing this tutorial, you've learned to create a project and make a pull request on GitHub.

Here's what you accomplished in this tutorial:

Created an open source repository
Started and managed a new branch
Changed a file and committed those changes to GitHub
Opened and merged a pull request
Take a look at your GitHub profile and you'll see your work reflected on your contribution graph.

For more information about the power of branches and pull requests, see "GitHub flow." For more information about getting started with GitHub, see the other guides in the getting started quickstart.

Help and support
Did this doc help you?

Privacy policy
Help us make these docs great!
All GitHub docs are open source. See something that's wrong or unclear? Submit a pull request.

Learn how to contribute

Still need help?
Ask the GitHub community
Contact support
Legal
© 2023 GitHub, Inc.
Terms
Privacy
Status
Pricing
Expert services
Blog

# glowing-umbrella
